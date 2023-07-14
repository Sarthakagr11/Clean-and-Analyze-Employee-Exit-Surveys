# Clean-and-Analyze-Employee-Exit-Surveys

In this guided project, I worked with exit surveys from employees of the Department of Education, Training and Employment (DETE) and the Technical and Further Education (TAFE) institute in Queensland, Australia.
In this project, I want to know the following:

* Are employees who only worked for the institutes for a short period of time resigning due to some kind of dissatisfaction? What about employees who have been there longer?
* Are younger employees resigning due to some kind of dissatisfaction? What about older employees?
  
I combined the results for both surveys to answer these questions. However, although both used the same survey template, one of them customized some of the answers. I aim to do most of the data cleaning and start analyzing the first question.

Below is a preview of a couple columns we'll work with from the dete_survey.csv:

ID: An id used to identify the participant of the survey</br>
SeparationType: The reason why the person's employment ended</br>
Cease Date: The year or month the person's employment ended</br>
DETE Start Date: The year the person began employment with the DETE

Below is a preview of a couple columns we'll work with from the tafe_survey.csv:

Record ID: An id used to identify the participant of the survey</br>
Reason for ceasing employment: The reason why the person's employment ended</br>
LengthofServiceOverall. Overall Length of Service at Institute (in years): The length of the person's employment (in years)</br>
