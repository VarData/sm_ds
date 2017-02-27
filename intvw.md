1. Why did you selected that as a feature? Multiple times means he was not satisfied with my answer.
2. What is confusion matrix.
3. What is ROC Curve?
4. How to select feature? What was the reason behind selecting experience range as feature.
5. PCA, Dimensionality reduction.
6. Which model did you built (Decision Tree, Logistic Regression, Random Forrest.


7. What are some imputing algorithms to replace missing values from data set?



## Stats:-
1. Why not absolute value in variance?

http://stats.stackexchange.com/questions/118/why-square-the-difference-instead-of-taking-the-absolute-value-in-standard-devia

The population variance is the sum of the squared deviations of all of the values in the population divided by the number of values in the population. When we are estimating the variance of a population from a sample, though, we encounter the problem that the deviations of the sample values from the mean of the sample are, on average, a little less than the deviations of those sample values from the (unknown) true population mean. That results in a variance calculated from the sample being a little less than the true population variance. Using an n-1 divisor instead of n corrects for that underestimation.

http://stats.stackexchange.com/questions/17890/what-is-the-difference-between-n-and-n-1-in-calculating-population-variance

### The benefits of squaring include:
2. Squaring always gives a positive value, so the sum will not be zero.
3. Squaring emphasizes larger differences - a feature that turns out to be both good and bad (think of the effect outliers have).



4. Why divide by n-1 to variance?
5. What is trimmed mean and why to use it?


https://www.otexts.org/fpp/6/1

Time series forecasting with ARIMA, and default parameters.
