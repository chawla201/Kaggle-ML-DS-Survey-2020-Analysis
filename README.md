<h1 align='center'>Kaggle ML & DS Survey 2020</h1>

<p align="center">
  <img src="https://github.com/chawla201/Kaggle-ML-DS-Survey-2020-Analysis/blob/master/images/header.png" width=1000>
</p>

 [2020 Kaggle ML & DS Survey](https://www.kaggle.com/c/kaggle-survey-2020/overview) is the fourth edition of the annual industry-wide survey that presents a truly comprehensive view of the state of data science and machine learning. The survey was live for 3.5 weeks in October, and kaggle collected a little more than __20000__ responses.


## Data
#### Main Data:
* <strong>[kaggle_survey_2020_responses.csv](https://github.com/chawla201/Kaggle-ML-DS-Survey-2020-Analysis/blob/master/data/kaggle_survey_2020_responses.csv):</strong> 39+ questions and 20,036 responses

Responses to multiple choice questions (only a single choice can be selected) were recorded in individual columns. Responses to multiple selection questions (multiple choices can be selected) were split into multiple columns (with one column per answer choice).
#### Supplementary Data:
* <strong>[kaggle_survey_2020_answer_choices.pdf](https://github.com/chawla201/Kaggle-ML-DS-Survey-2020-Analysis/blob/master/data/supplementary_data/kaggle_survey_2020_answer_choices.pdf):</strong> list of answer choices for every question. With footnotes describing which questions were asked to which respondents.<br>
* <strong>[kaggle_survey_2020_methodology.pdf](https://github.com/chawla201/Kaggle-ML-DS-Survey-2020-Analysis/blob/master/data/supplementary_data/kaggle_survey_2020_methodology.pdf):</strong> a description of how the survey was conducted. You can ask additional questions by posting in the pinned Q&A thread.
#### Cleaned and Transformed Data:
After cleaning, transforming and splitting the provided data(kaggle_survey_2020_responses.csv), we get 4 seperate DataFrames, namely:
<ol>
  <li>questions: Questions asked in the survey</li>
  <li>response: Responses entered by the respondents</li>
  <li>professionals: Responses by professional respondents</li>
  <li>non professionals: Responses by non-professional respondents</li>
</ol>
According to the Survey Methodology provided with the Data, a respondent can be categorised as `Non Professional` if the respondent is either a student or unemployed or has never spent money on cloud services. <br>

## Tecnologies Used:
    
* <strong>Python</strong>
* <strong>Pandas</strong>
* <strong>Numpy</strong>
* <strong>Matplotlib</strong>
* <strong>Seaborn</strong>
* <strong>Plotly</strong>

## Exploratory Data Analysis:
EDA of the data provides an overview of the demographic distributions and general trends in terms of Age, Location, Qualification, Experience, etc. <br> 
Since all the graphs and plots are created using Plotly, it is advised to look at the EDA Python Notebook (2020-kaggle-ml-ds-survey-analysis.ipynb) in [Kaggle Notebooks](https://www.kaggle.com/chawla201/2020-kaggle-ml-ds-survey-analysis) in [nbviewer](https://nbviewer.jupyter.org/github/chawla201/Kaggle-ML-DS-Survey-2020-Analysis/blob/master/EDA%20(All%20Respondents).ipynb) as github does not support interactive graphs.
<br>
We have two EDA files:
- [EDA (All Respondents)](https://nbviewer.jupyter.org/github/chawla201/Kaggle-ML-DS-Survey-2020-Analysis/blob/master/EDA%20%28All%20Respondents%29.ipynb)
- [EDA (Professionals)](https://nbviewer.jupyter.org/github/chawla201/Kaggle-ML-DS-Survey-2020-Analysis/blob/master/EDA%20%28Professionals%29.ipynb)

In the first one, I considered responses from all the respondents. Whereas in the second exploratory data analysis file, I have considered **only working professionals** to get a better sense of how the professional landscape of Kagglers looks.

<table>
  <tr><td><img src='https://github.com/chawla201/Kaggle-ML-DS-Survey-2020-Analysis/blob/master/images/age_dist.png' width=600></td><td><img src='https://github.com/chawla201/Kaggle-ML-DS-Survey-2020-Analysis/blob/master/images/gender.png' width=600></td></tr>
  <tr><td><img src='https://github.com/chawla201/Kaggle-ML-DS-Survey-2020-Analysis/blob/master/images/country.png' width=600></td><td><img src='https://github.com/chawla201/Kaggle-ML-DS-Survey-2020-Analysis/blob/master/images/education.png' width=600></td></tr>
</table>
<br>



