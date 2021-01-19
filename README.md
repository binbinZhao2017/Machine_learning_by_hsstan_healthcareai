# Machine_learning_by_hsstan_healthcareai

Abundance table is transformed by central log ratio (CLR) and normalized. Biomarker is then selected by hsstan package1 using default parameters. Abundance table of selected biomarker is implemented to machine learning model using healthcareai package2. Cross validation for three machine learning models including random forests, XGBoost, and regularized regression is executed and the best model is chosen for prediction.<br/>

Note:
The html file, generated by the Rmd file, is the analysis report and can open with browser (https://binbinzhao2017.github.io/Machine_learning_by_hsstan_healthcareai/16s_150samples_ML_20201120.html) <br/>

[1] Marco Colombo and Paul McKeigue (2020). hsstan: Hierarchical Shrinkage Stan Models for Biomarker Selection. R package version 0.8 https://CRAN.R-project.org/package=hsstan<br>
[2] Levi Thatcher, Michael Levy, Mike Mastanduno, Taylor Larsen, Taylor Miller and Rex Sumsion (2020). healthcareai: Tools for Healthcare Machine Learning. R package version 2.5.0. https://CRAN.R-project.org/package=healthcareai