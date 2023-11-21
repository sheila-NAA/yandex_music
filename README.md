# yandex_music

# Contents <a id='back'></a>

* [Introduction](#intro)
* [Stage 1. Data overview](#data_review)
    * [Conclusions](#data_review_conclusions)
* [Stage 2. Data preprocessing](#data_preprocessing)
    * [2.1 Header style](#header_style)
    * [2.2 Missing values](#missing_values)
    * [2.3 Duplicates](#duplicates)
    * [2.4 Conclusions](#data_preprocessing_conclusions)
* [Stage 3. Testing the hypotheses](#hypotheses)
    * [3.1 Hypothesis 1: user activity in the two cities](#activity)
    * [3.2 Hypothesis 2: music preferences on Monday and Friday](#week)
    * [3.3 Hypothesis 3: genre preferences in Springfield and Shelbyville](#genre)
* [Findings](#end)

ps. the table of content is a breakdown of the project.

## Introduction <a id='intro'></a>
Whenever we're doing research, we need to formulate hypotheses that we can then test. Sometimes we accept these hypotheses; other times, we reject them. To make the right decisions, a business must be able to understand whether or not it's making the right assumptions.

 In this project, we'll compare the music preferences of the cities of Springfield and Shelbyville. we'll study real Yandex.Music data to test the hypotheses below and compare user behavior for these two cities.
 ### Goal: 
Test three hypotheses:
1. User activity differs depending on the day of the week and from city to city. 
2. On Monday mornings, Springfield and Shelbyville residents listen to different genres. This is also true for Friday evenings. 
3. Springfield and Shelbyville listeners have different preferences. In Springfield, they prefer pop, while Shelbyville has more rap fans.

### Stages 
Data on user behavior is stored in the file `/datasets/music_project_en.csv`. There is no information about the quality of the data, so you will need to explore it before testing the hypotheses. 

First, I'll evaluate the quality of the data and see whether its issues are significant. Then, during data preprocessing, I will try to account for the most critical problems.
 
The project will consist of three stages:
 1. Data overview
 2. Data preprocessing
 3. Testing the hypotheses
 
[Back to Contents](#back)

