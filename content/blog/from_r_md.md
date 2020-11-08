---
title: "newmd"
author: 'null'
date: '2020-11-08'
output: pdf_document
categories: []
tags: []
draft: yes
slug: []
---


Let's add a table, just for kicks.

| hours of sun | happiness |
|---|---|
| 0 | 1 |
| 3 | 4 |
| 5 | 7 |
| 7 | 10 |


```{r}

mean(iris$Sepal.Length)
require(ggplot2)
ggplot(iris, aes(Sepal.Length, Sepal.Width, color = Species)) +
  geom_point() +
  geom_smooth(method = "lm") + 
  scale_color_manual(values = c("#3B9AB2", "#E4B80E", "#F21A00"))
  

```

