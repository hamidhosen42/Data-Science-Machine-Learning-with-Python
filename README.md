"# Data-Science-Machine-Learning-with-Python"

### Machine-Learning-Formulas

1. Naive Bayes

$$ P (A | C) = \frac{P(C | A) \times P(A)}{P(C)} $$

2. Bayes Optimal Classifier

$$ arg \ max\sum p(x|T) \times P(T|D)$$

3. Naive Bayes Classifier 

$$ arg \ max P(Spo|Tot) \times \prod P(Soc|Spo) $$

4. Bayes Map (Maximum a posteriori)

$$ h_{map} = arg \ max P(c|a) \times P(a) $$

5. Maximum Likelihood

$$ h_{ML}  = arg \ max P(c|a) $$

6. Total probability

$$ Total P(B) = P(B|A) \times P(A) $$

7. Mixture Models

$$ P(B) = P(B|A) \times P(A)$$

8. Mixture of Guassians Anomaly Detection

$$ P(x|\bar{x}) = \frac{1}{\sqrt{2\pi\\sigma^2}} \times exp [-\frac{1}{2}(\frac{x - \bar{x}}{\sigma})^2]$$
$$ Z_{cs} = \frac{N_{A}C_{B} + N_{B}C_{A}}{N_{A} + C_{B}}$$
$$ P(Z_{cs}) \rightarrow  0.50$$

9. EM Algorithm

$$ E \ step \ P(\bar{x}|x) = \frac{P(\bar{x}) \times P(x|\bar{x})}{\sum P(x) \times P(\bar{x})} $$
$$ M \ step \ P(x^{\prime}) = \frac{P(\bar{x}|x)}{n}$$
$$ E \ step  \ P(\bar{x}|x) = Assign \ Value $$
$$ M \ step  \ P(x^{\prime}) = P(B = 1 | A = 1 , C = 0 )$$

10. Laplace Estimate (Small Samples)

$$ P(A) = \frac{A \ + \ 0.5}{A \ + B \ + \ 1 }$$

11. Bayesian Networks

$$ tuples \ \neg for \ y \ = \ 0 \ \land \ y \ = \ 1$$

12. Limits 

$$ \lim_{h \to 0} \frac{f(x + h) - f(x)}{h} $$
$$ h = \Delta{x} \ = \ x^{\prime} \ - \ x  $$

13. Derivatives

$$  \frac{d}{dx}{x}^n = n.x^{n-1} $$
$$ \frac{d}{dx}{y}^n = \frac{d{y}^n}{dy}.\frac{dy}{dx} $$

14. Product Rule

$$ \frac{d}{dx}f(x).g(x) = f^{\prime}(x).g(x) + f(x).g^{\prime}(x)$$
$$ \frac{d}{dx}\frac{f(x)}{g(x)} = \frac{ f^{\prime}(x).g(x) + f(x).g^{\prime}(x)}{g(x)^2}$$
$$ \frac{d}{dx}2f(x) = 2\frac{d}{dx}f(x) $$
$$ \frac{d}{dx}f(x)+g(x) = \frac{d}{dx}f(x) + \frac{d}{dx}g(x) $$
$$ \frac{d}{dx}f(x)+2g(x) = \frac{d}{dx}f(x) + 2\frac{d}{dx}g(x) $$

15. Chain Rule

$$ \frac{d}{dx}g(f(x)) = g^{\prime}(f(x)).f^{\prime}(x)$$

16. Variance

$$ var = \frac{\sum(x-\bar{x})^2}{n-1}$$

17. Standard Deviation

$$ \sigma = \sqrt{variance}$$

18. Covariance

$$ Cov = \frac{(x-\bar{x}).(y-\bar{y})}{n-1} $$

19. Confidence Interval

$$ x \ \textpm \ 1.96\frac{\sigma}{\sqrt{n}}$$

20. Chi Squared

