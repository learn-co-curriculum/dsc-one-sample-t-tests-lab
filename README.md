

Following cohen's interpretation, one can confidently say that the sample mean shifts considerably towards the positive side as compared to the population mean, resulting in a large effect size. This also helps one conclude that training has a clear effect on the sales performance of the sales team when compared to pre-sales performance. 


### Exercise 1: 

Create a function in python `one_sample_ttest(sample, popmean, alpha)` that will take in a sample data(as the one given above),  the population mean and the alpha value to calculate and return the t-value, critical t-value and p-value for the sample and identify if the results are significant or not. 


```python
def one_sample_ttest(sample, popmean, alpha):

    # Visualize sample distribution for normality 

    
    # Population mean 

    # Sample mean (x̄) using NumPy mean()

    # Sample Stadrad Deviation (sigma) using Numpy
    
    # Degrees of freedom
    
    #Calculate the critical t-value
    
    #Calculate the t-value and p-value      
    
    #return results
    return None
```

### Exercise 2:

Use the function created in exercise 1 to answer the following analytical questions.

In a Python class, some of the students have taken online courses to improve their Python skills.
The scores of a random sample of 20 students who underwent the online- course, on a Python test are as follows: 

     [84.0, 92.4, 74.3, 79.4, 86.7, 75.3, 90.9, 86.1, 81.0, 85.1, 
      78.7, 73.5, 86.9, 87.4, 82.7, 81.9, 69.9, 77.2, 79.3, 83.3]

The mean score of the class before the test is 65. The teacher thinks that the online training has really helped the students and now they should perform better than the class (population) mean. Use this to set your null and alternate hypotheses.

1. Test to see if the sample mean is significantly different from 65 at the .05 level. Report the t and p values.
2. The researcher realizes that she accidentally recorded the score that should have been 80.9 as 90.9. Are these corrected scores significantly different from 65 at the .05 level?


```python

```

    Null hypothesis rejected. Results are statistically significant with t-value = 12.69 critical t-value = 3.579400148163749 and p-value = 1e-10



![png](index_files/index_3_1.png)


### Solution:


```python

```

    Null hypothesis rejected. Results are statistically significant with t-value = 13.2 critical t-value = 1.729132811521367 and p-value = 1e-10



![png](index_files/index_5_1.png)


## Summary

In this lesson, you saw a quick introduction to hypothesis testing using frequentists methods with t-values and p-values. You saw how a one sample t-test can be applied to contexts where the population mean is unknown and you have a limited amount of sample data. You looked at all the stages required for such hypothesis testing with a description of steps and also, how to perform these functions in Python. The lesson also briefly explains the comparison of using p-value for statistical significance vs. effect sizes. 


