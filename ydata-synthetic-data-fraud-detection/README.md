# Dealing with massively imbalanced datasets using YData and UbiOps

_Download link for necessary files_: [ydata-synthetic-data files](https://download-github.ubiops.com/#!/home?url=https://github.com/UbiOps/cookbook/tree/master/ydata-synthetic-data-fraud-detection/ydata-synthetic-data-fraud-detection)

In this recipe we will make use of synthetic data generation to balance highly 
imbalanced classes,in particular, generation of synthetic fraudulent events.

The use of synthetic data for this type of use cases helps to improve the 
accuracy of fraud detection models in many areas from the banking industry.


## Machine Learning and imbalanced datasets

Highly imbalanced datasets are extremely challenging for data teams, and they can be found very often in the industry, whether in topics such as detecting fraudulent events, or for money laundry and even credit underwriting.

The commonnality between each one of these use cases? 
The fact that only a small portion of the overall transactions represent one 
particular class. For fraud problems only a portion of those transactions 
were in reality a fraudulent event.

## In this notebook

In this example we will show you how to tackle such imbalanced datasets using YData to train a fraud predictor. 
Subsequently we will show how to deploy that model using UbiOps. 


## How does it work?

**Step 1:** Login to your UbiOps account at https://app.ubiops.com/ and create an API token with project editor
admin rights. To do so, click on *Users & permissions* in the navigation panel, and then click on *API tokens*.
Click on *create token* to create a new token.

![Creating an API token](api_token_screenshot.png)

Give your new token a name, save the token in safe place and assign the following roles to the token: project editor and blob admin.
These roles can be assigned on project level.

**Step 2:** Download the [ydata-synthetic-data files](https://download-github.ubiops.com/#!/home?url=https://github.com/UbiOps/cookbook/tree/master/ydata-synthetic-data-fraud-detection/ydata-synthetic-data-fraud-detection) folder and open `ydata-synthetic-data-fraud-detection.ipynb`. In the notebook you will find a space
to enter your API token and the name of your project in UbiOps. Paste the saved API token in the notebook in the indicated spot
and enter the name of the project in your UbiOps environment. This project name can be found in the top of your screen in the
WebApp. In the image in step 1 the project name is *scikit-example*.

**Step 3:** Run the Jupyter notebook `ydata-synthetic-data-fraud-detection.ipynb` and everything will be automatically deployed to your UbiOps environment! Afterwards you can explore the code in the notebook or explore the application in the WebApp.
