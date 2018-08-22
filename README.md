# AB-Testing

## Summary
A Jupyter notebook template/tutorial for running and evaluating ABn tests where the KPI of interest is binomial.

## Motivation
Reduce the amount of work required to set up and evaluate website experiments.

## What is included in this notebook?
- Step by step guide with instructions for setting up an experiment and explanations for how to interpret results
- Deconstructed built-in python functions used to calculate test statistics
- Plug and play format with call-outs to customizable cell blocks to allow the experimenter to quickly load their own data and modify formula default inputs 
- Links to additional resources
- Explanation for how to evaluate multiple variation tests

## How to navigate this notebook?
- Set Up: Pre Test 
    - Sample Size Calculator
    - Alpha Cutoff (Type I Error & Bonferroni Adjustment)
    - Determining Minimum Detectable Effect Size
- Set Up: Proportional Data
    - General Data Set Up (should be applicable to most data for proportion evaluation)
- Test Evaluation
    - 2 Sample Testing (z-test)
    - 2+ Sample Testing (chi-square)
    - Marascuilo Procedure (Multi pairwise z-test)
    
## How to use this notebook in order to get the most out of it?
- Load in a csv file (or query result) that matches the data structure (see section *Data Setup: Proportion*).
- Any `Cell block` that requires the experimenter to modify/input new variables is denoted with the color red and the following heading ***~ Set up Variables ~ *** (the rest of the cell blocks should not require any modifications).
- The 2 and 2+ Sample Test sections do NOT need to be run sequentially (*2+ Sample Testing* section will work without first having to run the cell blocks in the *2 Sample Testing*).

## Feedback
 I wanted to share some of the kind words that my colleagues used to describe the notebook.
- "I used a bunch of your code from the AB testing notebook for proportions in a HP testing notebook. It worked pretty smoothly!"
- "This is a fantastic notebook. It is thorough and comprehensive. You've left no stone unturned."
- "Isn't it great how fast I can asnwer all these questions?! (love this notebook)"
- "Starting to see some positive results... Thanks again for all your help getting the analysis notebooks together"


