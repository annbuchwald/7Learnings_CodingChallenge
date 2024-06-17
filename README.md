# 7Learnings Data Scientist Code Challenges

Hello potential 7Learnings colleague!
This coding challenge is an opportunity for you to demonstrate your skills and knowledge regarding data science as well as your ability to work independently and use documentation where required. It is not about getting the right solution, try to get as far as you can we will discuss your approach and experience in the interview.

## The Coding Challenge

This repository contains a jupyter notebook with the coding challenge consisting of 2 parts. We also provied data in `coding_challenge.csv` which you can use in case you get stuck in Part 1. 
Create a new git repository for this project and organize your code within that repo. You can provide your solution and thoughtprocess directly within the notebook.
Once you are finished commit and push your code and email the link to your 7Learnings contact.

We adivse you to use a virtual environment and install the dependencies there:
 ```
 virtualenv venv
 source venv/bin/activate
 pip install -r requirements.txt
 ```
 
In order to succesfully do this coding challenge you will need to  have a [gmail account](https://accounts.google.com/signup/v2/webcreateaccount?continue=https%3A%2F%2Fmyaccount.google.com%3Futm_source%3Daccount-marketing-page%26utm_medium%3Dcreate-account-button&flowName=GlifWebSignIn&flowEntry=SignUp) to enter the [google cloude console](https://console.cloud.google.com) where you can create your first project. Google might keep trying to get you to sign up for their free trial but you can safely ignore that, our challenge works with the [Sandbox version](https://cloud.google.com/bigquery/docs/sandbox). 

Once you finish setting up your project you will need to run 


```
gcloud auth application-default login
```
and also set to your default project. 

If you run into issues with using BigQuery in Jupyter Notebook you can refer to the documentation [here](https://cloud.google.com/bigquery/docs/visualize-jupyter) and the links provided above where you can find all the information you will need. 

#### Time Allotment
We respect your time and don't expect you to spend more than 3 hours on this. Try to get as far as you can, your solutions will then be discussed in the next interview, feel free to also add comments and explain what you intended to do. 


## What We Review

Your application will be reviewed by our engineers. The aspects of your code we will judge include:

- ability to get the technical environment set up 
- sql coding knowledge
- data cleaning and abstraction
- understanding of time-dependent data
- machine learning knowledge and evaluation metrics 


