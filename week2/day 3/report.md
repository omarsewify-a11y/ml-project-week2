# Machine Learning Report – Week 2 Day 3

## Student Information
Name: Omar Sewify  
University: American University of Ras Al Khaimah  
Major: Artificial Intelligence  

---

## Dataset
In this project, I used the Iris dataset. This dataset is a common dataset in machine learning used for classification tasks. It contains measurements of flowers and is used to predict the type of flower based on those measurements.

The dataset includes 150 samples of flowers with four main features:
- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

Each sample belongs to one of three classes:
- Setosa  
- Versicolor  
- Virginica  

---

## Features and Label
The input data (features) are the four flower measurements listed above.  
The output (label) is the flower type (Setosa, Versicolor, or Virginica).

So, the model learns to connect the features with the correct label.

---

## Machine Learning Workflow
In this project, I followed the basic machine learning process:

1. Load the dataset  
2. Understand the data  
3. Split the data into training and testing sets  
4. Train the model using training data  
5. Make predictions using test data  
6. Evaluate the model using accuracy  

---

## Model Used
I used a Decision Tree Classifier.

I chose this model because:
- It is simple to understand  
- It works well with small datasets  
- It makes decisions step by step using rules  
- It is good for classification problems  

---

## Training and Testing
The dataset was split into:
- 80% training data  
- 20% testing data  

The model learned from the training data and then tested its performance using the testing data.

---

## Results
The model predicted flower types based on the input features.

Accuracy achieved: **(write your accuracy here, for example 0.96 or 96%)**

This accuracy means the model correctly predicted most of the test samples.

---

## Understanding the Model
The model learns by finding patterns in the training data. It looks at how the features (like petal length and width) are related to each flower type. Then it creates rules to make predictions on new data.

For example, if a flower has certain measurements, the model uses learned rules to decide which class it belongs to.

---

## Comparison with Previous Project (Chatbot)
In the previous chatbot project (rule-based system), I manually wrote rules for the system to follow.

In this machine learning project, I did not write rules manually. Instead, the model learned patterns automatically from the data.

This is the main difference between rule-based systems and machine learning systems.

---

## Reflection
Before this task, I thought machine learning models needed complex coding and manual rules. After doing this project, I understood that machine learning is mainly about data and learning from examples.

One thing that surprised me is that the model can learn patterns by itself without being explicitly programmed with rules.

One thing I found a bit confusing at first was how the training and testing data work, but after practicing, it became clearer.

Overall, this project helped me understand the basic workflow of machine learning and how models make predictions.

---

## Conclusion
This project successfully demonstrated the full machine learning workflow from data loading to evaluation. It helped me understand how AI systems can learn from data instead of using manually written rules.
