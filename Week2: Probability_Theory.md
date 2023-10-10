## Week2: Probability Theory and Applications
*"It is essential to understand probability theory that can be used to predict and measure uncertain events"*

Video 1: https://youtu.be/-6bEInSZux8 <br/>
Video 2: https://youtu.be/CKqLWHObc_U

> Many important tasks in analytics deal with uncertain events.
> Association Rule Mining in market basket analysis and recommender systems

### Terminology
- **Random Experiment** is an experiment in which the outcome is not known with certainty prior to the occurrence of the event. That is, the output of a random experiment cannot be predicted with certainty.
- **Sample space** is the universal set consisting of all the possible outcomes of an experiment.
- **Event(E)** is a subset of the sample space.
- **Probability Estimation using Relative Frequency**: P(X) = Number of observations in favour of event X / Total number of observations
- **Algebra of Events**:  Assume that X, Y and Z are three events  --
  - ![image](https://github.com/dhirajmahato/Foundation_of_Data_Science_IIMB/assets/33785298/2bd96917-f2bb-4fd3-be6a-75a4fef23480)
  
### Fundamental Concept of Probability

#### Axioms of Probability
video: https://youtu.be/EWQ094BTaHM<br/>
Axioms:
1. The probability of event E always lies between 0 and 1. That is, 0 ≤ P(E) ≤   1.
2. The probability of the universal set or sample space, S, is 1. That is, P(S) = 1.
3. P(X ∩ Y) = P(X) + P(Y), where X and Y are two mutually exclusive events.

Following Elementary Rules:
1. P(A') = 1 – P(A)
2. P(∅) = 0 
3. P(A) ≤ P(B), where event class A is a subset of event class B
4. P(A ∪ B) = P(A) + P(B) - P(A ∩ B), either event A or event B occurs or that both occur simultaneously
5. P(A ∪ B) = P(A) + P(B), A and B are mutually exclusive events,

#### 1. Marginal Probability

Marginal probability is simply the probability of an event X, denoted by P(X), without any prior conditions. unconditional probability which is known as Marginal Probability.

#### 2. Joint Probability
Let A and B be two events in a sample space. Joint probability of the two events, written as P (A∩B)

### Association Rule Learning
video1: https://youtu.be/bJ903GwyeKs <br/>
video2: https://youtu.be/YM1BtNlUgY4

A method of finding associations between different entities in a database.

> Simple probability concepts such as joint probability and conditional probability can be used for solving analytics problems such as **market basket analysis (MBA)** and **recommender systems** using algorithms such as Association Rule Learning (aka Association Rule Mining).<br/>
> One can create a recommender system using simple association rule mining. Recommender systems are an important analytics technique that can be
used to significantly improve the revenues of an organization.<br/>
> The primary objective of MBA and recommender systems is to find the probability of buying two products (A and B) together.

- In a retail context, association rule learning is a method to find association relationships that exist between frequently purchased items.  
- Association rules can be created using point of sale (PoS) data from retail stores.
- The strength of association between two mutually exclusive subsets of SKUs(Stock Keeping Units) can be measured using **‘support’, ‘confidence’, and ‘lift’**.
  - Support = 𝑃(𝑋 ∩ 𝑌)
  - Confidence = P(Y | X )
  - Lift = 𝑃(𝑋 ∩ 𝑌) / 𝑃(𝑋) ∗ 𝑃(𝑌)
    - A necessary condition for association (complementarity) between two set of entities is that the Lift should be greater than 1.
    - If the Lift is 1, then the product purchases are independent
    - If the Lift is less than 1 then the products are substitutable. 

### Bayes Theorem
video1: https://youtu.be/qufrBR-LTEM

**Naïve Bayes algorithm** is one of the more popular algorithms used in classification problems such as text classification and sentiment analysis.

Objective:
- **Bayes’ theorem** helps data scientists update the probability of an event when any additional information is provided.
- **Bayesian statistics** helps decision makers with fine-tuning their beliefs with each additional data received.
- *Prior-probability* and *Posterior probability*.

#### Bayes' Theorem
P(B|A) = P(A|B) ∗ P(B) / P(A)

where  P(B) is Prior-probability ;  P(B|A) is Posterior probability ;  P(A|B) - likelihood of event A when event is B is true.

> Monty Hall Problem

#### Generalization of Bayes's Theorem
P(A) = P(A,B1) + P(A,B2) + P(A,B3) .....<br/>
P(A) = P(A|B1)∗P(B1) + P(A|B2)∗P(B2) +P(A|B3)∗P(B3) .....

Example: https://youtu.be/h9w6rmybrds

#### Random Variables
video1 : https://youtu.be/NDXW52R18aI
video2 (Discrete / Continuous): https://youtu.be/ByyhevguW30

  
Outcome of a random experiment may be recorded in different format. Outcomes of experiments may be recorded in numerical or nonnumerical terms.
For every random experiment, we can define a function that maps the outcome of the sample space to a real number.

- A random variable is defined as a function that assigns a real number to each sample point in the sample space S.
- Use of random variables provides us the flexibility required in probabilistic modelling.
- Random variables are usually denoted using capital letters, such as X, Y, and Z, whereas small letters, such as x, y, z, a, b, c, and so on, are used to denote precise value of a random variable.

example: The sample space discussed earlier S = {GGGG, GGGF, GGFG, …} will be mapped to a real number set S = {0, 1, 2, 3, 4}, which is often the interest of the analyst.

![image](https://github.com/dhirajmahato/Foundation_of_Data_Science_IIMB/assets/33785298/b2c97ce7-0050-4b2f-8bd7-8758bb6fc567)
