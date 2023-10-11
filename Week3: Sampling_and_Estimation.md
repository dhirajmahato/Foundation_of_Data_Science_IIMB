## Week3: Sampling and Estimatiion

### Sampling

Video: https://youtu.be/VK7Xmeyky2g

Sampling is the process of selecting a subset of observations from a population to make an inference about various population parameters such as mean, proportion, standard deviation etc.

- It is an important step in **inferential statistics**.<br/>
- Sampling is necessary when it is difficult or expensive to collect data on the entire population. <br/>
- Sampling is necessary because even when the entire population is available, using the entire population for estimation of a population parameter may not be feasible.

The process of identifying a subset from a population of elements (aka records or observations or cases) is called **sampling process or simply sampling.**

video: https://youtu.be/CUE1AZ-MTWs

The following steps are used in any sampling process: for attrition among young professionals
1. **Identification of target population:**  --> attrition among IT professionals in the age group 25–35 years.
2. **Decide the sampling frame:** Sampling frame defines the source (or method/procedure) used for -->  use data captured by many human resource departments across multiple companies.
3. **Determine the sample size:** determined using factors such as effect size, standard deviation, desired level of confidence, and margin of error.
   > For multivariate models such as multiple linear regression, logistic regression, and factor analysis, a thumb rule such as a sample 20 or 30 times the number of
   > independent variables are used. That is, if there are 10 variables, then a sample size of 200 in most cases would be acceptable.
4. **Sampling method:** for selecting individual cases in the sample
   - two major categories: *probabilistic sampling* and *non-probabilistic sampling*.
   - Probabilistic sampling is further classified into random sampling, stratified sampling, etc
   - Bootstrap aggregating (also known as Bagging) and Boosting are two popular sampling methods used in machine learning algorithms.
    
#### Population Parameter and Sample Statistics
video: https://youtu.be/PHpXE8hXvTU

scale, shape, and location of parameters

### Estimation of Parameters using Method of Moments
![image](https://github.com/dhirajmahato/Foundation_of_Data_Science_IIMB/assets/33785298/c1f6e4d0-5f48-4176-a328-5dcaef8904e9)

### Probabilistic Sampling
In Probabilistic sampling, individual observations in the sample are selected from the population according to a probability distribution. 

- Random sampling is one of the most popular and frequently used sampling methods. 
- Random sampling is ideal when the population is homogeneous.
- Stratified sampling is necessary when the population is heterogeneous.
- In a stratified sample, all strata will be represented in the sample, whereas in a cluster sampling, not all clusters will be represented.
- Bagging is sampling with replacement used in machine learning algorithms, especially in the random forest algorithm.

video1: https://youtu.be/lGG89Ec3jq0
video2: https://youtu.be/ltIBMP-6yNs

### Non-Probabilistic Sampling
In Non-probability sampling, the selection of sample units from the population does not follow any probability distribution. Sample units are selected based on convenience and/or on voluntary basis.

- Estimation based on non probability sampling may be biased.
- Convenience sampling and Voluntary sampling are non-probability sampling techniques in which the sample units are not selected according to a probability distribution.

### Sampling Distribution
Sampling distribution refers to the probability distribution of a statistic such as *sample mean* or *sample standard deviation*, computed from several random samples of the same size.

- Understanding the sampling distribution is important for hypothesis testing.  
- In hypothesis testing, the test statistic is derived based on the knowledge of sampling distribution.   

### Central Limit Theorem (CLT)

Video1: https://youtu.be/-lnasuJ4GKY <br/>
Video2: https://youtu.be/1bGMWcRShzw

For a large sample drawn from a population with mean (µ) and standard deviation (σ), the distribution of the sample mean  with mean (X̄) and standard deviation (σ/√n) will approach a normal distribution regardless of the initial distribution of the population.

### Sample Size Estimation   
