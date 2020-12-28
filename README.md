# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

### Overview
> The new format for the SAT was released in March 2016. As an employee of the College Board - the organization that administers the SAT - you are a part of a team that tracks statewide participation and recommends where money is best spent to improve SAT participation rates. Your presentation and report should be geared toward **non-technical** executives with the College Board and you will use the provided data and outside research to make recommendations about how the College Board might work to increase the participation rate in a **state of your choice**.

---

### Research Question
- Which states have the lowest scores for the ACT exam?
- Which states have the lowest scores for the SAT exam?
- Is there a correlation between the SAT Math score and the SAT ERW score?

---

### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)

--- 

### Datasets
For this project, I worked on six provided datasets:

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)
- [2018 SAT Scores](./data/sat_2018.csv)
- [2018 ACT Scores](./data/act_2018.csv)
- [2019 SAT Scores](./data/sat_2019.csv)
- [2019 ACT Scores](./data/act_2019.csv)

These data give average SAT and ACT scores by state, as well as participation rates for the classes of 2017, 2018, and 2019.

You can see the sources for the SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/) and [here](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows).

**This data has been compiled into CSV files which are also included in the *data* directory of this repo**

- Data Dictionnary

| Features | Type | Dataset | Description |
| --- | --- | --- | --- |
| state | object | SAT/ACT | Any given State. |
| participation_sat_17 | float | SAT | SAT Participation Rate in a given state in 2017 |
| erw_sat_17 | integer | SAT | Mean score for SAT English/Writing in 2017 |
| math_sat_17 | integer | SAT | Mean score for SAT Math in 2017 in a given state |
| total_sat_17 | integer** | SAT | Mean total SAT score a given state |
| participation_act_17 | float | ACT | ACT Participation Rate in a given state in 2017 |
| english_act_17 | float | ACT | Mean score for ACT English in 2017 in a given state|
| math_act_17 | float | ACT | Mean score for ACT Math in 2017 in a given state |
| reading_act_17 | float | ACT | Mean score for ACT Reading in 2017 in a given state |
| science_act_17 | float | ACT | Mean score for ACT Science in 2017 in a given state |
| composite_act_17 | float | ACT | Mean score for ACT Composite in 2017 in a give state |
| participation_sat_18 | float | SAT | SAT Participation Rate in a given state in 2018 |
| erw_sat_18 | integer | SAT | Mean score for SAT English/Writing in 2018 |
| math_sat_18 | integer | SAT | Mean score for SAT Math in 2018 in a given state |
| total_sat_18 | integer | SAT | Mean total SAT score a given state in 2018 |
| participation_act_18 | float | ACT | ACT Participation Rate in a given state in 2018 |
| composite_act_18 | float | ACT | Mean score for ACT Composite in 2018 in a give state |
| math_sat_19 | float | SAT |*Mean score for SAT Math in 2019 in a given state |
| ebrw_sat_19  | integer | SAT | Mean score for SAT English/Writing in 2019 |
| participation_sat_19 | integer | SAT | SAT Participation Rate in a given state in 2019 |
| total_sat_19 | integer | SAT | Mean total SAT score a given state |
| participation_act_19 | float | ACT | ACT Participation Rate in a given state in 2019 |
| composite_act_19 | float | ACT | Mean score for ACT Composite in 2019 in a give |


### Conclusion and Recommendation

- There is no association between ACT and SAT scores on Math
- There is a weak relationship between ACT Reading/Writing and SAT Reading/Writing
- There is a strong relationship between SAT scores in 2017 and 2018
- States with the lowest SAT scores include: North Dakota, Mississippi, Iowa
- States with highest SAT scores include: Delaware, Michigan, Connecticut, Colorado, Idaho
- States with the lowest ACT scores include: Maine
- States with highest ACT scores include: Alabama, Kentucky, Wisconcin, Utah, Tennessee, South Carolina
- Federal and states agencies play an important role in increasing the states participation to SAT/ACT. 
- More states should follow North Dakota state's path by mandating SAT/ACT to all high scool students
- Make freely available all costs related to the SAT/ACT tests  

### REFERENCES

2018 and 2019 state-by-state average results and participation for the SAT are available in PDF reports [here](https://reports.collegeboard.org/sat-suite-program-results/state-results). 2018 ACT state-by-state mean composite scores and participation rates are [here](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf) and 2019 data can be found [here](https://www.act.org/content/dam/act/secured/documents/cccr-2019/Average-Scores-by-State.pdf).
- Outside Research
- https://www.edweek.org/policy-politics/north-dakota-is-first-state-to-let-districts-use-act-instead-of-state-exam/2018/03
- https://www.inforum.com/news/education/4676771-SAT-scores-drop-participation-rises
