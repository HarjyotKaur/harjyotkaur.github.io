---
layout: post
title: Introduction to Hypothesis Testing
---


Every thing we can possibly think about can be accompanied with an observation. The methodology to prove your assumption using statistical techniques, introduces you to the world of Hypothesis Testing. 

For instance, the mean age of a cohort of students studying Data Science in UBC is 27. When a random sample of 35 students was selected, their average age was 25. Try comparing the information given about the population and sample. We can make the following observations.

![](imgs/sampling.jpg)
Image Source <a href="https://nces.ed.gov/blogs/nces/post/statistical-concepts-in-brief-how-and-why-does-nces-use-sample-surveys">nces.ed.gov</a>


* 35 students(sample) selected do not belong to the cohort(population) and thus have a different average age
* 35 students(sample) selected do belong to the cohort(population) and it was a case of random chance that this particular sample got selected.

Now we can use the following methods to prove either of these obersations:

* A different sample of the same size could be sampled to represent the population
* The sample size of the current sample could be increased to make it a more relevant representation of the population
* Or we could use statistical techniques to check which of the above observations hold

The first two would require a lot of mannual effort and resources, thus we decide to go with third option. Before, we delve further into formulas, let's go through some basic statistical concepts!

