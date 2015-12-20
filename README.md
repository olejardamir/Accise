# Accise (accurate + precise), deep learning for Support Vector Machines
Project that is supposed to push the limits of machine learning with the Support Vector Machines giving the most precise and accurate answer, while automatically adjusting the SVM parameters.


The idea is to allow the user to insert a CSV training file, CSV file that contains rows to apply the prediction onto.
The end-user should not be bothered by SVM settings, furthermore, user should not even need to know anything about SVMs or statistics to use this program.

Since there is enormous amount of settings for SVMs, what we can do is generate a pool of random SVM models and rate each one of them.

Then, we can ask the question: "Assuming the statistical evaluation of the models that were generated, what would be the result if the statistical evaluation were perfect or at some threshold?"
Then, this question is put into a loop until the final answer is obtained.

The algorithm therefore consists of predicting the results based on predicting the statistical evaluation, rather than a classical train-evaluate procedure.

Nevertheless, with this approach, the training is very fast, while obtaining the results can be much slower, depending on the number of epochs or the preferred statistical threshold at which the answers should be obtained.

This solution is meant for situations where we do not need a fast answer, but the most accurate AND a precise answer.


In my humble opinion only, given the deep-learning hype, this approach is similar since it mines the data until the right method is found. 
Therefore, I may call this a very simple SVM deep learning tool.

PS after this project is done, it will be my task to find out what parameters would work the best, and how to make this a one-click solution.

