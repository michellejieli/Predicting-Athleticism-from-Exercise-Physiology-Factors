# BME580 Final Project- Predicting Athleticism from Exercise Physiology Factors

### Abstract 
Oxygen consumption rate, or VO2, estimates the body’s ability to use oxygen during exercise, and is a good indicator of an individual’s health. However, VO2 is complex to calculate and measure, so this project aims to predict VO2 and athleticism from easily obtained exercise measurements using regression and classification models in a supervised learning approach. While regression seemed incompatible for predicting VO2, random forest worked best out of all the regression models we tried. Support vector machines (SVM) worked best to classify athleticism with an accuracy of 86%. Thus, we posed a solution to classify athleticism using easy to obtain metrics, which can help determine healthy living in rural areas without readily accessible healthcare. 

This repo contains: 

* 20220412_bme580project.Rmd - Code 
* png files - Visualization outputs from Rmd file
* classification_pipeline.py file - Entire classification pipeline from preprocessed scaled data to classification model evaluation and figure output

### Built With

* [R Markdown](https://rmarkdown.rstudio.com/)

### Install

This project requires **R** and the following R libraries installed:

- [tidyverse](https://www.tidyverse.org/)
- [psych](https://cran.r-project.org/web/packages/psych/index.html)
- [gridExtra](https://cran.r-project.org/web/packages/gridExtra/index.html)
- [caTools](https://cran.r-project.org/web/packages/caTools/index.html)
- [caret](https://cran.r-project.org/web/packages/caret/index.html)
- [lmtest](https://cran.r-project.org/web/packages/lmtest/index.html)
- [splines](https://www.rdocumentation.org/packages/splines/versions/3.6.2)
- [fastDummies](https://cran.r-project.org/web/packages/fastDummies/fastDummies.pdf)
- [mgcv](https://cran.r-project.org/web/packages/mgcv/index.html)
- [pracma](https://cran.r-project.org/web/packages/pracma/index.html)

You will also need to have software installed to run and execute a [R Markdown](https://www.rstudio.com/products/rstudio/download/).

### Data

We used data from “Treadmill Maximal Exercise Tests from the Exercise Physiology and Human Performance Lab of the University of Malaga,” published on December 10th, 2021. This is an open-access dataset of cardiorespiratory measurements and participant information available on the [PhysioNet Database](https://physionet.org/content/treadmill-exercise-cardioresp/1.0.1/).

### Contact
Michelle Li - michelle.li851@duke.edu or michelleli1999@berkeley.edu

### Contributors
Michelle Li, Ayush Shetty, and Ashu Raman
