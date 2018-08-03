# AB-Testing

## Summary
A Jupyter notebook template/tutorial for running and evaluating ABn tests where the KPI of interest is binomial.

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


----- 
## Testimonials
Even though this isn't by any means a paid product, I wanted to share some kind words that my colleagues told me because this notebook helped them save some time and shed light on some tricky concepts. My main goal for this tuturial is to help others do their job better and have a better understanding of some testing fundamentals.

- "I used a bunch of your code from the AB testing notebook for proportions in a HP testing notebook. It worked pretty smoothly!"
- "Paula - this is a fantastic notebook. it is thorough and comprehensive. you've left no stone unturned."
- "isn't it great how fast i can asnwer all these questions?! (love this notebook)"
- "Starting to see some positive results... Thanks again for all your help getting the analysis notebooks together"


