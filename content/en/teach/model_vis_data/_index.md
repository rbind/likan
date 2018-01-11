---
title: "R for Modeling and Visualizing Data"
author: "Likan"
date: '2017-09-01'
show_title: true
disable_comments: true
show_toc: true
---
# 1. Lecture Time and Location

- Time: 08:00 - 10:50, Monday;
- Location: Room 206, Teaching Building 2;

# 2. Prerequisites

Students of this course should be familiar with the basic concepts used in statistics, such as *Mean*, *Standard Deviation*, *Normal Distribution*, *t-statistic*, *ANOVA*, *F-ratio*, [*p-value*](https://likan.info/cn/post/2017-08-11-p-values-bayes-factor/), *Hypothesis Testing* etc. To acheive this, Students should have already finished some introductory courses in statistics, such as [Statistics for the Behavioral Sciences](/en/teach/stat_behav_sci/), or other courses at the same level. Students can also learn these basic concepts by themselves.

# 3. Course Information

[R](https://cran.r-project.org) is a language and environment for **statistical computing** and **graphics**. It is a GNU project which is similar to the S language and environment which was developed at Bell Laboratories by John Chambers and colleagues. R provides a wide variety of statistical (linear and nonlinear modeling, classical statistical tests, time-series analysis, classification, clustering, …) and graphical techniques, and is highly extensible. One of R's strengths is the ease with which well-designed publication-quality plots can be produced, including mathematical symbols and formulae where needed.

Linear models, their variants, and extensions are among the most useful and widely used statistical tools for social research. This course aims to provide an accessible, in-depth, modern treatment of *regression analysis*, *linear models*, *generalized linear models*, and closely related methods.

# 4. Final Examination

- To sucessfully complete the examination, your computer should have already installed the *R* software and the *R studio* software. One extra package, i.e., *car* should have also been installed before you attend this examination.
- The exanimation paper and the data set used in the final examination are avaliable from **2018-01-11, 0900** to **2018-01-15, 0900**.
- Download the two files from the following links: [*`Final_Examination_Formal.Rmd`*](https://rmodelvis.likan.info/Final_Examination_Formal.Rmd) file and the data set file [Titanic.txt](https://rmodelvis.likan.info/Titanic.txt).
- Rename the `Rmd` file into the following format *`SurnameGivenname_Student number.Rmd`* in Pinyin, such as *`ZhangSan_20170708.Rmd`*.
- Open the renamed *`.Rmd`* file with *`RStudio`*.
- Change the *`Name-Number`* region in the front matter of the *`Rmd`* file to your own name in Chinese characters and your student number, such as *`张三 - 20170708`*.
- Write your *R* code in the region enclosed by *···{r} XXX ···*, i.e. the XXX area.
Write your answers that don't include R code out of the region enclosed by *···{r} XXX ···*.
For more information concerning on the syntax of *Markdown* and *Rmarkdown*, please download the [Markdown](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) cheatsheet and the  [R markdown](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf) cheatsheet.
- Question **one** is mandatory. The remaining 5 questions are optional, you can choose any and only **three** questions from question 2 to question 6 to answer.
- After finishing all your answers, click the *`knit to HTML`* button in the *`knit`* drop-down menu of *`RStudio`*.
- Send both the filled *`.Rmd`* file and the knitted *`.html`* file to the following email address: `zhanlikan@blcu.edu.cn` before **2018-01-15, 0900**.

# 5. Tools

- [An interactive learning widget for R](/en/teach/model_vis_data/InteractiveR/)

# 6. Syllabus and Lecture Notes

- Part 0: Introduction
    - 01. Course introduction, [slides](https://rmodelvis.likan.info/2017_CH_01.pdf);
    - 02. R basics, [slides](https://rmodelvis.likan.info/2017_CH_02.pdf);
- Part I: Data craft
    - 03. Examining Data, [slides](https://rmodelvis.likan.info/2017_CH_03.pdf);
    - 04. Transforming Data, [slides](https://rmodelvis.likan.info/2017_CH_04.pdf);
- Part II: Linear models and least squares
    - 05. Linear least-squares regression, [slides](https://rmodelvis.likan.info/2017_CH_05.pdf);
    - 06. Statistical Inference for Regression, [slides](https://rmodelvis.likan.info/2017_CH_06.pdf);
    - 07. Dummy-variable regression, [slides](https://rmodelvis.likan.info/2017_CH_07.pdf);
    - 08. Analysis of variance, [slides](https://rmodelvis.likan.info/2017_CH_08.pdf),  [data](https://socialsciences.mcmaster.ca/jfox/Books/Applied-Regression-3E/datasets/Vocabulary-2.txt)
- Part III: Linear-model diagnostics
    - 09. Unusual and influential data, [slides](https://rmodelvis.likan.info/2017_CH_09.pdf)
    - 10. Non-Normality, Nonconstant Error Variance, and Nonlinearity
    - 11. Collinearity and Its Purported Remedies
- Part IV: Generalized linear models
    - 12. Logit and Probit Models for Categorical Response Variables, [slides](https://rmodelvis.likan.info/2017_CH_12.pdf)
    - 13. Generalized Linear Models
- Part V. Extending Linear and Generalized Linear Models
    - 14. Time-Series Regression and Generalized Least Squares
    - 15. Nonlinear Regression
    - 16. Nonparametric Regression
    - 17. Bootstrapping Regression Models
- Part VI: Mixed-Effects Models
    - 18. Linear Mixed-Effects Models
    - 19. Generalized Linear and Nonlinear Mixed-Effects Models


# 7. References

- R manuals
    - An Introduction to R, [Full text](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf)
    - R Data Import/Export, [Full text](https://cran.r-project.org/doc/manuals/r-release/R-data.pdf)
    - R Installation and Administration, [Full text](https://cran.r-project.org/doc/manuals/r-release/R-admin.pdf)
    - Writing R Extensions, [Full text](https://cran.r-project.org/doc/manuals/r-release/R-exts.pdf)
    - The R language definition, [Full text](https://cran.r-project.org/doc/manuals/r-release/R-lang.pdf)
    - R Internals, [Full text](https://cran.r-project.org/doc/manuals/r-release/R-ints.pdf)
    - The R reference Index, [Full text](https://cran.r-project.org/doc/manuals/r-release/fullrefman.pdf)

- R language in General
    - Becker, R. A., Chambers, J. M., & Wilks, A. R. (1988). *The New S Language: A Programming Environment for Data Analysis and Statistics*. Pacific Grove , CA : Wadsworth. (The **Blue** book)
    - Chambers, J. M. (1998). *Programming with data: A guide to the S language*. New York, NY: Springer. (The **Green** book)
    - Chambers, J. M. (2016). *Extending R*. Boca Baton, UK: CRC Press.
    - Wickham, H. (2015). *Advanced R*. Boca Baton, UK: CRC Press. [Full text](http://adv-r.had.co.nz)
    - Wickham, H., & Grolemund, G. (2016). *R for Data Science: Import, Tidy, Transform, Visualize, and Model Data*. Sebastopol, CA: O’Reilly Media. [Full text](http://r4ds.had.co.nz)

- R graphics
    - Murrell, P. (2011). *R Graphics* (2 ed.). Boca Raton, FL: CRC Press.
    - Kassambara, A. (2015). *Complete Guide to 3D Plots in R*: STHDA.
    - Wickham, H. (2009). *ggplot2: Elegant Graphics for Data Analysis*. New York, NY: Springer.

- Statistical models
    - Chambers, J. M., & Hastie, T. J. (Eds.). (1993). *Statistical Models in S*. London, UK: Champman & Hall. (The **White** book)
    - **Fox, J. (2016). *Applied Regression Analysis and Generalized Linear Models* (3 ed.). Thousand Oaks, CA: SAGE.**
    - Hastie, T. J., & Tibshirani, R. J. (1990). *Generalized additive models*. Landon, UK: Chapman and Hall.
    - Venables, W. N., & Ripley, B. D. (2002).  *Modern Applied Statistics with S*. Springer.
    - Wood, S. N. (2006). *Generalized Additive Models: an introduction with R*: CRC Press.
    - Bates, D., Mächler, M., Bolker, B., & Walker, S. (2015). Fitting Linear Mixed-Effects Models Using lme4. *Journal of Statistical Software, 67*(1). doi:10.18637/jss.v067.i01

- Probability and statistics
    - Fieller, N. (2016). *Basics of matrix algebra for statistics with R*. Boca Raton, FL: CRC Press.
    - Poole, D. (2015). *Linear Algebra: A Modern Introduction* (4 ed.). Stamford, CT: Gengage Learning.
    - Ugarte, M. D., Militino, A. F., & Arnholt, A. T. (2016). *Probability and statistics with R* (2 ed.). Boca Raton, UK: CRC Press.
    - Stewart, J. (2016). *Calculus: Early transcendentals* (8 ed.). Boston, MA: Cengage Learning.

- Typesetting
    - Xie, Y. (2014). *Dynamic Documents with R and knitr* (2 ed.). Boca Raton, FL: CRC Press.
