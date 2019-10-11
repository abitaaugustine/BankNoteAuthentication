# BankNoteAuthentication
## Using Multiple Linear regression to solve banknote authentication problem

To predict whether a given banknote is authentic given a number of measures taken from a photograph.

Dataset used - [**Banknote Authentication Data Set**](http://archive.ics.uci.edu/ml/datasets/banknote+authentication)

A binary classification problem. The dataset consists of 5 columns as follows: 

**Attributes:**
1.  Variance of Wavelet Transformed image (continuous).
2.  Skewness of Wavelet Transformed image (continuous).
3.  Kurtosis of Wavelet Transformed image (continuous).
4.  Entropy of image (continuous).

**Labels(Target)**

5.  Output (0 for authentic, 1 for inauthentic).

### Load the dataset
Load dataset into a pandas dataframe from the csv file.
### Analyse the data
Using scatter matrix.
### Prepare the data
Break the data (labels and attributes) into two subsets: a test set and a training set.
### Create the model
Using Linear Regression.
### Train the model
Train the classifier using training set.
### Evaluate the model
Evaluate using test set. <br />
Generate confusion matrix for varying threshold values. <br />
Calculate misclassification rate. <br />
Calculate area under ROC. <br />


