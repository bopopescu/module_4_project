# Module 4 Project: Superhero Classification

## Business Case
We are creating a web application for aspiring writers and comic enthusiasts. Our application uses character origin stories to predict whether the character will become a hero or villain. Users can test their characters against our model and use our feedback to enhance their origin stories. This will help writers create deeper plots, stronger characters and overall higher quality content

Objectives:
- Acquire Marvel origin stories via Wikipedia's API. 
- Use neural network to extract deep features
- Perform classification modeling on deep features
- Evaluate and compare model types
- Deploy production model


Project Outline:
- Day One: Source and Collect Data
- Day Two: Data exploration and understanding. Begin modeling processes. 
- Day Three: 
- Day Four:
- Day Five: 


## Data Collection, Exploration and Understanding
- Scrape origin stories using the Wikipedia API. 
- Collected over 100 different origin stories from Marvel

## Data Preparation
- Hero stories were brought in seperatley from villain stories, 
- The two dataframes were then merged together to create a master dataframe.
- Master dataframe was exported as a ``` .json file``` for use on Google Cloud
- Data added to Google Cloud bucket for collaboration 

## Modeling
- Used Google BERT NLP for feature extraction. 
- Used features from BERT and added them to Random Trees classifier in order to make final classifcations. 

## Evaluation

## Deployment
User Story:
Jimmy wants to create a new comic book character. He studies origin stories and think he has created the perfect origin for his new character. The character he has created is intended to be a villain and will give the other heroes a run for their money in the final battle. Jimmy wants to make sure his origin story is wicked enough to genuniely produce the villain he has created. This is where Jimmy would plug his origin story into the 'Story' box on our website and with one click of a button, Jimmy will know how well his story stacks up to the pros... and luckily for Jimmy, it was a villain.

### Google Slides Link
https://docs.google.com/presentation/d/1w-FUZtTbDsBRBQEJegyOWWDg79gr31JLoBdaQb_m1Gs/edit?usp=sharing
