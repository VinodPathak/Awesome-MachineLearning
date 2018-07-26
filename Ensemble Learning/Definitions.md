### Ensemble Learning  
> Combine Several Base models to produde optimal predictive model.  
Comprehensive guide on Ensemble Learning  
>> https://www.analyticsvidhya.com/blog/2018/06/comprehensive-guide-for-ensemble-models/  

Primer for Ensemble Learning Bagging and Boosting  
>> https://analyticsindiamag.com/primer-ensemble-learning-bagging-boosting/  

>> Meta Algorithms:- Learning how to learn  
>> MAML:- Model Agnostic Meta Learning  

1. Bagging
2. Boosting
3. Stacking

#### Ensemble Methods:   
1. Sequential Ensemble Methods:- AdaBoost, Exploit the dependence between the base Learners. Weighing previousy mislabeled examples with higher weight.  
2. Parallel Ensemble Methods:- Exploit the Independence Between Base Learners. Error Reduced by averaging.  

### Bagging Note:  
1. Stable Learners are not fit as they don't include generlization.  
2. Random Forest:- sampling with replacement and feature sampling. Bias increases but variance decreases because of averaing less   correlated trees.  
3. Extremely Randomized Trees: Splitting Threshold are randomized.  

#### Boosting Note:  
1. Fit a sequence of weak Learners.  
2. Base LEarners are trained in a sequence on weighted version of data.  

#### Stacking Note:  
1.Combining multiple classifier or regressor models via a meta classifier or regressor  

### Links  
> https://towardsdatascience.com/ensemble-methods-in-machine-learning-what-are-they-and-why-use-them-68ec3f9fef5f  
> https://blog.statsbot.co/ensemble-learning-d1dcd548e936  
