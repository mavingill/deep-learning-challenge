For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

The purpose of this analysis was to use machine learning algorithims and neural networks to unconver whether individuals would be successful when selected by Alphabet Soup. 

Results: Using bulleted lists and images to support your answers, address the following questions:


Data Preprocessing

Target Variable:
The target variable in our model is 'IS_SUCCESSFUL,' which is a column from the application_df DataFrame.

Feature Variables:
For our model, the feature variables encompass all other columns present in the application_df DataFrame. These features are derived by excluding the 'IS_SUCCESSFUL' column from the original dataset.

Excluded Variables:
To streamline our analysis, we have excluded the 'EIN' and 'NAME' columns from the input data. These columns were removed as they neither serve as target variables nor contribute as features to our dataset.



Compiling, Training, and Evaluating the Model

Neurons, Layers, and Activation Functions:
In the initial attempt, the model was configured with 5 neurons in both the first and second hidden layers, although these choices were made somewhat arbitrarily. The second attempt involved experimenting with different configurations to optimize performance.

Achieving Target Model Performance:
Unfortunately, the target model performance of 75% accuracy was not reached in either attempt.

Efforts to Improve Model Performance:
To enhance the model's performance, several steps were undertaken, including the addition of more hidden layers, the removal of certain columns, increasing the number of hidden nodes, and altering the activation functions applied to each layer. These adjustments aimed to improve the model's accuracy.


First Attempt:
My first attempt resulted in an accuracy of 73%. I used the following information:

hidden_nodes_layer1 = 5
hidden_nodes_layer2 = 5
epoch: 100

The result was the following graph:
![Alt text](image-4.png)

Second Attempt:
My second attempt resulted in an accuracy of 72.6%. I used the following information to get this result:

hidden_nodes_layer1 = 12
hidden_nodes_layer2 = 10
epoch: 100

The result was the following graph:
![Alt text](image-5.png)


Third Attempt:
My final attempt resulted in an accuracy of 72.7%. I used the following information to get this result:

hidden_nodes_layer1 = 20
hidden_nodes_layer2 = 30
epoch: 100

The result was the following graph:
![Alt text](image-6.png)


Summary:
In summary, the deep learning model achieved an accuracy of approximately 73% when addressing the classification problem. To potentially achieve higher predictive accuracy, a different approach is recommended. One possible solution involves enhancing the correlation between input and output by conducting more thorough data preprocessing and using a model with varied activation functions. Continuous iteration and experimentation are advised to attain the desired higher accuracy.

[def]: image.png