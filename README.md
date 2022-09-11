# ML-engineer-journey
This repository cantains a list of projects which i will work on while learning #course-ml-zoomcamp





# Introduction_to_Machine_Learning_1.1:
Suppose you want to sell your car on "olx." You filled up all the things that are required, and now you have to put in the price of
Your car and you don't know what price you should put on it. This step is tricky because nobody will buy it if you set a higher price.
If you put a too low price on your car, this will be your loss. One thing you can do is to go to the market and check the prices of cars.
That isn't easy. So, what can we do to solve this problem?
We can solve the problem with machine learning, but how? when you go to some car dealers' experts and show them your car? Then he asks some questions about the car, like a year of manufacture, make (BMW, FORD), mileage, and then he predicts the price of your car because he knows the pattern (selling or buying) if an expert can predict it, so the model can also predict the price by evaluating the patterns. So, we train our model on patterns like this kind of car being sold at this price and many other patterns we use to train our model. The input we provide to the model is called "features" (what we know about the cars), and what we want to predict is called "Target." So, when the model is trained, we give the random features or patterns to the model, and then the model predicts the price One thing you should know is that the model will not predict a 100% accurate price. It can be a little bit higher or a little bit lower than average. So now we have a model that predicts the price from the features. Now it's time to help our website users. Whenever they input the features, our model will predict the best price for the car.


# ML_vs_Rule_Based_Systems_1.2
Today I learned about ML vs. Rule-Based Systems so I will explain it to you guys.
Let's first talk about the rule base system: we all use email services like Gmail and Yahoo. We are all familiar with spam mail. So here is a situation where we don't want to see these spam mails in our email boxes because these are social engineering techniques that manipulate users to click on their specific links so they can steal their information. So now we know what spam emails are, and we don't want them. So how does the rule-based system deal with this problem? We often see a fake domain and a fake title in spam mail, so we will automatically make some rules to send these emails to the spam folder. If the sender mail = ------@online.com or the title contains "tax review," and if the body contains the word "deposit," make it spam. Otherwise, good email.
What If the rules change again and again? So, we have to code again and again, which is frustrating.
So, the question is how ML will help us solve this problem!
So, to deal with this problem using ML, we first have to get the data from our users. We all use emails, and when you open a specific email, there are options on the top bar, like ''Add to spam'' or "mark as spam." When the user marks these emails as spam, we will get all the spam mail data and organize it. When we have a sufficient amount (2k to 30k rows) of data, remember the rules from the rule base system? We will use those rules as our features for the model we train. When the model is fully trained, we will give the random features data so we can check the model prediction whether the model is working great or not. As we know, the model predictions are not 100% accurate, so when the model predicts on the provided features, whether this email is spam or how many percent of that email is spam? Let's say our model predicts some % on the provided data (0.8%, 0.6%, 0.3%), and for the final decision, we add a condition. If a prediction of feature data is >= to 0.5%, then based on that %, the model will put the specific email into the spam folder.



# Supervised_Machine_Learning_1.3

Today we will learn about supervised ML. The word “supervised” means there is a teacher who is supervising or teaching the model. As you know, we trained our model on car data. We provided all the car information to the model to predict the price and the spam mail data so that the model could predict which was spam and which was good.
So now we will discuss supervised ML types.
1: Regression
2: Classification
 
Let’s first talk about regression:
Remember the model we developed that predicted car prices based on the features we gave? We can also create a model that can predict the price of a house. We can say that a model which gives an output/prediction in a number can be called a regression model. The numbers could be from -0 to infinity.
 
The other type we have classification.
In classification, we do not predict a number value; we predict the category.
When a model sees a car, cat, or dog, it will put it in its category.
As we studied spam mail issues, it was also a classification problem. We were doing classification there. Spam or good mail?



# Model_selection_1.4

Today I am writing about the model selection process, which I recently learned, and I want to share it with you guys. The model selection process is vital in machine learning.
So, what do we do in the model selection process?
Suppose we have a dataset of cars, and we want an accurate model for price prediction.
So, we split our car dataset into 80/20 rules. 80% for training purposes and 20% for testing purposes.
This 20% is hidden from the model.
So now you train your model with different types of ML algorithms.
With logistic regression, it gives you 40% accuracy; with random forest, it gives you 60% accuracy.
And with a neural network it gives you 80%, so you choose the best accuracy model accordingly.
Another thing to remember is that if you choose a neural network as your prediction model, you must test it again using the 60/20/20 rule. 60% will be your training data, 20% will be for validation, and the other 20% for testing.
After this, if you get 78% to 79%, we are good to go with this NN model. The accuracy doesn't need to be 78 % or 79%; it could be lower or higher



Introduction_to_NumPy_1.4
check out my repo where I uploaded the Numpy Introduction practice file



# Introduction_to_Pandas_1.5
check out my repo where I uploaded the Pandas Introduction practice file








