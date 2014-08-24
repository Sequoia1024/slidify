---
title       : Calculate BMI App
subtitle    : 
author      : Jiajuan Liu
job         : Coursera Learner
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

A simple App to calculate one's BMI given height and weight.

height -- in cm

weight -- in kg

Other units (feet/pounds) may come later

--- .class #id 

## BMI

Body Mass Index (BMI):
A measure of relative weight based on an individual's mass and height.

BMI = mass(kg)/((height(m))^2)

Category       BMI range - kg/m2
 
Underweight:    < 18.5
 
Normal weight: 	18.5 - 22.9
 
Overweight:   	23.0 - 29.9
 
Obese:	         >= 30.0

http://en.wikipedia.org/wiki/Body_mass_index

---.class #id

## BMI example

Assume weight = 60kg, height = 170cm:

```r
height = 170/100 #(in m)
weight = 60
bmi = weight/(height^2)
bmi
```

```
## [1] 20.76
```

Based on the result, this person has normal weight

---.class #id

## App at work
http://jjliu.shinyapps.io/8_DevelopingDataProducts/

Try it out!
