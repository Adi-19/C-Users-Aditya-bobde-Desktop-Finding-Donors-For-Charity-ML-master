# Supervised Learning
# Project: Finding Donors for CharityML

# Description
CharityML is a fictitious charity organization located in the heart of Silicon Valley that was established to provide financial support for people eager to learn machine learning. After nearly 32,000 letters were sent to people in the community, CharityML determined that every donation they received came from someone that was making more than $50,000 annually. To expand their potential donor base, CharityML has decided to send letters to residents of California, but to only those most likely to donate to the charity. With nearly 15 million working Californians, CharityML has brought you on board to help build an algorithm to best identify potential donors and reduce overhead cost of sending mail. Your goal will be evaluate and optimize several different supervised learners to determine which algorithm will provide the highest donation yield while also reducing the total number of letters being sent.

Preprocessed data by transforming skewed functions, normalizing/scaling, and one-hot encoding
Evaluated models based on metrics such as Accuracy, Precision, Recall, F Beta Score, as well as compare them against a Naive Predictor
Explored real-world application of models, advantages, and disadvantages
Evaluated Supervised Learning techniques including Gaussian Naive Bayes, Decision Trees, Support Vector Machines (SVM) and chooses the best model
Created training and predicting pipeline to quickly and efficiently train models using various sizes of training sets and perform predictions on testing data
Tuned model using Grid Search to optimize hyperparameters
Extracted feature importance
Performed feature selection to get the most important features and re-trained the model
Examined effects of feature selection by comparing the model with reduced features and optimized model
# Install
This project requires Python 3.x and the following Python libraries installed:

NumPy
Pandas
matplotlib
scikit-learn
You will also need to have software installed to run and execute an iPython Notebook

We recommend students install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

# Code
Template code is provided in the finding_donors.ipynb notebook file. You will also be required to use the included visuals.py Python file and the census.csv dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in visuals.py is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

# Run
In a terminal or command window, navigate to the top-level project directory finding_donors/ (that contains this README) and run one of the following commands:

ipython notebook finding_donors.ipynb
or

jupyter notebook finding_donors.ipynb
This will open the iPython Notebook software and project file in your browser.

# Data
The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper "Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid", by Ron Kohavi. You may find this paper online, with the original dataset hosted on UCI.

# Features

1. age: Age
2. workclass: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
3. education_level: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-      6th, Preschool)
4. education-num: Number of educational years completed
5. marital-status: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
6. occupation: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-      fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
7. relationship: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
   race: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
8. sex: Sex (Female, Male)
9. capital-gain: Monetary Capital Gains
10. capital-loss: Monetary Capital Losses
11. hours-per-week: Average Hours Per Week Worked
12. native-country: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran,       Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala,       Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)
# Target Variable

income: Income Class (<=50K, >50K)
