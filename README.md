# Classifying Tweets about Roe vs. Wade

A binary classifier for identifying if tweets are pro-choice or pro-life.

In June 2022, Roe v. Wade was overturned by the Supreme Court. Since then, there have been countless laws passed restricting abortion access, and even lawsuits introduced working to restrict access in states where the procedure remains legal (namely through trying to ban the abortion drug Mifepristone). These news have galvanized members of the American public on both sides: either through mourning the loss of access or celebrating a victory for the pro-life movement. And, a lot of these people have taken to Twitter to share their thoughts, opinions, and feelings about the ruling.

In this project, my goal was to see if it was possible to identify whether tweets were pro-life or pro-choice based on the language used. I did this by using a dataset of preclassified tweets about the decision, which included data about the content of the tweets, users, and their bios. I ran this data through a classification model that worked to predict whether the tweet was classified as pro-life or pro-choice based on the training data provided.

Setup note: This classifier needs Keras to be installed in order to run.
