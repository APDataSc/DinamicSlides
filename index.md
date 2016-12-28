---
title       : Presentaciones dinámicas HTML
subtitle    : DECON-INEC
author      : Andrés Peña M.
job         : APDSc®
framework   : io2012      # {io2012, html5slides, shower, dzslides, revealjs, deckjs, Landslide...}
#revealjs   :       {theme: moon, transition: concav}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap]            # {mathjax, quiz, bootstrap}
ext_widgets : {rCharts: [libraries/nvd3, libraries/dygraphs]}
mode        : selfcontained # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
logo        : logo.png
---

<style>
.title-slide {
  background-color: #B0E2FF; /* #EDE0CF; ; #CA9F9D*/
  background-image:url(assets/img/cover1st_1.png);
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
  position:relative; 
}

.title-slide hgroup {
  position: absolute;
  width: auto;
  height: auto;
  right: 80px;
  top: 80px;
  text-align: center;
}

.title-slide hgroup > h1 , 
.title-slide hgroup > h2 ,
.title-slide hgroup > p {
  margin: 15;
  color: white;
  text-align: right;
}

</style>

# .



### ¿Qué es el Índice de Precios al Consumidor Estratificado?

El Índice de Precios al Consumidor Estratificado, es una medida de variación del nivel general de precios de un conjunto representativo de bienes y servicios de consumo, adquiridos por los hogares clasificados en distintos segmentos socioeconómicos de la población. 

### Propósito:

Contribuye a una mejor representatividad socioeconómica frente a la heterogeneidad de precios a los que se enfrentan los hogares de distintas realidades. 

### Período base:

Diciembre 2015=100


---

## Matriz 


```r
(mtx <- matrix (1:12, nrow=3, ncol=4, byrow=FALSE))
```

```
##      [,1] [,2] [,3] [,4]
## [1,]    1    4    7   10
## [2,]    2    5    8   11
## [3,]    3    6    9   12
```

Toute la présentation a été réalisée avec le package R <code>slidify</code>
</div>

--- {class: class1, bg: gray, id: id1}

## Gráfico 1











