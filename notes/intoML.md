# Descending into ML with Linear Regression 
y' = b + wx    
Where `w` is the weight vector and `b` is the bias  

Training a model simply means learning (determining) good values for all the weights and the bias from labeled examples.
In supervised learning, a machine learning algorithm builds a model by examining many examples and attempting to find a model that minimizes loss; this process is called empirical risk **minimization**.

<img src="/c/Users/nmark/Documents/GitHub/google-ML-crashcourse/loss.png">

## Loss
*loss* is essentially just the model's error  
L2 loss, or squared error, is the square of the differnce between prediction and label.  
(observation - prediction)^2  
(y - y')^2



