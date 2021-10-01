# Applied-Machine-Learning
# Introduction
The assessment for AML 2021 is based around a private Kaggle in-class competition. The link will be released on Moodle during the first few weeks. Please do
not share it with anyone outside of our AML class. You enter the competition
by downloading the data and accepting the rules. Set up a team and invite your
team members to join the team. Group members that do not join their Kaggle
team will not receive any marks for this assignment. Teams that invite external
members to the team will not receive any marks.
Please note that all scripts will be checked for plagiarism. In previous cohorts,
students have been failed for this. If you satisfy the pre-requisites, keep up
with lectures and work on the assignment, in a group, throughout the course
you should be able to complete this assignment. There is no negative marking
and a good pass is possible without attempting Part 5 if a conscientious and
thoughtful attempt is made on Parts 1-4.
Your work may end up consisting of various python notebooks, screenshots of
Kaggle entries and a word document. These should be zipped and uploaded to
Moodle before the coursework deadline.

## The competition metric is Area Under the ROC curve (AUCROC). We did not
cover this in class (though one of the links covers it). Briefly:

- You may think of it as the probability that two customers chosen at random will be correctly ranked for the risk of carrying out fraud.
- If AUCROC is 0.50 it means there is a 50/50 chance of ranking any two
randomly chosen customers correctly. You could have done this by simply
assigning model predictions at random. Therefore if your AUCROC is
about 0.50, your model is no better than a naive model.
- If AUCROC is 1 it means that you rank any two randomly chosen customers correctly every single time. This is a perfect model. If you attain
1
an AUCROC of 1 on the train data, then you have completely overfitted
your model. If you get an AUCROC of 1 on the test data it means I have
made a mistake and you should post this on Moodle immediately!

## There are 5 parts to this assignment:
- Part 1. Data Cleaning.
- Part 2. Linear regression 
- Part 3. Penalised logistic regression (elastic-net) with H2O 
- Part 4. Gradient boosting with catboost 
- Part 5. A choice of one of the topics covered in week 6
