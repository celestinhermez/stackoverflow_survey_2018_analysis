# 2018 Stack Overflow Survey Analysis

For the past 7 years, Stack Overflow has been distributing a survey to its 
users and made available the results for everyone to see and analyze. With
each iteration some questions have been added, and the responses enable a deep
look into the developers who use the platform on a daily basis, both as 
contributers and as users. As a data scientist, I do not consider myself
a traditional developer, and I wanted to confirm whether the respondents
to this survey agree with me.
The results of this analysis are in the file **developer_survey_2018.zip**.

In 2018, almost 100,000 people responded to the 129 questions of the survey,
on topics as varied as demographics (gender, age, country), professional
(developer type, company size, salary, OS used) but also more aspirational
(potential dangers of AI, where they see themselves in 5 years).

The file Developer Survey Analysis.ipynb contains all the analysis I have
conducted on these results. I was particularly interested in the languages
that are popular, whether it is possible to extract elements associated with
higher job satisfaction and who a "typical" developer is. For these three
topics, I also seeked to determine whether the subgroup of data scientists
differs in any way for other, more traditional developers. To conduct the
analysis, I used the CRISP-DM method, which consisted in gathering, wrangling,
preparing, modeling and presenting the data and my results. A HTML version
of this file is available in the repo.

The libraries used for this project are, and will need to be installed to 
sucessfully run the notebook:
- pandas
- numpy
- sklearn
- matplotlib
- scipy
- zipfile
- os
- random
- re
- math
- seaborn

A summary of the insights from this analysis can be found in my [Medium blog
post] (https://medium.com/@celestinhermez/are-data-scientists-typical-developers-an-analysis-of-the-2018-stack-overflow-survey-afaa23cc7a60). It showed that although data scientists do not fundamentally differ
from other developers with regards to the languages they use or how satisfied 
they are with their jobs, they have different backgrounds and come from a 
different demographic. 