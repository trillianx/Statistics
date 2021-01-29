# Bayesian A/B Testing

A/B testing is used everywhere: marketing, retail, newsfeed algorithms, online advertising, etc... At the heart of A/B testing is about comparing things such as Logo A versus Logo B. It is about answering the question: Can we say convincingly that one is better than the other? A/B testing allows us to quantify an answer to this question in terms of metrics, scores, and numbers. 

## The High Level Picture

There are many examples of A/B Testing that exist in our day-today lives. The one place where A/B Testing is used quite a lot is in the pharmaceutical trials. For example, a company has developed a new drug and they want to find out if it works or not. For example, suppose that the drug is for reducing blood pressure. We want to test how good this drug is. 

To test this, we design an experiment. The experiment will have two groups, the **control group** who are given a placebo and the **treatment group** who are given the actual drug. You will then execute the experiment and measure their blood pressure before and after taking the drug. Now there are a lot of variabilities that exist in the experiment. We want to reduce these variabilities and find the difference that is a definitive proof of the effect of the drug. 

Another example is that of a website. You have a website and you hire a website designer to make a new look for your website. She makes multiple version of the website. Now, you want to compare different options such that the website can bring in more customers to your website. A/B testing is where you can get the answer to your question. 

In these two examples we see a pattern. 

* There are about comparing two or more items
* Each group of items produce numbers
* We want to create a metric with which we can measure the scores each group gets. We would then compare, using statistics, which group is higher and lower 

## Bayesian Machine Learning

The Bayesian approach is the following: Everything is random. Each random event is associated with a random variable. Let’s take an example to understand Bayesian approach versus the Frequentist approach. 

Suppose we have a class of students and we want to model the height of the student as a Gaussian. Therefore, we must find the mean and variance of the height of students. The frequentist approach this problem by measuring the height of each of the students. Then they create a likelihood function to measure the probability of each of student’s heights given the value of mean and standard deviation. They do this for various values of mean the standard deviation. Using the maximum likelihood estimation, they determine the values of the coefficients that gives the largest likelihood. In the Bayesian approach, we do not solve for the mean the variance but treat them as random variables. We then find the probability distributions of these random variable given the dataset at hand. In other words, rather than finding a number for the coefficients as we do in the frequentist approach, we find a distribution in the Bayesian approach.

>  In the Bayesian approach, the parameters are not numbers but distributions. 



