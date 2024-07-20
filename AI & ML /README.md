**Project Objective**

Our group project objective is to predict the price of a phone based on its features.

**Methodology**

We used a dataset containing various features of existing phones to train a regression analysis based machine learning model in order to predict the price of a new phone.

**Dataset**

The dataset we will be using to build our ML model is from Kaggle: https://www.kaggle.com/datasets/rkiattisak/mobile-phone-price?resource=download

The (uncleaned) dataset variables include:

    Brand: the manufacturer of the phone
    Model: the name of the phone model
    Storage (GB): the amount of storage space (in gigabytes) available on the phone
    RAM (GB): the amount of RAM (in gigabytes) available on the phone
    Screen Size (inches): the size of the phone's display screen in inches
    Camera (MP): the megapixel count of the phone's rear camera(s)
    Battery Capacity (mAh): the capacity of the phone's battery in milliampere hours
    Price ($): the retail price of the phone in US dollars

**Model Selection**

Based on our analysis, we narrowed our model selection to 2 models: a Decision Tree Model and a Neural Network Model. To determine the best model for predicting phone prices, we will initially use both the decision tree and neural network models. The decision tree will provide insights into which variables matter the most, while the neural network will leverage the dataset's complexity to potentially achieve higher accuracy. By comparing their performance and considering the specific requirements of interpretability versus predictive power, we will select the model that best meets our goals for accurate and insightful price predictions.

**Conclusion**

In summary, our project successfully predicted phone prices using a Decision Tree Model, which outperformed the Neural Network model. We improved its accuracy through hyperparameter tuning with grid search. Future work could focus on refining feature details, adding new factors, and addressing dataset limitations. Exploring larger datasets and neural networks could further enhance our findings. Overall, the project highlights the effectiveness of decision tree models and hyperparameter tuning in predictive analytics, and it was interesting to see how this can be used on real world data.

**_Please see our python notebook for code, visual displays, and greater detail explanations of the sections above._**

**!!NOTE: LINKING CSV FROM GITHUB!!**
- The url needs to be updated before running the notebook as the token expires after some time.
- Go to Mobile phone price.csv and click 'Raw'.
- Copy the url.
- This is the url to assign the path for csv.
