# StatsWithRLabs: Selected Labs used in Duke Coursera Stats with R specialization
## ToDo:  
* rep_sample_n function from Course 2 Lab 1 comes with the statsr package created by the MOOC development team. Write your own version of the function that takes M random samples of size n from population pop...signature must be rep_sample_n(pop,M,n). It must return a data frame with the same columns as the population


## Features used and topics covered  in labs:
* Course2Lab1 covers dplyr::sample_n function and rep_sample_n function in Course's statsr package. Also uses <strong><em>shiny</em></strong> package. Contains example of <strong><em>shinyApp(...)</em></strong> function call.

* Course2Lab2 covers:
    * how to generate confidence intervals in R
    * how to restructure a data frame to plot n confidence intervals- one for each of n samples drawn from the population
    * how to plot n confidence intervals, coloring each interval by whether or not it captures the population parameter; also superimposes plot of vertical line for population parameter.
    * how to use existing confidence intervals (e.g. uses 95% CIs) created for each of n samples drawn from a population to construct confidence intervals for each of these samples at a <em>new confidence level (e.g. uses 99%)</em> <strong>without resampling from the population</strong> 