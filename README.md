# Probabilistic programming training 

## Introduction

> The aim of this repository was to use Pyro and Bayesian approach to model simple  real life situations. 5 different tasks were solved

## Tasks

> 1. Generate random variable from prefered dystribution using Pyro (pyro.sample)
    - animate how distribution of values changes
    - animate histograms of values
    - start with empty list of values, generate new samples, generate histogram

> 2. Write a simulator (and exact solution utilizing Bayes theorem) for chances to be ill on a certain disease. We know that it affects from about 1 to 100 out of 50,000 people. There was developed a test to check whether the person has the disease and it is quite accurate: the probability that the test result is positive (suggesting the person has the disease), given that the person does not have the disease, is only 2 percent; the probability that the test result is negative (suggesting the person does not have the disease), given that the person has the disease, is only 1 percent. When a random person gets tested for the disease and the result comes back positive, what is the probability that the person has the disease? Check whole parameter space and visualise results.
    - it must be a simulator!
    - sample from distribution using given probabilities
    - repeate experiment and compare with Bayes equation

> 3. Visualize (pmf, mean, variance) of pseudo random number generators (parametrized) that follows distributions:
   - Single gaussian 
   - Two combined gaussian distributions 
   - N combined gaussian distributions 
> 4. Student applied for 9 faculties, acceptance chance for each faculty was 0.01. Unfortunately student was not accepted to any. What is the probability of that situation? Write a function that will solve that problem (parametrized), use exact method and binomials based solution with parameterized number of trials (binomial)

>5. Create simple pyro model, that models salary distribution in population of Poland. A priori parameters derived from 2016 cenus carried out by GUS (Central Statistical Office in Poland)
Requirements:
 - two distributions
 - one of distribution can result in more than 2 results (not Bernoulli)