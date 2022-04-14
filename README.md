# maximum_likelihood_estimation_chongjun_yuchen
An educational app based on BOAST Maximum Likelihood Estimation by Chongjun and Yuchen. This is a redesign of an existing app. The orginal app contains an educational game. We think the game is good so we keep it unchanged. 
The source code is from Maximum Likelihood Estimation in BOAST ch5.
# What did we update
## 1. prerequisites
We added explanation of what is the likelihood function before explaining what is the MLE.  
We added explanation in the simple MLE procedure.  
We explain why the Invariance property and Large Sample Property are necessary in the usage of MLE.
## 2. Explore (plots)
We added the mathematical expressions of optimization of log-likelihood functions for samples from Poisson distribution and exponential distribution.  
We suggest the users to choose a large sample size so the Large Sample Property would apply.  
We removed the two parameters log-likelihood plot since it is a little bit confusing.                                                                      
We have thought about other ways that can better visualize a 3-dimensional plot. The orginal app utilizes a colormap to display the gamma distribution. We agree that colormap is an commonly used way for sure. And we think the visualization panel can be improved by adding graphs of vertical slices through the log-likelihood function surface through the MLE (2-dimensional graph showing the relationship between log-likelihood and alpha/beta). But we are still trying to figure out how to realize this idea in the Shiny app. 
We also have throught about adding other modes of distribution, such as binomial distribution. Binomial distribution has two parameters as well, so that it could be included under the tab of "two-parameter". But we hesitated to do so because we were concerned that it might make the exploration part even more complex and confused.
