# Terminology 
- Label: variable we are predicting (y)
- Features: input variable describing the data (x)  

- Example is a particular instance of data
	- Labeled example has {features,label}: (x,y)
		- Used to train a model
	- Unlabled exmaple has {features,?}: (x,?)
		- Used for making predictions on new data
	- Model maps exmaples to predicted labels
		- Defined by internal parameters, which are learned
- Model
	- Defines relationship between features and labels
		- **Training** is learning/creating the model. Show the model labeled exmaples and the model will gradually learn the relationships between labels and features.
		- **Inference** is when you apply a trained model to unlabeled examples to make new predictions.

- Regression vs. Classification
	 - **Regression** model predictions continous values
	 - **Classification**  model predicts disrete values






