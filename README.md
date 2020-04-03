[<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/banner.png" width="888" alt="Visit QuantNet">](http://quantlet.de/)

## [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/qloqo.png" alt="Visit QuantNet">](http://quantlet.de/) **SCGScagnostics** [<img src="https://github.com/QuantLet/Styleguide-and-FAQ/blob/master/pictures/QN2.png" width="60" alt="Visit QuantNet 2.0">](http://quantlet.de/)

```yaml


Name of Quantlet: Wetter-Scagnostics

Published in: SCG_Scagnostics

Description: "Calculates the scagnostic measures for the dataset and plots the SPLOM, the scagnostics SPLOM and the heat-map of the scagnostic measures"

Keywords: 'scagnostics, scagnostic coefficients, SPLOM, heat-map'

Author: Alina Kohlmayer & Michaela Kordasch

Submitted:  Fri, April 3 2020 by Alina Kohlmayer

Datafile: Wetter_Semlach_20200402.csv

```

![Picture1](cvalues_tempwindspeed.png)

![Picture2](DT_MST.png)

![Picture3](Edgedistribution.png)

![Picture4](Heatmap.png)

![Picture5](scatterplot.png)

![Picture6](SPLOM.png)

![Picture7](temp_vs_windspeed.png)

### R Code
```r


# Packages needed ---------------------------------------------------------

install.packages("rJava")
install.packages("lattice")
install.packages("alphahull")
install.packages("scagnostics")
install.packages("tripack")
install.packages("RTriangle")
install.packages("igraph")
install.packages("psych")
install.packages("gplots")
install.packages("RColorBrewer")

# Library -----------------------------------------------------------------

library(rJava)
library(lattice)
library(alphahull)
library(scagnostics)
library(tripack)
library(RTriangle)
library(igraph)
library(psych)
library(gplots)
library(RColorBrewer)


```

automatically created on 2019-02-06