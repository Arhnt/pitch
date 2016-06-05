---
title       : Predicting Braking Distance
subtitle    : 
author      : Coursera Student
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## History
An autonomous car (driverless car, self-driving car, robotic car) is a vehicle that is capable of sensing its environment and navigating without human input.

1. Some demonstrative systems, precursory to autonomous cars, date back to the 1920s and 30s.
2. The first self-sufficient (and therefore, truly autonomous) cars appeared in the 1980s.
3. In July 2013, Vislab demonstrated BRAiVE, a vehicle that moved autonomously on a mixed traffic route open to public traffic

More information available at _https://en.wikipedia.org/wiki/Autonomous_car_

---

## Problem Definition
Autonomous vehicles detect surroundings using radar, lidar, GPS, Odometry, and computer vision. Advanced control systems interpret sensory information to identify appropriate navigation paths, as well as obstacles and relevant signage.

Various Regression models can be used in car systems to predict behaviour for surrounding cars based on inputs from sensors.

--- 

## Model
Simplified example of using regression model to predict braking distance by car speed

```r
model <- lm(dist ~ speed, data = cars)
```
![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png)

---

## Conclusion
Sensor modules market shows significant grow and Data science applications is essensial part of it.
!(1.jpg)
http://image-sensors-world.blogspot.com/2015/12/yole-report-on-autonomous-vehicles.html

