README: Data Analysis with AI - Week 1 Submission
Link to Github: 

Research Question

How does life satisfaction (Q49) relate to income inequality perceptions (Q106) and trust in government institutions (Q71) across different countries?


Objective

This project aims to analyze the relationship between life satisfaction, trust in government, and financial perceptions across various countries using data from the World Values Survey (WVS) Wave 7 (2017-2022). The analysis will focus on identifying patterns and correlations between these factors.


Dataset Information

Total Variables: 168

Total Observations: 97,220

Filtered Dataset Variables: 11

Filtered Dataset Observations: 97,220

Source: World Values Survey (WVS) Wave 7 (2017-2022)

File Name: WVS_subset.csv

Location: Provided by the instructor, assumed local directory.


Variables Description: This dataset contains global survey responses on social, economic, and political values. The key variables selected relate to life satisfaction, trust in government, financial perception, and institutional confidence.

Selected Variables

1. B_COUNTRY – Country identifier

Represents the country where the survey was conducted. Encoded using ISO country codes.

2. A_YEAR – Year of the survey

Indicates the year when the respondent was surveyed.

3. Q49 – Life Satisfaction (Scale: 1-10)

Measures the respondent's overall satisfaction with life. (1 = Completely dissatisfied, 10 = Completely satisfied.)

4. Q71 – Trust in Government (Scale: 1-4)

Assesses the level of confidence in the national government. (1 = A great deal, 2 = Quite a lot, 3 = Not very much, 4 = None at all.)

5. Q50 – Satisfaction with Financial Situation (Scale: 1-10)

Evaluates how satisfied the respondent is with their household's financial situation. (1 = Completely dissatisfied, 10 = Completely satisfied.)

6. Q57 – General Trust in People (Scale: 1-2)

Measures the respondent's perception of trustworthiness in people. (1 = Most people can be trusted, 2 = Need to be very careful.)

7. Q70 – Confidence in the Justice System (Scale: 1-4)

Captures the respondent's confidence in the justice system and courts. (1 = A great deal, 2 = Quite a lot, 3 = Not very much, 4 = None at all.)

8. Q73 – Confidence in Parliament (Scale: 1-4)

Measures the level of confidence in the national parliament. (1 = A great deal, 2 = Quite a lot, 3 = Not very much, 4 = None at all.)

9. Q75 – Confidence in Universities (Scale: 1-4)

Assesses the trust in higher education institutions. (1 = A great deal, 2 = Quite a lot, 3 = Not very much, 4 = None at all.)

10. Q78 – Confidence in Banks (Scale: 1-4)

Evaluates how much respondents trust financial institutions. (1 = A great deal, 2 = Quite a lot, 3 = Not very much, 4 = None at all.)

11. Q56 – Standard of Living Compared to Parents (Scale: 1-3)

Compares the respondent’s standard of living to their parents at the same age. (1 = Better off, 2 = About the same, 3 = Worse off.)


For our analysis of life satisfaction (Q49), the five most valuable predictors are: satisfaction with financial situation (Q50), trust in government (Q71), general trust in people (Q57), confidence in the justice system (Q70), and standard of living compared to parents (Q56).

Satisfaction with financial situation is the strongest predictor, as financial well-being directly impacts overall life satisfaction. Trust in government may influence life satisfaction by shaping perceptions of stability and fairness in society. General trust in people reflects social capital, which is linked to well-being and a sense of security. Confidence in the justice system is crucial, as belief in a fair legal system can contribute to a sense of societal stability. Finally, standard of living compared to parents captures perceived economic mobility, which affects expectations and life contentment. These factors together provide a broad understanding of what influences life satisfaction across different countries.

Above was the detailed description of the selected variables, including what they measure and their units of analysis.


Descriptive Statistics for Key Variables

Variable                     | Mean  | Std Dev | Min  | Q1  | Median | Q3  | Max

Q49 (Life Satisfaction)      | 7.01  | 2.34    | -5   | 6   | 7      | 9   | 10

Q71 (Trust in Government)    | 2.46  | 1.35    | -5   | 2   | 3      | 3   | 4

Q50 (Satisfaction with       |       |         |      |     |        |     |
 Financial Situation)        | 6.16  | 2.51    | -5   |5    | 6      | 8   | 10

Q57 (General Trust in People)| 1.70  | 0.65    | -5   | 1   | 2      | 2   | 2

Q70 (Confidence in Justice   |
System)                      | 2.25  | 1.31    | -5   | 2   | 2      | 3   | 4

Q56 (Standard of Living      |       |         |      |     |        |     |
Compared to Parents)         | 1.80  | 0.75    | -5   | 1   | 2      | 2   | 3



