# Boston_housing

<img src="https://github.com/Mukhriddin19980901/Boston_housing/blob/main/pics/boston3.png" width="700" height="500" />

<img src="https://github.com/Mukhriddin19980901/Boston_housing/blob/main/pics/boston_info.png" width="700" height="500" />

# Introduction.
In order to use this model you need to create the environment on you computer.This is a Keras easy type data for beginners of Data Science.
Data consists of 13 different features in both train and test input datas.Our output data is average prices of the 404 accomadations in Boston,USA.we needed to predict prices of 102 houses in test data.I used neural networks to increase the accuracy rate rather than using LinearRegression model from scikit-learn library.  

> You can compare the prices of that area

<img src="https://github.com/Mukhriddin19980901/Boston_housing/blob/main/pics/prices.png" width="700" height="500" />


# Step - 1 . Downloading model

- First click the buttons *windows+R*  and type *cmd* in box below clone my model from github on the black window

       C:\>  git clone https://github.com/Mukhriddin19980901/boston_housing.git

- Write this command on black window.
 
       C:\> cd boston_housing
 
# Step - 2 .Creating virtual environment 

- You need to upgrade your pip command to create environment

       C:\boston_housing>python.exe -m pip install --upgrade pip


- Here you need to install environment module and you can create  your virtual environment

       C:\boston_housing>python -m venv pip install --user virtualenv
 
 - Give the name to the environmentyou can give any name instead *environment_name*)

       C:\boston_housing>python -m venv environment_name

- Then you need to activate the environment

       C:\boston_housing>environment_name\Scripts\activate.bat

- Install all required libraries from the *requirements.txt* file

      (environment_name) C:\boston_housing> pip install -r requirements.txt

- Now you can work on jupyter notebook

      (environment_name) C:\boston_housing>jupyter notebook


# Step - 3 . Coding
 
- Now you can see the code [here](https://github.com/Mukhriddin19980901/Boston_housing/blob/main/boston_house_prices.ipynb).I used mean squared error loss function and rmsprop ([Root Mean Squared Propagation](https://keras.io/api/optimizers/rmsprop/),)

- The model summary :

<img src="https://github.com/Mukhriddin19980901/Boston_housing/blob/main/pics/model_summary.png" width="700" height="500" />

-Here you can compare the flactuation of training accuracy and loss after every epoch.


<img src="https://github.com/Mukhriddin19980901/Boston_housing/blob/main/pics/download.png?raw=true" width="700" height="500" />


- As far as validation concerned the numbers are  , validation accuracy is **79 %**  and validation loss **64 %**


🔴 ***If you find it useful give a star to this repo and follow me on [Kaggle](https://www.kaggle.com/muhriddinmalik) and [Linkedin](https://www.linkedin.com/in/mukhriddin-khaydarov-8a9729209?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3Bay%2BB1xqoRZKf2DcZnvkRVw%3D%3D)***
