# Machine Learning Bird's Eye View

## History of Statistician's Perspective
* Evolved from understanding data. 
* Field of data analysis -> field of mathematics where we try to understand the mechanisms that create data. 
* Probability based models were used to model the world around us.
### Kind of data distributions
* Binomain
* Poisson
* Zipf

These mathematical functions were very helpful to describe the all the aspects of life. But it seemed the very mere oversimplification of the real-life data. 

## History of Computer Scientist's Perspective
* CS felt the need of machines that could observe the data and recognizing the pattern. 
* Instead of following the hard-coded rules, the new techniques are now based on distributions.
* So, now we create models that can provide accurate and very close predictions to the real world data. 
* Drawback: They can't explain why they are making such predictions.

## Types of Machine Learning -

### 1. Supervised Learning
* Studying labeled data, these techniques can extend patterns to unlabeled data. 
* Highest business application in the industry. 
* DL can be used within supervised ML to create techniques that are better at image recognition or identifying when a movie was created based on the video footage.
##### Classification
* Predicts the category to which an item belongs.
* Can be Binary as well as multi-class. 
##### Regression
* Provides numeric outcomes.

### 2. Unsupervised Learning
* Creates model for data that have no pre-existing labels to train on.
* Second most used in business applications. 
* By learning patterns even when data do not have labels, these techniques can group items together that are likely to be similar.
* Applications:
    1. Reducing dataset to a fewer number of useful features.
    2. Grouping similar items
    3. Building Music recommendation systems. 


### 3. Reinforcement Learning
* RL is used to train algorithms that learn based on taking certain actions & receiving rewards for those actions. 
* Applications:
    1. Self-driving cars. 
    2. Game-playing agents. 

## Deep Learning
* Has beaten all other ML algorithms in its ability to predict. 
* Can be used for Supervised, Unsupervised and, RL.
* Till now we have focused on precise prediction, and not on 'how' or 'why' of the predictions. 
 ### Barriers:
* Huge data. 
* Huge computational power. 
* No reasoning of decisions being made.

## ML Libraries
* Tensorflow & Scikit-learn
    1. open-source
    2. advance techniques in un/supervised ML.

## Ethics in ML
* Since our data in real-world holds errors and biases, the models built on them contain the same defects as well. 
* Human biases should always be considered while building the models. 
* Real-world validation of the model is more important than statistical validation. 

## Fitting a line through data. 
* Equation of line: *y = w<sub>1</sub>x + w<sub>2</sub>*
* slope: *w<sub>1</sub>*
* y-intercepts: *w<sub>2</sub>*
* Absolute Trick:  Never take large steps. So we use concept of learning rate. (LR)
* *y = (w<sub>1</sub> + pα)x + (w<sub>2</sub>* + α) ; α is LR
* α helps us to tread carefully towards the data points. 
* when the point is in 2nd quadrant: *p* is -ve. This causes a rotation of line. 
