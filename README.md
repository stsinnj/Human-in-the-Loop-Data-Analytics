# 3406 Assessment 2: Weekly trends of human step counts

## The driving question: 
- *What is the trend of week-to-week step data?*

The project utilises gathered step count data to explore data from the project participants, who provides the data for analysis. 

Our aim would be to find patterns of participant’s weekly behaviour and analyse their movement/exercise rate in a weekly fashion and find any individual or universal trends.
Weekly data represents a more accurate approach then analysing monthly trend, and is a significant time period for behaviour analysis.

Sub-parts of the driving question was utilised to have a higher coverage of answer the driving question.
We also do understand the limitation of our project, with a small amount of samples and limited data variables, we have to rely and on the insight shown from each participant. We aim to produce ethical, meaningful results while being aware of of uncertainty produced in the study.

All the findings were produced with Jupyter notebook of Python 3.0, with 6 process notebook for reference of analysis and a product notebook for running all step data from the apple device formats.

</br>

## Team members:

**Sheng Wang**: Manager, Doomsayer

**Tiannan Chen**: Tracker, Ed-tracker

**Tianshu Shen**: GitHub expert, Grading requirements

**Xin Guo**: Product Notebook co-ordinator, README co-ordinator

**Shangfei Wang**: Product Notebook co-ordinator, Final Reviewer

**Audrey Ao**: Product Notebook co-ordinator, Final Reviewer

</br>

## Table of content 

- [Product notebook](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/RE6-Group4-Final-Notebook.ipynb)
- [Process notebook: Tianshu Shen](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Week12-TianshuShen-Summarize.ipynb)
- [Process_notebook: Audrey Ao](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Week12_Audrey_individual_product_notebook.ipynb)
- [Process notebook: Sheng Wang](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Week12-ShengWang_personal_code.ipynb)
- [Process notebook: Xin Guo](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Week10_xinguo.ipynb)
- [Process notebook: Tiannan Chen](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Tiannan_Chen%20Personal%20Product%20Notebook.ipynb)
- [Process notebook: Shangfei Wang](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Week13-ShangfeiWang_personal_code.ipynb)

</br>

## Key files and variables:

These are files that have to be read by the product notebook in order to obtain results and visualisations. 

- [Extracted step data example](https://raw.github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/main/src/resources/Participant-01.csv?token=GHSAT0AAAAAAAAAHGL3SCR27UFH4C32ZD52Y3DOANA) 

The first step data has variables of Start and finish time both recorded in hour and also the numerical step counts of each of these times. The time could be treated as dates, and was thus treated as weeks by us after some wrangling.

- [Extracted detailed step data example](https://raw.github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/main/src/resources/Participant-01-second-detail.csv?token=GHSAT0AAAAAAAAAHGM3UCEKRXZJHD2NDEPWY3H7JZA)

The second step data includes the date of the recording, then the time(hour), and the steps taken at each measurement. This could be wrangled into the same format as the first step data.

- [Extra dataset: Australian Holiday data](https://raw.github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/main/src/resources/australian-public-holidays-combined-2022.csv?token=GHSAT0AAAAAAAAAHGM2RGHQU5DGLFDCQEFGY3H7IXA)

The third file is the Australian holiday data, with the date time of each holiday and as well as the state of the holiday.

- [Datasets](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/tree/main/src/resources)

</br>

## Ethical analysis:

[Ethical analysis](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Ethical-analysis)

</br>


## Use of Issues and wiki for group processes

### Issue

[Use of Issues and wiki for group processes](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Issue-Collection)


### Meeting records

[Group_meeting](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Meeting-minutes)

### Group member roles

[Group member roles](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Group-Roles)

### Group member Work overview

- [Weekly Overview: Audrey](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-Audrey)
- [Weekly Overview: Shangfei Wang](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-Shangfei-Wang)
- [Weekly Overview: ShengWang](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-ShengWang)
- [Weekly Overview: Tian Shu Shen](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-Tian-Shu-Shen)
- [Weekly Overview: Tiannan Chen](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-Tiannan-Chen)
- [Weekly Overview: Xin Guo](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-Xin-Guo)

</br>



## Reflection on group processes

[Reflection on group processes](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Reflection)

</br>

## Think-aloud and Cognitive Walkthrough

[Report of Think-aloud](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Think-Aloud) \
[Cognitive walk through from think aloud](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Cognitive-Walkthrough)

</br>


## Overview of team’s work:

### Sub-Part 1:

The result shows that by using a certain time frame of weekly step data could not predict the next time frame. As the inaccuracy of prediction could be seen in the figure from June to September, where January to May’s data was used to train for the predictor. 

![](https://raw.github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/main/src/images/shangfei.png?token=GHSAT0AAAAAAAAAHGM3XYQPPJC4VT74ZCEOY3H6UWA)

- [Link’s to the contributor’s report](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-Shangfei-Wang)
- [Link to contributor’s code](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Week12-ShangfeiWang_personal_code.ipynb)

</br>


### Sub-Part 2:
The result shows that weekly step counts is not effected by holidays, as shown in the figure, step counts of the two participant did not follow the patterns of holiday proportion of a week.

![](https://raw.github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/main/src/images/illustration.png?token=GHSAT0AAAAAAAAAHGM2ZMO22UAYT6Z5ROOEY3H6RCA)

- [Links to the contributor’s report](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-Tian-Shu-Shen)
- [Links to contributor’s code](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Week12-TianshuShen-Summarize.ipynb)

</br>

### Sub-Part 3:
The results indicates whether an individual meets the daily requirement of exercise of adult, any weeks with above 70000 steps meets the requirement. As seen in the figure, it shows the participant only had two weeks of enough exercise, although other form of exercise also maintains health and this varies by participants.

![](https://raw.github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/main/src/images/tiannan.png?token=GHSAT0AAAAAAAAAHGM3WVFKGRDD2EVHSTQYY3H6Z7A)

- [Link’s to contributor’s report](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-Tiannan-Chen)
- [Link to contributor’s code](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Tiannan_Chen%20Personal%20Product%20Notebook.ipynb)

</br>

### Sub-Part 4:
The results indicates that people walk don't have a general pattern on walking during each month, where the week with highest steps spread out through a month as seen in the figure below.

![](https://raw.github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/main/src/images/audrey.png?token=GHSAT0AAAAAAAAAHGM3YZYNCLFEC5OT3O4IY3IOSUA)

- [Link’s to contributor’s report](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-Audrey)
- [Link to contributor’s code](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Week12_Audrey_individual_product_notebook.ipynb)

</br>

### Sub-Part 5:
The results shows that participant's weekly step counts differ between winter and summer, as shown on the figure of the progressing step counts over seasons measured in week.

![](https://raw.github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/main/src/images/xin.png?token=GHSAT0AAAAAAAAAHGM3D3QVPAFRJUEARQPGY3H67UQ)

- [Link to contributor’s report](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-Xin-Guo)
- [Link to contributor’s code](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Week10_xinguo.ipynb)
- [Link to contributor's code(test for participant 4 and 7)](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/week11_xinguo.ipynb)

</br>

### Sub-Part 6:
The result of the work shows that for different individuals the significance of weekend on weekly data varies between individuals. As seen in the figures below, participant 1 has similar weekly steps when subtracted weekend comparing to weekly steps subtracted from week days. Although this varies among participants.

![](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/images/sheng3.png)

- [Link to contributor’s report](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/wiki/Weekly-Overview:-ShengWang)
- [Link to contributor’s code](https://github.sydney.edu.au/xguo0149/2022-DATA3406-RE06-Group04/blob/main/src/Week12-ShengWang_personal_code.ipynb)



