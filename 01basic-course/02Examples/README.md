# Basic Course Examples

## Machine Learning

- [Basics](02Examples/learn)
   - Learn GGPLOT fundamentals $\rightarrow$ [Rmd](02Examples/learn/learn_GGPLOT.Rmd), [html](02Examples/learn/learn_GGPLOT.html)
   - Learn R data structures $\rightarrow$ [Rmd](02Examples/learn/R-data-struct.Rmd), [html](02Examples/learn/R-data-struct.html)
   - Learn basic EDA and Notebooks in R $\rightarrow$ [pdf](02Examples/learn/learn_NB_EDA.pdf)
- Exploratory Data Analysis
   - Crabs: explores crab species data in R $\rightarrow$ [html](02Examples/EDA_crabs/EDA_crabs.html)
   - Diabetes: a very complete EDA of clinical [data](02Examples/EDA_diabetes/pima-indians-diabetes.csv) $\rightarrow$  [notebook](02Examples/EDA_diabetes/pima-indians-diabetes-EDA.ipynb), [html](02Examples/EDA_diabetes/pima-indians-diabetes-EDA.html)
 - Linear Regression
   - Photosynthesis: we fit a simple linear regression and then a nonlinear transformation to plant photosynthesis data $\rightarrow$ [md](l02Examples/in_reg_photo/lin_reg_photo.md), [Rmd](02Examples/lin_reg_photo/lin_reg_photo.Rmd), [data](02Examples/lin_reg_photo/photo.csv)
   - Concrete: comparison between simple and multiple regression on a database with quantitative and categorical variables, with generation of a surrogate model $\rightarrow$  [data](02Examples/mlreg_concrete/ConcreteStrenght.csv), [notebook](02Examples/mlreg_concrete/mlreg_concrete.ipynb), [md](02Examples/mlreg_concrete/mlreg_concrete.md), [pdf](02Examples/mlreg_concrete/mlreg_concrete.pdf)
 - SVM Regression: nonlinear regression with a radial kernel for LIDAR data $\rightarrow$  [Rmd](02Examples/svm_reg/svm_reg.Rmd), [html](02Examples/svm_regsvm_reg.html), [markdown](02Examples/svm_regsvm_reg.md)
 - Classification
    - k-NN classifier for `iris` data: fit a simple classifier to multi-species data  $\rightarrow$  [Rmd](02Examples/k_nn_iris/k_nn_iris_md.Rmd), [html](02Examples/k_nn_iris/k_nn_iris.html), [markdown](02Examples/k_nn_iris/k_nn_iris_md.md)
	- SVM classifier for  `iris` data: EDA and feature selection $\rightarrow$ [Rmd](02Examples/svm_iris/svm_iris.Rmd), [html](02Examples/svm_iris/svm_iris.html), [markdown](02Examples/svm_iris/svm_iris.md)
- Neural Networks
   - Squares: train a simple NN to learn the rule of squares for the first 10 integers $\rightarrow$ [data](02Examples/nnet_squares/squares.csv), [Rmd](02Examples/nnet_squares/nnet_squares.Rmd), [html](02Examples/nnet_squares/nnet_squares.html), [markdown](02Examples/nnet_squares/nnet_squares.md)
   - Wine: train a NN classifier to detect fraud on wine denomination, using chemical composition data $\rightarrow$  [data](02Examples/nnet_MLP_wine/wine_data.csv), [notebook](02Examples/nnet_MLP_wine/nnet_MLP_wine.ipynb), [md](02Examples/nnet_MLP_wine/nnet_MLP_wine.md), [html](02Examples/nnet_MLP_wine/nnet_MLP_wine.html)
- Unsupervised learning
   - k-means on a simple example with Gaussian blobs  
        - R version $\rightarrow$ [Rmd](02Examples/k_means/k_means_simple.Rmd), [markdown](02Examples/k_means/k_means_simple.md), [html](02Examples/k_means/k_means_simple.html)
		- Python version $\rightarrow$ [notebook](02Examples/k_means/k_means_skl.ipynb), [markdown](02Examples/k_means/k_means_skl/k_means_skl.md), [html](02Examples/k_means/k_means_skl.html)

- Cross-validation and Tuning
   - Comparison of CV methods with `caret` $\rightarrow$ [Rmd](02Examples/CV/CV_caret.Rmd), [html](02Examples/CV/CV_caret.html), [markdown](02Examples/CV/CV_caret.md)
   - Tuning of k-nn model with `iris` data $\rightarrow$ [R](02Examples/CV/CV_k_nn_iris.R), [html](02Examples/CV/CV_k_nn_iris.html)
   - Model selection and tuniing using SVM on `iris` data $\rightarrow$ [Rmd](02Examples/CV/TUNE_svm_iris.Rmd), [html](02Examples/CV/TUNE_svm_iris.html), [markdown](02Examples/CV/TUNE_svm_iris.md)
   - [Tuning a NN](02Examples/CV/TUNE_nn_class_caret) using `caret` on `iris` data  $\rightarrow$ see the linked folder for data and all files.
   - CV and tuning with python (`sklearn`) $\rightarrow$ [notebook](02Examples/CV/CV_RF_sklearn.ipynb), [html](02Examples/CV/CV_RF_sklearn.html), [markdown](02Examples/CV/CV_RF_sklearn.md)



## Data Assimilation

### Variational DA

Variational DA, based on adjoint methods, is complicated to code. We recommend to rather use the reliable open-source code repositories that are referenced in the DA [Lecture](https://github.com/markasch/CSU-IMU-2023/blob/main/01basic-course/01Lectures/12_DA_var.pdf).


### Statistical DA

Statistical DA is less complex to code, in particular in the form of simple Kalman Filters. Extensions of the KF will be studied in the [Advanced Course](https://sites.google.com/view/csu2023/advanced-course), which should be consulted for more details and examples.