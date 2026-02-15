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

The number of your chosen topic: `#1`

Describe the purpose of your survey:
```
The purpose of this survey is to identify the main reasons entry- and lower-level employees are leaving the company and the factors most affecting their job satisfaction. Results will be used to prioritize changes to many ereas of the company like policies, management practices, workload expectations, growth opportunities, and workplace supports that could reduce turnover and improve retention.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
- Target population: All current entry- and lower-level employees at the company.
- Sampling units: Individual employees (each eligible employee is one sampling unit).
- Overall sampling strategy: Stratified random sampling to ensure representation across key groups likely tied to turnover—department/function, location, and tenure band (e.g., <6 months, 6–12 months, 1–3 years). for this senario, we will do by Departments (e.g., Engineering, Support, Sales, Marketing, HR, IT, etc.).Randomly sample within each stratum.
```

Your 5-10 question survey:
```
1. Overall, how satisfied are you with your job? (1 = Very dissatisfied, 5 = Very satisfied)
2. How likely are you to leave the company in the next 6 months? (1 = Very unlikely, 5 = Very likely)
3. My day-to-day responsibilities are clear. (1 = Strongly disagree, 5 = Strongly agree)
4. My workload is manageable. (1 = Strongly disagree, 5 = Strongly agree)
5. I receive helpful support and feedback from my manager. (1 = Strongly disagree, 5 = Strongly agree)
6. I see a realistic path for growth or promotion here. (1 = Strongly disagree, 5 = Strongly agree)
7. My pay and benefits feel fair for my role and responsibilities. (1 = Strongly disagree, 5 = Strongly agree)
8. I feel respected and included on my team. (1 = Strongly disagree, 5 = Strongly agree)
9. What are the top 2 reasons you would consider leaving? (Select up to 2)
☐ Pay/benefits ☐ Workload ☐ Manager relationship ☐ Lack of growth ☐ Team culture ☐ Stress/burnout ☐ Role mismatch ☐ Scheduling/remote policy ☐ Other: ____
10. What is one change the company could make that would most improve your experience? (Short answer)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type:
A stratified probability sample with a two-stage design: (1) sampled units are groups of telephone numbers linked to addresses; (2) one eligible person (15+) is randomly selected within the household. It also used “rejective sampling” (a form of sub-sampling) where all volunteers complete the long interview, while non-volunteers are randomly split into long vs short interview groups.

2. Sample size: 

Field sample: approximately 50,000 units (with ~40,000 invitation letters to the electronic questionnaire sent); Achieved analytic sample (reported in a StatCan analysis article using the 2018 GSS-GVP): 16,149 respondents.

3. arget population:

All persons 15 years and older living in the 10 provinces, excluding full-time residents of institutions.

4. Sampling frame:

A frame combining landline + cellular telephone numbers drawn from the Census and administrative sources, linked with Statistics Canada’s dwelling frame; frame records are telephone-number groups associated with an address (or a single number if not linkable).

5. Survey mode(s)

Data were collected either by:
- Electronic questionnaire (online / EQ), or
- CATI (computer-assisted telephone interviewing)

6. Timeline

Reference period: past 12 months preceding the interview date
Collection window (Cycle 33, 2018): September 4, 2018 to December 28, 2018
The survey is conducted every 5 years (Sept–Dec) per the program description.

7. Response rate

Overall response rate: 41.9%.

8. Weights

Main person weight: WGHT_PER (for person-level estimates).
Bootstrap weights are provided for design-based variance estimation.

Weight adjustments include:
- adjustment for the rejective sampling/sub-sampling of non-volunteers,
- calibration to independent age-sex-by-province controls,an adjustment so the weighted income distribution matches the 2017 CIS distribution by province.

9. Data processing

Processing used Statistics Canada’s SSPE generalized processing steps, with a structured environment to monitor processing and follow harmonized business processes.

10. Cleaning, imputation, etc.

Edits: automated and manual edits at macro/micro levels, including family/relationship checks, consistency checks, and flow edits; CATI included built-in range/flow edits during the interview.

Imputation: mostly donor (nearest-neighbour/score) imputation, with mean imputation used where donor imputation wasn’t possible.

Income: in 2018, personal income questions were not asked; income was obtained via linkage to tax data for respondents who did not object, and remaining missing income was imputed.

11. Sources of error

Statistics Canada explicitly notes both:

- Sampling error (variance estimation supported via bootstrap), and
- Non-sampling error, including coverage error (e.g., households without telephones or not covered by the frame), non-response, response error, and processing error.

12. Limitations / known biases

- Coverage limitations because the surveyed population excludes households without telephones (and any not covered by the telephone frame), which can introduce bias if excluded households differ systematically.

- Non-response bias risk (mitigated by weight adjustments, including modelling using admin characteristics of non-responding households).

- Comparability concerns vs earlier cycles, because 2018 introduced an Internet option and other content/mode-related changes (StatCan flags comparability issues in its “main changes” documentation).

13. Links to documentation / sources used

https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
https://www150.statcan.gc.ca/n1/en/catalogue/45250011
https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getMainChange&Id=143876&utm_source=chatgpt.com
https://www150.statcan.gc.ca/n1/pub/75-006-x/2021001/article/00002-eng.htm?utm_source=chatgpt.com

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
