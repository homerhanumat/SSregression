## About `SSregression`

[![GitHub version](https://badge.fury.io/gh/paternogbc%2FSSregression.svg)](http://badge.fury.io/gh/paternogbc%2FSSregression)


This interactive application allows you to explore how Sums of Squares are calculated in simple linear regressions. Change one of the parameters to see what happens.

Check this application online: [SSregression](https://paternogbc.shinyapps.io/SS_regression)

## Run this application on R Studio

Before you run, install the following R packages:

```{r} 
install.packages(shiny)
install.packages(ggplot2)
install.packages(shinydashboard)
install.packages(grid)
install.packages(markdown)
install.packages(ggExtra)
install.packages(DT)
```

To run this application localy, simple paste the following code on `R` console: 
```{r} 
 shiny::runGitHub("SSregression", "paternogbc")
```

![](http://i.imgur.com/d6i4LGy.png)


## Want to help?
Fork this repo and create a pull request. Please, report bugs [here](https://github.com/paternogbc/SSregression/issues).


## License
This software is Open Source and is under the public license [GPL-3.0](http://www.gnu.org/licenses/gpl-3.0.en.html)

![logo](https://raw.githubusercontent.com/paternogbc/SSregression/master/www/logo.png) 

_The OSI logo trademark is the trademark of [Open Source Initiative](http://opensource.org/)_

## Author
Gustavo Paterno | paternogc@gmail.com

## Credit

This application was developed with [shiny](http://shiny.rstudio.com/) in 
[R studio](https://www.rstudio.com/).

