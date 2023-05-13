# NIRS
Using of classic ML methods for prediction of key feature.
A standard data set of Titanic survivors from the site was selected for the input data kaggle.com . 

The purpose of the work is to study and test the effectiveness of some forecasting methods.
It is necessary to study the most popular optimization methods: Logistic regression, k nearest neighbors, linear support/support vector machine, naive Bayesian classifier, 
decision tree, random forest, perceptron, stochastic gradient descent. 
To study their advantages and disadvantages, and on the basis of the data obtained to draw a conclusion about the effectiveness of the methods considered.

Before proceeding to the analysis of statistical forecasting methods, let's consider some general concepts and definitions related to correlation and regression models. Two random variables are correlationally related if the mathematical expectation of one of them changes depending on the change in the other.
The use of correlation analysis assumes the following prerequisites:
a) Individual observations are stachostically independent, i.e. the value of this observation should not depend on the value of the previous and subsequent observations.
b) The covariance between the error associated with one value of the dependent variable y and the error associated with any other value y is zero.
c) The variance of the error associated with one value of y is equal to the variance of the error associated with any other value.
d) The covariance between the error and each of the independent variables is zero.
e) The direct applicability of this method is limited to cases when the equation of the curve is linear with respect to its parameters bo, bi, ...,bk, However, this does not mean that the equation of the curve itself with respect to variables should be linear. If the empirical equations of observations are not linear, then in many cases it is possible to bring them to a linear form and already. after that, apply the least squares method.

f) Observations of independent variables are made without error.

Before starting the correlation analysis, it is necessary to check the fulfillment of these prerequisites.

The relationship between random and non—random variables is called regression, and the method of analyzing such relationships is called regression analysis. The use of regression analysis implies the mandatory fulfillment of the prerequisites (b-d) of correlation analysis. Only when the above prerequisites are fulfilled, the estimates of the correlation and regression coefficients obtained using the least squares method will be unbiased and have minimal variance.
Regression analysis is closely related to correlation analysis. When the prerequisites of correlation analysis are fulfilled, the prerequisites of regression analysis are fulfilled. At the same time, regression analysis imposes less stringent requirements on the initial information."
For example, regression analysis is possible even if the distribution of a random variable differs from the normal one, as is often the case for technical and economic quantities. A random variable is used as a dependent variable in regression analysis, and a non—random variable is used as an independent variable.
According to the degree of complexity, statistical studies can be divided into two-dimensional and multidimensional. The first concern the consideration of paired relationships between variables (paired correlations and regressions) and are aimed in predictive research at solving such problems as establishing a quantitative measure of the closeness of the relationship between two random variables, establishing the proximity of this relationship to a linear one, assessing the reliability and accuracy of forecasts obtained by extrapolation of regression dependence. 
Multidimensional methods of statistical analysis are mainly aimed at solving the problem of system analysis of multidimensional stochastic forecasting objects. The purpose of such an analysis is, as a rule, to clarify the internal relationships between the variables of the complex, to construct multidimensional functions of the connection of variables, to highlight the minimum number of characteristics describing the object with a sufficient degree of accuracy. One of the main tasks here is to reduce the dimensionality of the description of the forecasting object.
Thus, statistical methods are mainly used to prepare data, to bring them to a form suitable for making a forecast. As a rule, after their application, one of the extrapolation or interpolation methods is used to obtain a directly predictive result.
