#Intent Prediction in Code 
##With Applied Machine Learning Techniques

Software and code are becoming present nearly everywhere in our daily lives both personal and professional. Whether it helps us accomplish complex and massive tasks, or powers the applications and products we rely on, the digital world is expanding. Yet, only a fraction of us are literate in code, and even among those of us who are, there are a wide range of languages and frameworks so no one is familiar with it all, and mistakes or misinterpretations can be made even on languages we're familiar with. 

I propose a model which could predict the intent or purpose of a sample of code. A tool like this would helpful in understanding more of the world around us and would be hugely impactful for:  
- Education. Making code more accessible and interpretable.  
- Security. Identifying code with malicious intent.  
- Development. Providing contextual tooltips, suggestions, resources.   

The goal of this project is to develop an ML model which employs NLP tools to interpret a samples of code and make a prediction as to its intent.

Below is a copy of the table of contents of the notebook for a sample of the work done.
***

##Table of Contents
1.0 - Introduction
1.1 - Problem
2.0 - Background
2.1 - Stack Overflow
2.2 - Packages and Libraries
3.0 - Limitations and Assumptions
4.0 - The Data
4.1 - Sources of Data
4.1.1 - CoNaLa
4.1.2 - Other Sources of Data
5.0 - Exploratory Data Analysis
5.1 - Importing Data
5.1.1 - Importing CoNaLa Competition Data
5.1.1.1 - Importing CoNala Training Data
5.1.1.2 - Importing CoNaLa Test Data
5.2 - DataFrames from CoNaLa Competition Data
5.3 - Input and Target
5.4 - Pickling Data
5.5 - CoNaLa Mined Data
6.0 - Modelling Approaches
7.0 - Preprocessing
7.1 - Separating Input and Target
7.2 - Preparing for Tokenization
7.2.3 - Helper Functions
7.2.3.1 - List Splitting Helper Function
7.3 - Vectorizing Text Data
8.0 - Modelling and Analysis
8.1 - Seq2Seq Discussion
8.2 - Implementing Seq2Seq
8.3 - Training the Seq2Seq Model
8.4 - Predicting a Target Sequence
8.5 - Prediction for Custom Data
9.0 - Discussion
9.1 - Model Metric Performance
9.2 - Model Qualitative Performance
9.2.1 - Model Weaknesses
9.2.2 - Model Strengths
10.0 - Conclusions and Next Steps
11.0 - References