$$ Chi = \frac{(\hat{y} - y)^2}{\sqrt{y}} = \frac{\delta^2}{\sqrt{y}} $$

21. R Squared

$$ R^2 = \frac{n\sum{xy} - \sum{x}.\sum{y}}{\sqrt{(n\sum{x}^2 - (\sum{x})^2).(n\sum{y}^2 - (\sum{y})^2)}}$$

22. Loss

$$ Loss = {Bais}^2 + {Variance}^2 + Noise$$

23. Sum of Squared Errors

$$ E|\overrightarrow{w}| = \frac{\sum{(\hat{y}-y)^2}}{2}$$

24. Cost Function

$$ J(\theta_j) = \theta_j - \eta.\frac{\sum{(\hat{y}-y)^2}}{2} $$

25. Number of examples

$$ m \geq \frac{log(N_H)+log(\frac{1}{\delta})}{\in} $$
where,
$$ \in = \frac{\hat{y}}{y}$$ and $$ \delta = y - \hat{y}$$

26. Markov Chains

$$ p^{t+1}(X = x) = \sum_xp^t.(X = x).T(x \to x)$$

27. K Nearest Neighbor

$$ \hat{f}(x) \leftarrow \frac{\sum{f(x)}}{k}$$
$$ DE(x_i, x_j) = \sqrt{(x_i - x_j)^2 + (y_{xi} - y_{xj})^2}$$

28. Weighed Nearest Neighbor

$$ f(x) = \sum{\frac{f(x)}{D(x_1x_2)^2}. \sum D(x_1x_2)^2}$$

29. Principal Components Analysis

