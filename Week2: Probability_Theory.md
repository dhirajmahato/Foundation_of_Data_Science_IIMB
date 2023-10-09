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
video1: https://youtu.be/bJ903GwyeKs
video2: https://youtu.be/YM1BtNlUgY4
A method of finding associations between different entities in a database.

> Simple probability concepts such as joint probability and conditional probability can be used for solving analytics problems such as **market basket analysis (MBA)** and **recommender systems** using algorithms such as Association Rule Learning (aka Association Rule Mining).<br/>
> One can create a recommender system using simple association rule mining. Recommender systems are an important analytics technique that can be
used to significantly improve the revenues of an organization.<br/>
> The primary objective of MBA and recommender systems is to find the probability of buying two products (A and B) together.

- In a retail context, association rule learning is a method to find association relationships that exist between frequently purchased items.  
- Association rules can be created using point of sale (PoS) data from retail stores.
- The strength of association between two mutually exclusive subsets of SKUs(Stock Keeping Units) can be measured using **‘support’, ‘confidence’, and ‘lift’**.
  - Support = P( X ∩ Y )
  - Confidence = P(Y | X ) 

