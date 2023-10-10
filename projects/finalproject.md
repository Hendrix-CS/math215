---
layout: work
type: Project
num: Final
worktitle: Final Project
topicdue: Tuesday, October 24 
draftdue: Tuesday, November 21
finaldue: Monday, December 5
---

## Description

Instead of a final exam, you will complete a final project which will
help summarize your statistics and data analysis skills we have been building through our labs with R.

### Important dates

-   Project topic: **{{page.designdue}} @ 5pm**
-   Rough Draft due: **{{page.draftdue}} @ 8pm**
-   Project due: **{{page.finaldue}} @ 8pm**
-   Presentations: **{{page.finaldue}}, 8:30-11:30am**

## Dataset

Your first task is to find an interesting dataset that you will explore in your project. This could be something related to your academic interests, or something else you would just like to explore.

Use your chosen dataset to create a new public dataset on Kaggle in your account. Then create a notebook that includes this dataset and reads in the information into a data frame.

You will need to have your topic and dataset approved by the instructor by **{{page.designdue}} @ 5pm**.

There are an enormous number of datasets available formatted as CSV files. Here are some resources to help your initial search.

*  [R CSV Datasets](https://vincentarelbundock.github.io/Rdatasets/datasets.html). 
*  [Centre Dataset Resources](https://library.centre.edu/DataScience/finddatasets)
*  [Data.gov](https://data.gov/)
*  [USGS Science Data](https://www.usgs.gov/products/data)

The following table lists of a few of them that I think are in an easily managable state and could provide some interesting analysis questions given our R skills, but feel free to choose one not on this list.

| Dataset | Documentation | Data |
|------|------|-----|
| Fertility | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/AER/Fertility2.html) | [Fertility2.csv](https://vincentarelbundock.github.io/Rdatasets/csv/AER/Fertility2.csv) |
| Home Mortgage Disclosure Act | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/AER/HMDA.html) | [HMDA.csv](https://vincentarelbundock.github.io/Rdatasets/csv/AER/HMDA.csv) |
| Parade Salary Survey | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/AER/Parade2005.html) | [Parade2005.csv](https://vincentarelbundock.github.io/Rdatasets/csv/AER/Parade2005.csv) |
| Labor Force Participation | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/AER/PSID1976.html) | [PSID1976.csv](https://vincentarelbundock.github.io/Rdatasets/csv/AER/PSID1976.csv) |
| Teacher Ratings | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/AER/TeachingRatings.html) | [TeachingRatings.csv](https://vincentarelbundock.github.io/Rdatasets/csv/AER/TeachingRatings.csv) |
| Smoking Cessation | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/asaur/pharmacoSmoking.html) | [Smoking.csv](https://vincentarelbundock.github.io/Rdatasets/csv/asaur/pharmacoSmoking.csv) |
| British Election Panel Study | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/carData/BEPS.html) | [BEPS.csv](https://vincentarelbundock.github.io/Rdatasets/csv/carData/BEPS.csv) |
| Canadian National Election Study | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/carData/CES11.html) | [CES11.csv](https://vincentarelbundock.github.io/Rdatasets/csv/carData/CES11.csv) |
| Titanic Survival | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/carData/TitanicSurvival.html) | [TitanicSurvival.csv](https://vincentarelbundock.github.io/Rdatasets/csv/carData/TitanicSurvival.csv) |
| Vocabulary and Education | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/carData/Vocab.html) | [Vocab.csv](https://vincentarelbundock.github.io/Rdatasets/csv/carData/Vocab.csv) |
| Post-Coma Recovery of IQ | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/carData/Wong.html) | [Wong.csv](https://vincentarelbundock.github.io/Rdatasets/csv/carData/Wong.csv) |
| Mortgage Subsidies and GI Bill | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/causaldata/mortgages.html) | [mortgages.csv](https://vincentarelbundock.github.io/Rdatasets/csv/causaldata/mortgages.csv) |
| Cricketers Lifespans | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/DAAG/cricketer.html) | [cricketer.csv](https://vincentarelbundock.github.io/Rdatasets/csv/DAAG/cricketer.csv) |
| Airbags and Accidents | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/DAAG/nassCDS.html) | [nassCDS.csv](https://vincentarelbundock.github.io/Rdatasets/csv/DAAG/nassCDS.csv) |
| Unemployment | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/Benefits.html) | [Benefits.csv](https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/Benefits.csv) |
| Car Choice | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/Car.html) | [Car.csv](https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/Car.csv) |
| Doctor Visits | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/DoctorAUS.html) | [DoctorAUS.csv](https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/DoctorAUS.csv) |
| Extramarital Affairs | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/Fair.html) | [Fair.csv](https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/Fair.csv) |
| Preservation of Kakadu National Park | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/Kakadu.html) | [Kakadu.csv](https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/Kakadu.csv) |
| Ketchup Buying | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/Ketchup.html) | [Ketchup.csv](https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/Ketchup.csv) |
| Visits to Physician Office | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/OFP.html) | [OFP.csv](https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/OFP.csv) |
| Return to School | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/RetSchool.html) | [RetSchool.csv](https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/RetSchool.csv) |
| Tobacco Budget Share | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/Tobacco.html) | [Tobacco.csv](https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/Tobacco.csv) |
| Medical Expenses in Vietnam | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/VietNamI.html) | [VietNamI.csv](https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/VietNamI.csv) |
| Wife Working Hours | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/Ecdat/Workinghours.html) | [Workinghours.csv](https://vincentarelbundock.github.io/Rdatasets/csv/Ecdat/Workinghours.csv) |
| Air Pollution | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/geepack/ohio.html) | [ohio.csv](https://vincentarelbundock.github.io/Rdatasets/csv/geepack/ohio.csv) |
| Baseball | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/ISLR/Hitters.html) | [Hitters.csv](https://vincentarelbundock.github.io/Rdatasets/csv/ISLR/Hitters.csv) |
| Orange Juice Prices | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/ISLR/OJ.html) | [OJ.csv](https://vincentarelbundock.github.io/Rdatasets/csv/ISLR/OJ.csv) |
| Eighth-Grade Test Scores | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/MASS/nlschools.html) | [nlschools.csv](https://vincentarelbundock.github.io/Rdatasets/csv/MASS/nlschools.csv) |
| Blizzard Salary | [HTML](https://vincentarelbundock.github.io/Rdatasets/doc/openintro/blizzard_salary.html) | [blizzard_salary.csv](https://vincentarelbundock.github.io/Rdatasets/csv/openintro/blizzard_salary.csv) |


## Paper 

Based on the data you choose, you will be writing a paper as a Kaggle Notebook, with code and richly annotated with Markdown blocks, describing your analysis of particular questions involving statistics. 

Your paper should have the following headings and sections: 

*  Overview
*  Methodology
*  Exploratory Data Analysis
*  Inference
*  Conclusions

### Overview

First, you should lay the groundwork for the topic you will be discussing in your paper. What would someone need to know about the topic if they are unfamiliar with it in order to understand your analysis below? What questions will you be answering with your graphs, statistical analysis, and later discussion? Do you have a hypothesis for what you will find when you do the analysis?

{% include note.html content="You must be asking at least **two** different questions about your dataset." %}

This will probably involve a few references to outside material or other websites. If it is a website, make a link to it; if it is a textbook, use a consistent citation structure.
You may use [MLA](https://owl.purdue.edu/owl/research_and_citation/mla_style/mla_formatting_and_style_guide/mla_formatting_and_style_guide.html), [APA](https://owl.purdue.edu/owl/research_and_citation/apa_style/apa_formatting_and_style_guide/general_format.html), or other formats, as long as a reader can easily find the reference.

Also in this section explain what about this topic is of interest to *you* and why you selected it for this paper.

### Methodology

Detail in a few sentences how this specific data was gathered, when,
and by whom. Is it from a survey or from an experiment? Clearly explain the methodology used for the survey or experiment design, using the language we discussed in *Unit 3: Producing Data* of our textbook.
You will need to research the original paper that discussed
the dataset to find this information. Summarize this in your own words,
do not copy from the source. 

{% include note.html content="If you cannot find an appropriate data provenance or original source, then this dataset is probably not the best one to use for this project." %}

### Data Notebook

The reader will want to know some information about your chosen dataset. Load up the data as a variable, show a few rows of the data frame, and provide a description of each of the variables being used in your analysis. Clearly indicate the type of each variable of interest (categorical or quantitative) and the role it is playing in your analysis.

### Exploratory Data Analysis

Next, you should examine the data using appropriate exploratory tools we have learned (boxplots, scatter plots, two-way tables, bar charts, etc). Use these graphs, and generate some summary statistics (mean, median, standard deviation, etc), to visualize and understand your data. Clearly discuss why the tools and statistics you show are the right way to analyze the data.

### Inference

Finally, use the appropriate statistical tools we have discussed in class to make *inferences* about your data. Are you estimating population means and understaning their difference among subgroups or to a hypothesis? Are you estimating population proportions and examining differences? Are confidence intervals involved? Are your conclusions statistically significant? Clearly explain the tools you use and why they are the right approach to answer your questions.

### Conclusions

Write a paragraph summarizing your findings and put them in context of your original topic introduction. Did your results match your hypotheses? Are there any reasons why your results might not be accurate? What future questions could be asked about your dataset?

## Presentation

Everyone will present their projects on {{page.finaldue}}.
Your presentation, using PowerPoint, Prezi, Google Slides, or some
other appropriate presentation medium, will be **at most 5 minutes
long**. You should not present your Kaggle notebook, but extract key portions and data from your writeup into a formal presentation.

{% include warning.html content="Practice beforehand to make sure
you have a good sense for how much time you have. Five minutes is not
very long at all." %}

Your presentation should include **four slides**. The four slides should follow this structure:

*   A quick summary of the context of the dataset
*   What are the questions your are investigating?
*   What are some visualizations and summary statistics?
*   What were your conclusions made through inference techniques?

## What to turn in

You should turn in two things on Teams

*   Your presentation slides (if your slides are on Prezi or Google Slides or some other cloud-based system, just submit the URL).
*   A link to your public Kaggle notebook.
