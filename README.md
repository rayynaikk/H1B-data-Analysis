# H1B-data-Analysis
We have choosen this dataset to derive insights for a particular year(FY2016) about the number of cases filed, the number of cases approved or denied, the companies which are filing the application on behalf of their non-immigrant employees and their approval rate, etc.
Link to dataset:  https://www.kaggle.com/datasets/jmpark746/h1b-visas


1 Motivation

H-1B Visa is a visa in the U.S. under the Immigration and Nationality Act, section
101(a)(15)(H) that allows U.S. employers to temporarily employ foreign workers in
specialty occupations. A specialty occupation requires the application of specialized
knowledge and a bachelor’s degree or the equivalent of work experience.
We have choosen this dataset to derive insights for a particular year(FY2016) about the
number of cases filed, the number of cases approved or denied, the companies which are
filing the application on behalf of their non-immigrant employees and their approval rate,
etc.


2 Project Description

H-1B visas are a category of employment-based, non-immigrant visas for temporary
foreign workers in the United States. For a foreign national to apply for an H1-B visa, a
US employer must offer them a job and submit a petition for a H- 1B visa to the US
immigration department (Wikipedia (2021, March 8), H-1B visa). Visas are awarded to
employers on a first come first serve basis, with applications accepted each year beginning
April. If the applications exceed an annual cap set by the government in the first five
business days of April, visas are awarded through a lottery system (Neil G. Ruiz (2017,
April 27), Key facts about U.S. H1B Visa program).

The H1B Visa enables foreign skilled workers to stay in the US for up to six years and
apply for permanent residency in the interim. It is important for the U.S. Department of
Labor to identify which employers are sending the greatest number of H1B Visa
applications and what is the percentage share of the annual 85,000 visa cap for the
employers with most applications. At the same time, figure out the most common job title
and their relative wages for which the greatest number of applications are filed.
This study provides information about the employment gaps within the U.S., which are
filled by foreign workers. This gives an idea as to which areas the U.S. government should
emphasize to encourage domestic students to develop more local workforce in those job
domains for the future. At the same time, it aims to provide guidance for employment in
the US to international students.


3 Data Loading & its Description

We found relevant dataset about H-1B from Kaggle, which consists of more than 50,000
records and includes 15 features in the main schema such as case number, case status, case
submitted, decision date, employer details, job and salary related information and so on.
The cases are divided into 4 types: CERTIFIED, CERTIFIED-WITHDRAWN, DENIED,
WITHDRAWN. We have the following information for each record: We have used the
Azure Data Studio to upload the .csv file and derive the insights from data.
CASE_NUMBER - A unique case ID for every applicant.

3
BUAN 6320.002- Database Foundations For Business Analytics H-1B ANALYSIS
CASE_STATUS – The target variable consists of 4 different values. Status is associated
with the last significant event.
CASE_SUBMITTED – The date of case submission DECISION_DATE - The date when
the decision was rolled out for a perticular case EMPLOYEE_ID - This is a unique ID for
each employee AGENT_REPRESENTING_EMPLOYER - It is a yes/no field to
represent if an employee is represented by an agent.
AGENT_ID – This is a unique ID for each agent
JOB_Title – Title of the Job
SOC_CODE - This is a unique code for each occupation. FULL_TIME_POSITION –
Whether the position is full time or not
PREVAILING_WAGE - The prevailing wage for a job position is defined as the average
wage paid to similarly employed workers in the requested occupation in the area of
intended employment
PW_UNIT_OF_PAY - It is the unit of pay for prevailing wages. H1B_DEPENDENT -
It is a yes/no field to represent if there are any dependents on the H1B applicant.
WILLFUL_VIOLATOR - It is a yes/no field to represent if the employer has violated the
H1B rules and has been denied the hiring of workers for a period of time.
WORKSITE_LOC_ID - City and State information of the foreign worker’s intended area
of employment
