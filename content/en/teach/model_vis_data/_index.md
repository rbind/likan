---
title: "R for Modeling and Visualizing Data"
author: "Likan"
date: '2017-09-01'
show_title: true
disable_comments: true
show_toc: true
---
# 1. Lecture Time and Location

- Time: Monday, 08:00 - 11:50;
- Starting Day: 18, SEP;
- Location: TBA

# 2. Prerequisites

Students of this course should be familiar with the basic concepts used in statistics, such as *Mean*, *Standard Deviation*, *Normal Distribution*, *t-statistic*, *ANOVA*, *F-ratio*, *p-value*, *Hypothesis Testing* etc. To acheive this, Students should have already finished some introductory courses in statistics, such as [Statistics for the Behavioral Sciences](/en/teach/stat_behav_sci/), or other courses at the same level. Students can learning these basic concepts by themselves.

# 3. Course Information

[R](https://cran.r-project.org) is a language and environment for **statistical computing** and **graphics**. It is a GNU project which is similar to the S language and environment which was developed at Bell Laboratories by John Chambers and colleagues. R provides a wide variety of statistical (linear and nonlinear modeling, classical statistical tests, time-series analysis, classification, clustering, …) and graphical techniques, and is highly extensible. One of R's strengths is the ease with which well-designed publication-quality plots can be produced, including mathematical symbols and formulae where needed.

Linear models, their variants, and extensions are among the most useful and widely used statistical tools for social research. This course aims to provide an accessible, in-depth, modern treatment of *regression analysis*, *linear models*, *generalized linear models*, and closely related methods.

# 4. References

- R manuals
    - [An Introduction to R](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf)
    - [R Data Import/Export](https://cran.r-project.org/doc/manuals/r-release/R-data.pdf)
    - [R Installation and Administration](https://cran.r-project.org/doc/manuals/r-release/R-admin.pdf)
    - [Writing R Extensions](https://cran.r-project.org/doc/manuals/r-release/R-exts.pdf)
    - [The R language definition](https://cran.r-project.org/doc/manuals/r-release/R-lang.pdf)
    - [R Internals](https://cran.r-project.org/doc/manuals/r-release/R-ints.pdf)
    - [The R reference Index](https://cran.r-project.org/doc/manuals/r-release/fullrefman.pdf)

- R language in General
    - Chambers, J. M. (2016). *Extending R*. Boca Baton, UK: CRC Press.
    - Wickham, H. (2015). *Advanced R*. Boca Baton, UK: CRC Press.
    - Wickham, H., & Grolemund, G. (2016). *R for Data Science: Import, Tidy, Transform, Visualize, and Model Data*. Sebastopol, CA: O’Reilly Media.


- R graphics
    - Murrell, P. (2011). *R Graphics* (2 ed.). Boca Raton, FL: CRC Press.
    - Kassambara, A. (2015). *Complete Guide to 3D Plots in R*: STHDA.
    - Wickham, H. (2009). *ggplot2: Elegant Graphics for Data Analysis*: Springer.

- Statistical models
    - Chambers, J. M., & Hastie, T. J. (Eds.). (1993). *Statistical Models in S*. London, UK: Champman & Hall.
    - **Fox, J. (2016). *Applied Regression Analysis and Generalized Linear Models* (3 ed.). Thousand Oaks, CA: SAGE.**
    - Venables, W. N., & Ripley, B. D. (2002). *Modern Applied Statistics with S*: Springer.
    - Bates, D., Mächler, M., Bolker, B., & Walker, S. (2015). Fitting Linear Mixed-Effects Models Using lme4. *Journal of Statistical Software, 67*(1). doi:10.18637/jss.v067.i01
    - Hastie, T. J., & Tibshirani, R. J. (1990). *Generalized additive models*. Landon, UK: Chapman and Hall.
    - Venables, W. N., & Ripley, B. D. (2002).  *Modern Applied Statistics with S*. Springer.
    - Wood, S. N. (2006). *Generalized Additive Models: an introduction with R*: CRC Press.

- Probability and statistics
    - Fieller, N. (2016). *Basics of matrix algebra for statistics with R*. Boca Raton, FL: CRC Press.
    - Poole, D. (2015). *Linear Algebra: A Modern Introduction* (4 ed.). Stamford, CT: Gengage Learning.
    - Ugarte, M. D., Militino, A. F., & Arnholt, A. T. (2016). *Probability and statistics with R* (2 ed.). Boca Raton, UK: CRC Press.
    - Stewart, J. (2016). *Calculus: Early transcendentals* (8 ed.). Boston, MA: Cengage Learning.

- Typesetting
    - Xie, Y. (2014). *Dynamic Documents with R and knitr* (2 ed.). Boca Raton, FL: CRC Press.


# 5. Syllabus, Lecture Notes, and Scripts

- Part 0: Introduction
    - 00. Course introduction, [slides](https://rmodelvis.likan.info/2017_CH_00.pdf);
    - 01. R basics
- Part I: Data craft
    - 02. Examining Data
    - 03. Transforming Data
- Part II: Linear models and least squares
    - 04. Linear least-squares regression
    - 05. Statistical Inference for Regression
    - 06. Dummy-variable regression
    - 07. Analysis of variance
- Part III: Linear-model diagnostics
    - 08. Unusual and influential data
    - 09. Non-Normality, Nonconstant Error Variance, and Nonlinearity
    - 10. Collinearity and Its Purported Remedies
- Part IV: Generalized linear models
    - 11. Logit and Probit Models for Categorical Response Variables
    - 12. Generalized Linear Models
- Part V. Extending Linear and Generalized Linear Models
    - 13. Time-Series Regression and Generalized Least Squares
    - 14. Nonlinear Regression
    - 15. Nonparametric Regression
    - 16. Bootstrapping Regression Models
- Part VI: Mixed-Effects Models
    - 17. Linear Mixed-Effects Models
    - 18. Generalized Linear and Nonlinear Mixed-Effects Models
