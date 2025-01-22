# bank-telemarketing-study
This repository contains my submission project of module 17-1 from Professional Certificate in Machine Learning &amp; Artificial Intelligence by Berkeley ExecEd/Berkeley Haas

## The context

During the exercise, I have worked on analyzing data from a [dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing) from S.Moro, P.Rita and P.Cortez that contains 41188 rows.
The objective was to find what are the aspects that impact the success of a bank telemarketing campaign.

## The results

After discovering the data and doing some cleanup in the dataframe, I have run multiple classifiers using the dataframe to build some models.
I have been able to find out that a good month to execute the telemarketing campaign could be either July or March, but more importantly it is very crucial to take
in consideration the social and economic context because all the fields are impacting deeply the results of the marketing campaign; on the other hand it seems
that there are no specific profiles of people answering positively to the marketing campaign.

The most successful classifiers I have used to predict the answers to the bank telemarketing campaign was the k-nearest neighbors classifier called KNeighborsClassifier in
scikit-learn. On the training set the balanced accuracy score was approximately 0.793; and 0.791 against the testing set.

If you want more details on how I found these results or see the size of the samples used, you can find all the details in my notebook referred in the section below.

## The notebook

If you want to read the study, the notebook is accessible [here](https://github.com/jbbenoist/bank-telemarketing-study/blob/main/assignment%2017-1.ipynb).
