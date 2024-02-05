# Module21_deep-learnin-challenge
<h2>Module21 Challenge Report</h2>

<h3>Overview</h3>
Purpose of this analysis is to create a model to help predict an applicants rate of success based on the features in the dataset.
Using TensorFlow,  preprocess, compile, train, and evaluate the binary classification model to calculate the model’s loss and accuracy.

Test the model and optimise it to improve the model output

<h3>Compile, Train and Evaluate the Model</h3>

Total of 4 layers

Nodes: 
  - 10 
  - 18
  - 8
  - 1

Activation functions: 
 - reLU
 - 2 x tanh
 - sigmoid

![image](https://github.com/michaelz-id/Module21_deep-learnin-challenge/assets/72367969/71f5efde-5b23-4f51-9faa-e97c4f9bbdd2)


<h3>Model Results</h3>

After running the model through 30 epochs:

![image](https://github.com/michaelz-id/Module21_deep-learnin-challenge/assets/72367969/b65d2b32-7a62-4e53-a3e1-4d2f1ff6b2fc)

The results show an accuracy score of approx 73% with a loss of 56%

![image](https://github.com/michaelz-id/Module21_deep-learnin-challenge/assets/72367969/ff90a7a6-50f3-49da-8162-3ee3f9a919f7)

<h3>Recommendations</h3>
Model and accuracy could be improved with deeper investigation in model design and layers
- Due to limitations on hardware I could not experiment further
- Including Principle Component Analysis (PCA) could simplify the data that might result in more accuracy
- Experiment with other ML techniques such as: Random Forest or XGBoost decision tree
