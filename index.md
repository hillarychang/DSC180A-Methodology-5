# DSC 180A - Methodology Assignment 5

**Name**: Hillary Chang
**Email**: hic001@ucsd.edu

**Section**: B02
**Mentor**: Brian Duke, Kyle Nero

## Brainstorming for Quarter 2 Project Proposal

**1. What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic covered in my domain this quarter was experimenting with different models to classify transaction categories. We tested various models, including Naive Bayes, Logistic Regression, Random Forest, FastText, and Transformer-based models, and observed how each performed differently. It was very interesting to see how simpler models like Naive Bayes and Logistic Regression provided solid results, while more complex models, like FastText, offered higher accuracy but had a higher latency. Therefore, it was very interesting to see how each model had its own strengths and weaknesses in terms of the run time and accuracy. I also found it very interesting to explore feature engineering techniques, such as tokenizing the memo field by adding specific tokens for whole dollar amounts, transaction dates, and other indicators. These tokens seemed to help the models categorize transactions more effectively, which shows how important feature engineering is in improving model performance.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
A potential investigation I would like to pursue for my Quarter 2 Project would be a predictive model to see which users would pay their bills/maintain good credit. We would build off of our work categorizing transactions and estimating income to create a more comprehensive financial profile for each customer. With a larger feature set that captures each person's spending habits, income, and transaction categories, we could improve the model’s understanding of each customer’s financial behavior. Our goal would be to predict which customers are likely to pay their bills, based on these features. We could start with a more basic predictive model, like Logistic Regression, due to its speed, then keep trying more complex models that could have better accuracy.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
Although we haven't began predicting user income, I think one potential change to my approach in my current Quarter 1 Project is to improve ways to handle external transfer transactions. Since these transactions can represent both income (ex. payments from Venmo) and non-income (ex. payments between friends), it would be useful to use clustering or advanced natural language processing techniques on the memo field to better distinguish between types. By clustering transactions with similar memo descriptions or analyzing their regularity, we could identify patterns that indicate income more accurately. This could help improve the accuracy of our income classification, particularly for transactions that aren’t labeled as income or non-income.

**4. What other techniques would you be interested in using in your project?**  
I am interested in exploring more advanced NLP techniques, such as BERT to improve classification accuracy. BERT’s approach could allow for a greater understanding of transaction descriptions. Another technique I would like to explore is transfer learning, where we could use a pre-trained language model on a related dataset and fine-tune it to our specific task. This might improve performance on categories with limited examples. Dimensionality reduction techniques like PCA or clustering-based feature extraction could also be interesting and beneficial in enhancing the effectiveness of our model.
