# Adding control and treatment groups matching on households to observe potential differences

## Abstract
In the paper, they used a minimum distance algorithm between census blocks and used as features the proportion of blocks with different characteristics. We would like to make an additional matching on the household level in order to  further confirm the conclusions of the authors, or to nuance them.

First we would like to re-use the same features as in the paper, but at the household level. Second, we want to test different distance functions. In the paper, they used the L-infinite (Chebyshev) distance; We want to see how different the matching may be with different metrics like for example the L1 (taxicab) or L2 (euclidean) distance.

Third we want to try out some matching with different features, like the average number of people per household.


## Research questions
1. Would the paper's results have changed if they had added matching on the households ?
2. How do the different distance functions impact the results ?
3. How do the choice of matching features impact the results ?


## Proposed dataset
We will use the same datasets as in the paper as they already include everything we need.

## Methods
There are five steps that will have to be done:
1. Make the already done replication modular
2. Replicate in a modular way another section of the paper/table, our choice is now directed towards "Estimated Program Impact on Child Health"/Table 5
3. Implement different matching algorithms/strategies on households
4. regenerate tables with 1. and 2. using the matchings of step 3.
5. Analyse the results 

## Proposed timeline
05.12.20 Replication is modular, and replication of second Table is done (Step 1-2)

12.12.20: The matching algorithms are done (Step 3-4)

18.12.2 0: Finish analysis of the results (Step 5) and start working on the video (P5)

## Organisation within the team
During the first week, A will modify the replication done in p2 to make it more modular. During this time, B and C will work on doing the replication of the second table.

In week 2, A will implement the usage of different distance functions while B will create the different feature sets for the matching. C will assemble the two with the already done modular replications of the tables to regenerate them with the new matched sets.

The third week A will start working on what will be included in the video while B and C analyze the results. B will compute the difference between the replicated tables and the post-match tables and C will write down our observations. 

## Repartition of work
Week 1 followed the plan exactly, Quentin modularised the first replication, while Anne and Max replicated the second table.

Week 2 Quentin implemented the distance functions, and started writing the report. Max and Anne implemented the matching. Anne also fleshed out the report.
Week 3 Max finished the matching and generated all the tables. Quentin reorganised and exported those table to the latex format and Anne wrote the bulk rest of the report. And we all worked together to finish the report 🌈

That being said, for week 2 and 3, we each helped the others on about every task, so everyone did a little of everything.
