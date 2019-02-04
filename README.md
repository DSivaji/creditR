# creditR
## A Credit Risk Scoring and Validation Package

This package covers R functions related to the applications used in credit risk scoring. The package includes variable analysis, variable selection, model development, model calibration, rating scale and model validation methods. Through defined functions, methodologies can be applied quickly for all modeling data or a specific variable.The package was issued for the use of credit risk professionals. For the use of the package, basic level knowledge about credit risk scoring methodologies is required.
### Prerequisites
In order to install the creditR package, devtools package must also be installed. You should run the following code to install the devtools package.
```
install.packages("devtools", dependencies = TRUE) 
```

### Getting Started
You can install the creditR package with the help of install_github code by using devtools package.
```
library(devtools)
install_github("ayhandis/creditR)
library(creditR)
```

### A List of Functions
The list of functions available under the package is shared below.

 [1] "Adjusted.Binomial.test"              "Adjusted.Herfindahl.Hirschman.Index" "Anchor.point"                       
 [4] "bayesian.calibration"                "Binomial.test"                       "chisquare.test"                     
 [7] "correlation.cluster"                 "Gini.univariate"                     "Gini.univariate.data"               
[10] "Gini_elimination"                    "Herfindahl.Hirschman.Index"          "IV.calc"                            
[13] "IV.calc.data"                        "IV_elimination"                      "k.fold.cross.validation.glm"        
[16] "Kolmogorov.Smirnov"                  "master.scale"                        "missing_elimination"                
[19] "missing_ratio"                       "na_checker"                          "na_filler_contvar"                  
[22] "PSI.calc"                            "PSI.calc.data"                       "regression.calibration"             
[25] "scaled.score"                        "SSI.calc"                            "SSI.calc.data"                      
[28] "train_test_balanced_split"           "train_test_split"                    "variable.clustering"                
[31] "variable.clustering.gini"            "vif.calc"                            "woe.get.clear.data"                 
[34] "woe.glm.feature.importance"          "woe.table.calc"

### An Application of the Package
An example application of the package is shared below. It is just a study of how functions can be applied.

```
Give an example
```

## Bug Fixes

Please inform me via the e-mail address in the Author section for the errors encountered in the use of the package.

## Author

* **Ayhan Dis**  - [Github](https://github.com/ayhandis) - [Linkedin](https://www.linkedin.com/in/ayhandis/)  - disayhan@gmail.com

## License

This project is licensed under the GPL-2 - see the [LICENSE.md](LICENSE.md) file for details

### Built With

* [R](https://cran.r-project.org/)
* [R Studio](https://www.rstudio.com/) 
