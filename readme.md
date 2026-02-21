### Project schedule: 
   1. Understanding what to do in the above-given Predicting Life Expectancy Project
   2. Identify and get familiar with the tools needed to complete this project
   3. Writing codes
   4. Collecting Data sets
   5. The time duration is 5 days
### Deliverables: 
   1. Predicting Life Expectancy Using Machine Learning.
   2. Making a user interface too as front-end work and writing code as backend work to make the user interact and calculate the Life

### Setting The Development Environment
   1. Creating GitHub account
   2. Creating Slack account
   3. Signing up for cloud services
       1.  Node-Red for front end
       2.  Watson Studio for coding

   • Machine Learning services

# 1.  INTRODUCTION
  1.1          Overview:

 This project is based on predicting the life expectancy of a person. It is the statistical average of the number of years a person is expected to live. Factors affecting life expectancy are Country, Mental and Physical Illness, lifestyle, diet, health care services, financial condition, BMI, alcohol consumption, Diseases, etc.

Here in this Predicting Life Expectancy project, our motive is to find the life expectancy of a person after providing details such as the country he is living in is developed or is developing, BMI of the person, Disease history, Income, Population of that country, Expenditure, etc. So here I have used Machine learning and Artificial Intelligence to predict life expectancy. The data used in the training of the model was the data by WHO taken from Kaggle.

There were almost 22 columns stating different factors affecting Life expectancy and 2939 rows comprising data of different persons from different countries. Based on the results we got on Watson Studio some factors which were not affecting the Life expectancy much were removed and the scoring endpoint was obtained after running full code. This scoring endpoint is the URL that helps us to send payload data to a model or function development for analysis (such as to classify the data or to make predictions).

After obtaining the endpoint the next step is to work on Node-red which is the platform, we can use for developing our front-end page that will have a form asking you your details such as year of birth, adult mortality, infant deaths, BMI, etc. rest we’ll discuss in details later on.

#### Requirements: IBM Cloud, GitHub, Slack, IBM Watson, Node-Red

 1.2          Purpose:
 The purpose of this project is to build a model that will predict the Life Expectancy of a person after giving the details of the BMI, Expenditure, Disease history, etc.

# 2.  Literature Survey
2.1          Proposed Solution:
 The project tries to create a model based on data provided by the World Health Organization (WHO) to evaluate the life expectancy for different countries in years. The data offers data on different person’s Physical health, Mental health, etc from the time frame 2000 to 2015. The data was taken from the website: https://www.kaggle.com/kumarajarshi/life-expectancy- who/data. 

# 3.  Theoretical Survey
3.1          Block diagram
