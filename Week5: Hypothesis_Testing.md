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
5. **p-value**: which is the conditional probability of observing a test statistic value as extreme as the one observed in the sample, given the null hypothesis is true.
    - It quantifies the likelihood of observing the data or more extreme data if the null hypothesis a were true.
    - A p-value is a probability that measures the strength of evidence against the null hypothesis (H0) in a hypothesis test.
    - The p-value ranges between 0 and 1, where a smaller p-value indicates stronger evidence against the null hypothesis

**Example**: In a hypothesis test, if the p-value is less than a pre-defined significance level (e.g., 0.05), it is considered statistically significant, and you reject the null hypothesis (H0) in favor of the alternative hypothesis (Ha).

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

#### Type I Error, Type II Error, and Power of the Hypothesis Test

video: https://youtu.be/3OO63srgchM

**Type I Error/False Positive:** It is the probability of falsely claiming an effect or difference.  
- The conditional probability of rejecting the null hypothesis when it is true.
- The significance value α is the maximum value of Type I error
- Type I error = α = P(Rejecting null hypothesis | H0 is true)

**Type II Error/ False Negative:**  It is the probability of missing a true effect or difference.
- The conditional probability of failing to reject(retain) a null hypothesis is true is called Type II Error.
- Usually denoted by β
- Type II error = β = P(retain null hypothesis | H0 is false)

**Example**: In a clinical trial, a Type I error would mean falsely concluding that the drug is
effective when it actually has no effect. A Type II error would mean failing to identify the
drug's effectiveness when it does have an effect.


**Power of the test:(1-β)**

#### Hypothesis Testing for Population Mean with known Variance: Z-Test
video : https://youtu.be/T3ujcnOAB-w

Z-test (also known as one-sample Z-test) is used when a claim (hypothesis) is made about the population parameter such as population mean or proportion. 
- Z-test uses CLT to conduct a hypothesis test for population mean when the population variance is known.
- The test statistics here called Z statistics
  - The *critical value* in this case will depend on the significance value **α** and whether it is a **one-tailed or two-tailed test.**
 
**one-sample Z-test** used when:
1. 
