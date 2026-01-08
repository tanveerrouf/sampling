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

The number of your chosen topic: '1'

Describe the purpose of your survey:
```
Chosen Scenario: 1 - Employee Turnover
Purpose of Survey: I aim to identify the primary factors driving high turnover among entry and lower-level positions at the tech company. I seek to understand employee satisfaction across compensation, career development, management practices, and workplace culture. These insights will directly inform retention strategies and prevent additional staff departures.

```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target Population: All current and recently departed (past 12 months) entry and lower-level employees (salary grades 1-4)
Sampling Frame: Company HR database listing all employees in these grades, plus exit interview records
Sampling Units: Individual employees
Strategy: I will use stratified random sampling by department to ensure representation across all departments experiencing turnover. I will create separate strata for current versus recently departed employees. This approach captures why people leave while understanding what keeps current employees engaged.
```

Your 5-10 question survey:
```
1. Rate your satisfaction with your compensation relative to your responsibilities. (Very Dissatisfied / Dissatisfied / Neutral / Satisfied / Very Satisfied)


2. Do you see clear opportunities for career advancement within the company? (Yes / Somewhat / No)


3. Rate your direct manager's support for your professional development. (Excellent / Good / Fair / Poor)


3. Which factor most influenced your decision to leave or consider leaving? (Limited growth / Low pay / Poor management / Work-life balance / Lack of recognition / Other:)


4. On a scale of 1-10, how valued do you feel by your team and leadership?


5. What single change would most improve your work experience? (Open-ended)


6. How often do you receive meaningful performance feedback? (Weekly / Monthly / Quarterly / Rarely / Never)


7. The company culture emphasizes collaboration and inclusion. Do you agree? (Strongly Agree / Agree / Neutral / Disagree / Strongly Disagree)

```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
General Social Survey - Giving, Volunteering and Participating (2018, Cycle 33)

Sample Type: Cross-sectional sample survey with stratified probability sampling design using "rejective sampling" methodology.

Sample Size: Approximately 50,000 field sample units, with about 40,000 invitation letters sent and 24,000 questionnaires expected to be completed.

Target Population: All persons aged 15 and older living in Canada's ten provinces, excluding full-time institutional residents (those residing more than six months in institutions).

Sampling Frame: Combined frame using landline and cellular telephone numbers from the Census and administrative sources, linked with Statistics Canada's dwelling frame. Records group telephone numbers by address, improving household telephone coverage.

Survey Mode(s): Electronic questionnaire or CATI (computer-assisted telephone interviewing). Respondents could choose French or English. Average completion time: 44 minutes. No proxy responses permitted.

Timeline: Collection period: September 4, 2018 to December 28, 2018. Data release: January 26, 2021.

Response Rate: Overall response rate: 41.9%

Weights$WGHT_PER$: Basic weighting factor for person-level analysis calculating estimates of non-institutionalized persons aged 15+ with specified characteristics. Bootstrap weights created for design-based variance estimation. Weights adjusted for rejective sampling and calibrated to match 2017 Canadian 
Income Survey distribution by province.

Data Processing: Used Social Survey Processing Environment (SSPE)—generalized processing steps monitoring data quality through structured environment ensuring best practices.

Cleaning & Imputation: Automated and manual edits at macro and micro levels including family, consistency, and flow edits. Donor imputation used primarily: recipient records (with missing data) matched to donor records by shared characteristics; highest-scoring donor filled missing values. Where donor imputation unavailable, mean imputation was used. Personal income obtained via linkage to 2017 T1FF tax records (81.9% of respondents); missing data imputed. Family income obtained through T1FF linkage (81.7% of households); remaining imputed.

Sources of Error: Sampling error and non-sampling errors including imperfect coverage and non-response.
Limitations & Known Biases: Coverage error: Households without telephones excluded from surveyed population; biases expected to be small given small exclusion rates. Non-response bias: Mitigated through weight adjustments using non-responding household characteristics extracted from administrative sources. Response errors and processing errors may occur.

Documentation & Additional Sources: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234

```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 14 January 2026`
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
