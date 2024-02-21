# Introduction to Particle Filters: Estimation of Stochastic Volatility Models

## Summary

This project serves as a teaching material and it aims to fulfill three purposes simultaneously. First, it introduces the reader to Sequential Monte Carlo (SMC) Methods, also known as Particle filters. These are advanced methods used in various fields such as robotics, signal processing, financial econometrics, etc. Similar to the Monte Carlo Markov Chains (MCMC) method, SMC methods are used to approximate stationary distributions, but they are designed in a way to efficiently approximate distributions inherent in financial models sequentially. Second, I delve into the world of volatility models to (i) illustrate how/when/why these particle filters can be used and (ii) convince that stochastic volatility models are amazing.  Finally, I show how to estimate the model parameters which will give us the filtered latent variables (in this case, the log-volatility). 
     
The efficacy of the algorithms derived in the text is first tested by applying them to a simulated model, and then they are applied to real financial data. I provide a step-by-step guide to the algorithms by blending theoretical depth and practical application, introducing very fundamental concepts first and then gradually building on them and advancing to advanced methods. Additionally, a detailed explanation of the codes is provided. I use parallel computing to accelerate the code execution when approximating the likelihood function via simulation. 

**Keywords:** Particle Filter, Sequential Monte Carlo Methods, Simulated Maximum Likelihood Estimation, Stochastic Volatility Models

**Prerequisites:**
* Probability and Statistics (It would be helpful to be familiar with some sampling methods such as MCMC method)
* Non-linear Optimization
