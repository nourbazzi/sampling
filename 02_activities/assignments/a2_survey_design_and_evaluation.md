# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `1`

Describe the purpose of your survey:
```
The purpose of this survey is to identify the drivers of voluntary turnover among employees in entry- and lower-level positions across the company. The results will be used by the Human Resources Department to help implement workplace changes would most improve employee satisfaction and intention to stay.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: All current employees of the company who hold entry- or lower-level positions, across all departments. "Entry- and lower-level" is defined as non-management roles. Managers and senior staff are excluded.
Sampling frame: The company's internal employee directory, which is a complete, up-to-date list of every current employee, with their department and job grade.
Sampling units: Individual employees.
Observational units: Individual employees.
Overall sampling strategy: Stratified random sampling. The population is divided into non-overlapping strata which are defined by department (and within each department, also defined by job grade if strata are large enough). Then, an independent simple random sample is drawn from each stratum. Finally, the results are pooled for overall estimates.
Justification:  HR's goal is to compare satisfaction and turnover drivers BETWEEN departments so interventions can be targeted. Stratified sampling is exactly the right tool for this: it produces estimates with known precision for each subpopulation (stratum).

```

Your 5-10 question survey:
```
1. How long have you worked at Tech Gnomad?
( )Less than 6 months
( )6 months to 1 year
( )1-2 years
( )2-4 years
( )4+ years

2. Which department do you currently work in?
( )Marketing Department
( )Customer Support Department
( )Accounting Department
( )Product Management Department

3. Overall, how satisfied are you with your job?
( )Very dissatisfied
( )Dissatisfied
( )Neither Satisfied nor dissatisfied
( )Satisfied
( )Very satisfied

4. How likely is it that you'll be working at Tech Gnomad 12 months from now?
( ) Very unlikely
( ) Unlikely
( ) Unsure
( ) Likely
( ) Very likely

5. Please rate how satisfied you are with each of the following aspects of your job. (1 = Very dissatisfied, 5 = Very satisfied)
                                          1   2   3   4   5
   a. your compensation                  ( ) ( ) ( ) ( ) ( )
   b. your workload                      ( ) ( ) ( ) ( ) ( )
   c. the support you get from your manager ( ) ( ) ( ) ( ) ( )
   d. opportunities for advancement ( ) ( ) ( ) ( ) ( )
   e. the recognition you receive ( ) ( ) ( ) ( ) ( )

6. Which of the following, if any, would most improve your job satisfaction?
   Please select up to TWO.
( ) higher pay
( ) a more manageable workload
( ) better opportunities for career advancement
( ) more supportive management
( ) more flexibility in schedule
( ) more recognition for my work
( ) other (please specify)

7. If you have considered leaving Tech Gnomad, what is the main reason? Please leave blank if this doesn't apply to you.

8. What is one change that we at Tech Gnomad could make that would most improve your experience as an employee?
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: sample survey with a cross-sectional design. Stratified and multi-stage probability sample. Within each stratum, a simple random sample without replacement of records (telephone numbers) was selected. Then one eligible person per selected household was chosen using the 'age-order' selection method.
2. Sample size: 16,149 respondents
3. Target population: All persons aged 15 years or older living in Canada. This is excluding (1) residents of the three territories (Yukon, Northwest Territories, Nunavut), and (2) full-time residents of institutions.
4. Sampling frame: A combination of two different components. (1) Lists of telephone numbers in use (both landline and cellular) available to Statistics Canada from various sources (Telephone companies, Census of population, etc.) and (2) The Address Register (AR): List of all dwellings within the ten provinces. About 86% of telephone numbers were linked to the AR, and the remaining 14% (unlinked) were also kept on the frame to maintain coverage of households with a telephone.
5. Survey mode(s): Online questionnaire or telephone-interviewing. 
6. Timeline: Collection period: September 4 to December 28, 2018. Reference period: the 12 months preceding the interview date.  Frequency: every 5 years.
7. Response rate: 41.9%
8. Weights: The number of persons represented by a given person in the sample. Initial household weight = inverse of the probability of selection. Person weight = household weight x Factor 1 x number of eligible (15+) household members.
9. Data processing: data capture: responses entered directly into the EQ system by respondents. output was encrypted and sent to Ottawa. editing: duplicates were removed. out of scope records were dropped
10. Cleaning, imputation, etc: Three non-response types are defined: complete (records dropped and accounted for through weighting), item (handled via "Not stated" code or imputed), and partial. Imputation used DONOR imputation via a score function: characteristics of each recipient (incomplete) record were compared with all donor records, and the highest-scoring "nearest" donor supplied the missing value (ties broken randomly), constructed so imputed records still pass the edits; where donor imputation was not possible, mean imputation among a donor pool was used
11. Sources of error:     
- Coverage error: households without telephone service, or with service not covered by the frame, were excluded from the surveyed population.
- Measurement (response) error: respondent misunderstanding, recall error, refusal
- Processing error: errors introduced during capture, coding, or editing.
12. Limitations, known biases, etc: Participation was voluntary. Also, there is non-comparability over time: the 2018 move to electronic-questionnaire collection (plus  content revisions) means StatCan states it is NOT appropriate to compare 2018 GSS GVP results with previous iterations.
13. Link to documentation and any additional sources used:
Statistics Canada, 2023, "General Social Survey, Cycle 33, 2018 [Canada]: Giving, Volunteering and Participating", https://doi.org/10.5683/SP3/U1AYY0, Borealis
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
