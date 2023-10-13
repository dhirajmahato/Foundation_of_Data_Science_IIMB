## Week5: Hypotheis Testing

### Introduction
video: https://youtu.be/uSgFKwbA-PQ

Hypothesis testing is used to establish evidence of an association relationship between an outcome variable and predictor variables.

- Hypothesis test consists of two complementary statements called null hypothesis and alternative hypothesis, only one of which can hold true.
- The objective of hypothesis testing is to either reject or retain a null hypothesis.

> Data analysis in general can be classified as **exploratory data analysis** or **confirmatory data analysis**.<br/>
>  In exploratory data analysis, the idea is to look for new or previously unknown hypotheses or suggest hypotheses. In the case of confirmatory data analysis, the objective is to test the validity of a hypothesis (confirm whether a hypothesis is true or not) using techniques such as **hypothesis testing** and **regression.**

### Setting up a hypothesis test: 
https://youtu.be/mA0mJ3Sg2G8

#### Classification
1. Parametric hypothesis testing eg: for population parameters mean, std dev
2. Non-Parametric hypothesis testing  eg: for distribution of data

#### Example of hypothesis:
1. girls take more selfies
2. avg time by women on social media than men
3. morality rate in covid independent of gender

***Initially, we believe null hypothesis is true.***
Null hypothesis i.e no relationship b/w variable under consideration

#### Steps:
1. **Description of Hypothesis** ----> https://youtu.be/0OCz_0xcIoE
2. **Null(H0) and Alternative Hypothesis(Ha)**  ----> https://youtu.be/9NJ2v5kEz0E
3. **Test-Statistic**: ----> https://youtu.be/scT8JvQ9r1E
  - It is the standardized difference between the null hypothesis & the observed value, 
  - enables us to calculate (p-value) evidence against null hypothesis, 
  - depends on the probability dist of the sampling distribution.
4. **Decision Criteria – Significance Value, α** ---> https://youtu.be/x2-RiAzmXho
5. **p-value**: which is the conditional probability of observing a **test statistic** value as extreme as the one observed in the sample, given the null hypothesis is true.

|criteria |                  |
|-----------|------------------|
|p-value< α | Reject the null hypothesis |
|p-value>= α | Retain the null hypothesis |


#### One-tailed test and a Two-tailed test 
video: https://youtu.be/YtFO2K4WaFg

A one-tailed test and a two-tailed test are alternative ways of computing the statistical significance of a parameter inferred from a data set, in terms of a **test statistic.**

- A two-tailed test is appropriate if the estimated value is greater or less than a certain range of values, this method is used for null hypothesis testing and if the estimated value exists in the critical areas, the alternative hypothesis is accepted over the null hypothesis.
- A one-tailed test is appropriate if the estimated value may depart from the reference value in only one direction, left or right, but not both.

**statement 1**:  Salary of ML experts on avg at least <= $100K

- H0: µm <= 100,000  ; equality in null hypothesis ,
- Ha: µm >  100,000  ; sign decide which side is rejection side having area α in alternate hypothesis, **right-tailed Test**
  
**statement 2**:  The average waiting time at the Heathrow airport security check is less than 30 minutes

- H0: µm >=30
- Ha: µm < 30  ;  **left-tailed Test**

**statement 3**: The avg salary of men and women grad is different

- H0: µm = µf
- Ha: µm != µm ; rejection region on both side with area α/2 each; **two-tailed Test**

![image](https://github.com/dhirajmahato/Foundation_of_Data_Science_IIMB/assets/33785298/1063ff1a-5a7f-4e30-be71-0468d9296cf9)