$$ x^{'}= x - \bar{x}$$
$$ Eigenvalue = [A] - \lambda{I} $$
$$ EigenVector = Eigenvalue.[A]$$
$$ f(x) = Eigenvector^{T}.[x_{i1}.....x{jn}] $$

30. Linear Regression

$$ m_1 = \frac{\sum x_2^{\ 2} \sum x_{1}y - \sum x_1x_2 \sum x_2y}{\sum x_1^{\ 2} \sum x_2^{\ 2} - (\sum x_1x_2)^2} $$
$$ b = \bar{y} - m_1 \bar{x}_1 - m_2 \bar{x}_2 $$ 

$$ f(x) = \sum_{i=1}^{n}m_ix_i \ + \ b $$

31. Logistic Regression Formula

$$dds \ Ratio = log(\frac{p}{1 - p} = mx \ + \ b) $$
$$ (\frac{p}{1 - p}) = e^{mx + b}  $$
$$ \{J}(\theta) = - \frac{\sum y . log(\hat{y}) + (1 - y).log(1 - (\hat{y})}{n} $$

where,
$\hat{y} = \frac{1}{1 + e^{mx + b}}$
for y = 0 and y = 1 

-2LL $\rightarrow 0$

$\bar{x}_1 \sim \bar{x}_2 \ne \bar{x}_1^{\ '} \sim \bar{x}_2^{\ '}$

$mx +b = \frac{p}{1 - p}$
$p(a|c) = \frac{mx+b}{mx + b + 1}$

$logit = \frac{1}{100.log(p(a|c))}$

32. Decision Trees

$$ Entropy = $$


## ID3 Algorithm in Decision Tree :
   ID3 algorithm stands for Iterative Dichotomiser 3, which is a classification algorithm that follows a greedy approach of building a decision tree by selecting the best attribute that yields maximum Information Gain (IG) or minimum Entropy (H).

We will go through the basics of the decision tree, ID3 algorithm before applying it to our data. We will answer the following questions:

1. What is a decision tree?
2. What is the ID3 algorithm?
3. What is information gain and entropy?
4. What are the steps in the ID3 algorithm?
5. Using ID3 algorithm on a real data
6. What are the characteristics of the ID3 algorithm?

What is a Decision Tree?
A Supervised Machine Learning Algorithm, used to build classification and regression models in the form of a tree structure.

A decision tree is a tree where each -

Node - a feature(attribute)
Branch - a decision(rule)
Leaf - an outcome(categorical or continuous)
There are many algorithms to build decision trees, here we are going to discuss the ID3 algorithm with an example.

What is an ID3 Algorithm?
ID3 stands for Iterative Dichotomiser 3

It is a classification algorithm that follows a greedy approach by selecting the best attribute that yields maximum Information Gain(IG) or minimum Entropy(H).

What are Entropy and Information gain?
Entropy is a measure of the amount of uncertainty in the dataset S. Mathematical Representation of Entropy is shown here -

H ( S ) = ∑ c ∈ C − p ( c ) l o g 2 p ( c )
Where,

S - The current dataset for which entropy is being calculated(changes every iteration of the ID3 algorithm).
C - Set of classes in S {example - C ={yes, no}}
p(c) - The proportion of the number of elements in class c to the number of elements in set S.
In ID3, entropy is calculated for each remaining attribute. The attribute with the smallest entropy is used to split the set S on that particular iteration.
Entropy = 0 implies it is of pure class, which means all are of the same category.

Information Gain IG(A) tells us how much uncertainty in S was reduced after splitting set S on attribute A. Mathematical representation of Information gain is shown here -

I G ( A , S ) = H ( S ) − ∑ t ∈ T p ( t ) H ( t )
Where,

H(S) - Entropy of set S.
T - The subsets created from splitting set S by attributing A such that
S = ⋃ t ϵ T t
p(t) - The proportion of the number of elements int to the number of elements in set S.
H(t) - Entropy of subset t.
In ID3, information gain can be calculated (instead of entropy) for each remaining attribute. The attribute with the largest information gain is used to split the set S on that particular iteration.

What are the steps in the ID3 algorithm?

Calculate entropy for the dataset.
For each attribute/feature.
Calculate entropy for all its categorical values.
Calculate information gain for the feature.
Find the feature with maximum information gain.
Repeat it until we get the desired tree.


<!-- ------------------------------------------------------------- -->

## [Difference Between Supervised and Unsupervised Learning](https://medium.com/@hamid42/difference-between-supervised-and-unsupervised-learning-f51643aeb647):
   ### Supervised Learning:
   <img width="887" alt="Supervised Learning" src="https://user-images.githubusercontent.com/68488154/131554881-51ee1661-4625-4983-9798-fd4be5f919a9.png">

   In Supervised learning, you train the machine using data that is well “labeled.” It means some data is already tagged with the correct answer. It can be compared to learning which takes place in the presence of a supervisor or a teacher.
     
   A supervised learning algorithm learns from labeled training data, helps you to predict outcomes for unforeseen data. Successfully building, scaling, and deploying accurate supervised machine learning Data science models takes time and technical expertise from a team of highly skilled data scientists. Moreover, Data scientist must rebuild models to make sure the insights given remains true until its data changes.
    
   ### Unsupervised Learning:
   <img width="739" alt="Unsupervised Learning" src="https://user-images.githubusercontent.com/68488154/131554911-987a80a2-76d8-4ae0-a58d-c27f296ec918.png">

   Unsupervised learning is a machine learning technique, where you do not need to supervise the model. Instead, you need to allow the model to work on its own to discover information. It mainly deals with the unlabelled data. Unsupervised learning algorithms allow you to perform more complex processing tasks compared to supervised learning. Although, unsupervised learning can be more unpredictable compared with other natural learning deep learning and reinforcement learning methods.
   
   ### Supervised and Unsupervised Learning Algorithm:
   <img width="771" alt="Supervised and Unsupervised Learning Algorithm" src="https://user-images.githubusercontent.com/68488154/131554785-d0055847-4788-4357-8745-0a89152f08b2.png">

## Performance Metrics:
  <img width="417" alt="Performance Metrics" src="https://user-images.githubusercontent.com/68488154/132079458-2ec5d7b4-d131-4e08-9190-d25d70dfa625.png">

## R-Squared Value:
   R-squared is a goodness-of-fit measure for linear regression models. This statistic indicates the percentage of the variance in the dependent variable that the independent variables explain collectively. R-squared measures the strength of the relationship between your model and the dependent variable on a convenient 0 – 100% scale. Image of a large R-squared. After fitting a linear regression model, you need to determine how well the model fits the data. Does it do a good job of explaining changes in the dependent variable? There are several key goodness-of-fit statistics for regression analysis.
   
  <img width="632" alt="R-Squared Value" src="https://user-images.githubusercontent.com/68488154/132080071-c47681a6-eae1-4793-9d00-aeabe6e5330f.png">
  
## Feature Engineering in ML:
   
   ### Encoding Technique Types:
   #### 1. Without Use any encoding:
   #### 2. lavel encoding:
  <img width="616" alt="8-Level Encoding" src="https://user-images.githubusercontent.com/68488154/133471493-8d0024d3-915e-49c0-acb4-812cc589d516.png">
  <img width="639" alt="9-Level Encoding1" src="https://user-images.githubusercontent.com/68488154/133471538-2a2b5e58-a7fc-4b6a-adbd-96e308ac5a3c.png">
  
   #### 3. One Hot Encoding:
   <img width="601" alt="10-One-Hot Encoding" src="https://user-images.githubusercontent.com/68488154/133471900-e76017bb-b963-4fa0-acca-17e1c0783f3c.png">
   
   #### 4. Ordinal Encoding:
   <img width="628" alt="11-Ordinal Encoding" src="https://user-images.githubusercontent.com/68488154/133471958-73a26580-f85c-4627-a89c-3a6c2146d312.png">
   
   #### 5. Hash Encoding:
   <img width="648" alt="12-Hashing Encoding" src="https://user-images.githubusercontent.com/68488154/133471981-03a210ee-3f76-45cd-b5f0-b4cbd26bf2e5.png">

## ID3 Algorithm in Decision Tree :
   ID3 algorithm stands for Iterative Dichotomiser 3, which is a classification algorithm that follows a greedy approach of building a decision tree by selecting the best attribute that yields maximum Information Gain (IG) or minimum Entropy (H).

We will go through the basics of the decision tree, ID3 algorithm before applying it to our data. We will answer the following questions:

1. What is a decision tree?
2. What is the ID3 algorithm?
3. What is information gain and entropy?
4. What are the steps in the ID3 algorithm?
5. Using ID3 algorithm on a real data
6. What are the characteristics of the ID3 algorithm?

What is a Decision Tree?
A Supervised Machine Learning Algorithm, used to build classification and regression models in the form of a tree structure.

A decision tree is a tree where each -

Node - a feature(attribute)
Branch - a decision(rule)
Leaf - an outcome(categorical or continuous)
There are many algorithms to build decision trees, here we are going to discuss the ID3 algorithm with an example.

What is an ID3 Algorithm?
ID3 stands for Iterative Dichotomiser 3

It is a classification algorithm that follows a greedy approach by selecting the best attribute that yields maximum Information Gain(IG) or minimum Entropy(H).

What are Entropy and Information gain?
Entropy is a measure of the amount of uncertainty in the dataset S. Mathematical Representation of Entropy is shown here -

H ( S ) = ∑ c ∈ C − p ( c ) l o g 2 p ( c )
Where,

S - The current dataset for which entropy is being calculated(changes every iteration of the ID3 algorithm).
C - Set of classes in S {example - C ={yes, no}}
p(c) - The proportion of the number of elements in class c to the number of elements in set S.
In ID3, entropy is calculated for each remaining attribute. The attribute with the smallest entropy is used to split the set S on that particular iteration.
Entropy = 0 implies it is of pure class, which means all are of the same category.

Information Gain IG(A) tells us how much uncertainty in S was reduced after splitting set S on attribute A. Mathematical representation of Information gain is shown here -

I G ( A , S ) = H ( S ) − ∑ t ∈ T p ( t ) H ( t )
Where,

H(S) - Entropy of set S.
T - The subsets created from splitting set S by attributing A such that
S = ⋃ t ϵ T t
p(t) - The proportion of the number of elements int to the number of elements in set S.
H(t) - Entropy of subset t.
In ID3, information gain can be calculated (instead of entropy) for each remaining attribute. The attribute with the largest information gain is used to split the set S on that particular iteration.

What are the steps in the ID3 algorithm?

Calculate entropy for the dataset.
For each attribute/feature.
Calculate entropy for all its categorical values.
Calculate information gain for the feature.
Find the feature with maximum information gain.
Repeat it until we get the desired tree.

## [All About Confusion Matrix.pdf](https://github.com/hamidhosen42/Basic-Machine-Learning-with-Python/files/7272695/All.About.Confusion.Matrix.pdf)

## Types of Regression
   1. Linear Regression
   2. Polynomial Regression
   3. Logistic Regression
   4. Quantile Regression
   5. Ridge Regression
   6. Lasso Regression
   7. Elastic Net Regression
   8. Principal Components Regression (PCR)
   9. Partial Least Squares (PLS) Regression
   10. Support Vector Regression
   11. Ordinal Regression
   12. Poisson Regression
   13. Negative Binomial Regression
   14. Quasi Poisson Regression
   15. Cox Regression
   16. Tobit Regression

## Ensemble Learning

Ensemble methods is a machine learning technique that combines several base models in order to produce one optimal predictive model . To better understand this definition lets take a step back into ultimate goal of machine learning and model building.

## [Random Forest Classifier & Regressor](https://www.youtube.com/watch?v=4EOCQJgqAOY)
![image](https://user-images.githubusercontent.com/68488154/136642823-85231cce-6661-442d-a1a5-dd6165a73748.png)

link:[Random Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)

The random forest is a classification algorithm consisting of many decisions trees. It uses bagging and feature randomness when building each individual tree to try to create an uncorrelated forest of trees whose prediction by committee is more accurate than that of any individual tree.

Random forests or random decision forests are an ensemble learning method for classification, regression and other tasks that operates by constructing a multitude of decision trees at training time. ... For regression tasks, the mean or average prediction of the individual trees is returned.

Random Forest Regression is a supervised learning algorithm that uses ensemble learning method for regression. ... A Random Forest operates by constructing several decision trees during training time and outputting the mean of the classes as the prediction of all the trees


## Feature Selection Techniques in Machine Learning with Python
Feature Selection is one of the core concepts in machine learning which hugely impacts the performance of your model. The data features that you use to train your machine learning models have a huge influence on the performance you can achieve. How to select features and what are the Benefits of performing feature selection before modeling your data?
   1. Reduces Overfitting: Less redundant data means less opportunity to make decisions based on noise.
   2. Improves Accuracy: Less misleading data means modeling accuracy improves.
   3· Reduces Training Time: fewer data points reduce algorithm complexity and algorithms train faster.

## Feature Selection Methods:
   1. Univariate Selection
   2. Feature Importance ( https://youtu.be/VXv0-Hv9cT4 )
   3. Correlation Matrix with Heatmap
## Feature Selection Related Important Links:
   1. https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.chi2.html#sklearn.feature_selection.chi2
   2. https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.f_classif.html#sklearn.feature_selection.f_classif
   3. https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.mutual_info_classif.html#sklearn.feature_selection.mutual_info_classif
   4. https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.f_regression.html#sklearn.feature_selection.f_regression
## k-nearest neighbors (KNN)
The k-nearest neighbors (KNN) algorithm is a simple, supervised machine learning algorithm that can be used to solve both classification and regression problems. It's easy to implement and understand, but has a major drawback of becoming significantly slows as the size of that data in use grows.
   1. https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html
   2. https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html
   3. <img width="470" alt="2-" src="https://user-images.githubusercontent.com/68488154/140653966-7b3dc395-e67d-47e8-ac44-f2b899a49fac.png">
   4. <img width="569" alt="3-" src="https://user-images.githubusercontent.com/68488154/140654023-8ba459a1-493b-43ab-b236-0aa3e6d24cfc.png">

## [TF-IDF Vectorizer | Feature Extraction Techniques | NLP](https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html)
TF-IDF stands for Term Frequency(TF)-Inverse Document Frequency(IDF). It highlights a specific issue that might not be too frequent in our corpus but holds great importance. The TF–IFD value increases proportionally to the number of times a word appears in the document and decreases with the number of documents in the corpus that contain the word. It is composed of 2 sub-parts, which are: Term Frequency (TF) and Inverse Document Frequency (IDF)


## [Naive Bayes Algorithm](https://scikit-learn.org/stable/modules/naive_bayes.html)
Applications of Naive Bayes Algorithms: 
1. Real-time Prediction
2. Recommendation System
3. Text classification/ Spam Filtering/ Sentiment Analysis:
4. Multi-class Prediction:

Scikit learns (Python Machine Learning library) will help here to build a Naive Bayes model in Python. There are three types of Naive Bayes model under the sci-kit learn library:

#### Gaussian: 
  It is used in classification and it assumes that features follow a normal distribution.

#### Multinomial:
It is used for discrete counts. For example, let’s say,  we have a text classification problem. Here we can consider Bernoulli trials which is one step further and instead of “word occurring in the document”, we have “count how often word occurs in the document”, you can think of it as “number of times outcome number x_i is observed over the n trials”.

#### Bernoulli: 
The binomial model is useful if your feature vectors are binary (i.e. zeros and ones). One application would be text classification with a ‘bag of words’ model where the 1s & 0s are “word occurs in the document” and “word does not occur in the document” respectively.

## Apriori Algorithm in Data Mining:
<img width="524" alt="1" src="https://user-images.githubusercontent.com/68488154/145719561-4856a936-1db5-4bf3-a3c4-e05c12798b46.png">


## Feature Scaling Techniques in Machine & Deep Learning:
1. What is Feature Scaling? 

Feature scaling is a method used to normalize the range of independent variables or features of data. In data processing, it is also known as data normalization and is generally performed during the data preprocessing step.

2. Which machine learning algorithms require feature scaling?

The Machine Learning algorithms that require the feature scaling are mostly KNN (K-Nearest Neighbours), Neural Networks, Linear Regression, and Logistic Regression.

3. Feature Scaling is a technique to standardize the independent features present in the data in a fixed range. It is performed during the data pre-processing to handle highly varying magnitudes or values or units. If feature scaling is not done, then a machine learning algorithm tends to weigh greater values, higher and consider smaller values as the lower values, regardless of the unit of the values.

Example: If an algorithm is not using a feature scaling method then it can consider the value 100 meters to be greater than 5 km but that’s actually not true and in this case, the algorithm will give wrong predictions. So, we use Feature Scaling to bring all values to the same magnitudes and thus, tackle this issue.

4. Min-Max Normalization: This technique re-scales a feature or observation value with a distribution value between 0 and 1.

5. Standardization: It is a very effective technique which re-scales a feature value so that it has distribution with 0 mean value and variance equals to 1.
<img width="500" alt="Screenshot 2021-12-12 222125" src="https://user-images.githubusercontent.com/68488154/145720520-89b0ce93-7de1-4b4d-8b3d-cc90ca60daaa.png">


### Classification report:
<img width="341" alt="Screenshot 2021-12-13 112013" src="https://user-images.githubusercontent.com/68488154/145756956-071ebb77-2de9-4b57-bf8e-80a9a19659a9.png">
