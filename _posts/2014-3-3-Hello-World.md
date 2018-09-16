---
layout: post
title: Introduction to Hypothesis Testing: Example
---


Every thing we can possibly think about can be accompanied with an observation. The methodology to prove your assumption using statistical techniques, introduces you to the world of Hypothesis Testing. 

For instance, the mean age of a cohort of students studying Data Science in UBC is 27. When a random sample of 35 students was selected, their average age was 25. Try comparing the information given about the population and sample. We can make the following observations.

* 35 students(sample) selected do not belong to the cohort(population) and thus have a different average age
* 35 students(sample) selected do belong to the cohort(population) and it was a case of random chance that this particular sample got selected.

Now we can use the following methods to prove either of these obersations:

* A different sample of the same size could be sampled to represent the population
* The sample size of the current sample could be increased to make it a more relevant representation of the population
* Or we could use statistical techniques to check which of the above observations hold

Now let's solve an example:

A test on awarenes of Data Science was conducted in a University, the average score on the test was 58 with a standard deviation of 15. That got you into thinking that students studying Statistics/Computer Science/Data Science would be __more aware__ about the field of Data Science. So you randomly sample out the scores of 100 such students and their mean score was 65. Is your sample more aware about Data Science? 

- __Step 1:__ Let's first state our null and alternative hypothesis  
    $H_o: \mu = 58$  
    $H_1: \mu > 58$  


- __Step 2:__ Now let's compute the Z statistics for this:  
  Population mean ( $\mu$)=58  
  Population standard deviation ( $\sigma$)=15  
  Sample mean ($x$)=65  
  As stated above, $ z=\frac {x-\mu} {\sigma / \sqrt n} $  
  
  #### $z=\frac {65-58} {15 / \sqrt 100} = 4.66 $
  
  
- __Step 3:__ Since the Level of Significance is not given, let's assume it to be 5% i.e $\alpha = 5\%$
  Now we can either take the p-value as 0.05 or we look in the z-table to find the corresponding z score=1.65
  
  
- __Step 4__: For the ease of understanding, we'll compare both Z-scores and P-values. 
  * The Z-score at 5% Level of Significance is 1.65 and the p-value is 0.05
  * The computed Z-score is 4.66 and the corresponding p-value from the z-table is 0.0007
  
Since $ 0.0007 $<$ 0.05 $ we __reject__ the Null Hypothesis. Also, to look at it from another angle, you can compare the z-scores, since $ 4.66 > 1.65 $, we __reject__ the Null Hypothesis. These both that the population and sample have different behaviours, hence we reject the null hypothesis and accept the alternate hypothesis, that the sample does have a higher awareness of Data Science than the population.

