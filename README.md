# Oliver Wyman Data Analyst Interview Task
Please submit the result as a Github project. You can find a description and all the necessary data for each part of the challenge in the corresponding directory. When submitting your results, a detailed design of the repository is welcome (e.g. README that reflects the way you structured your code and approached the task, related files saved in the appropriate format, code readability, clear and concise comments). Please note that we should be able to reproduce your code and get the same result.  
*Maximum time to complete the task: 7 days.*

The main goal of this challenge is to build a model to predict the probability of default (financial term describing the likelihood that a borrower will be unable to meet its debt obligations: important – assume borrowers that have defaulted previously are not eligible for a new loan). The task contains the following sections:
* Part 1 ‐ Exploratory data analysis


This part of the task assumes efficient json processing, as well as applied EDA with an explanation of what methods of exploring the data are used and what conclusions can be drawn from this analysis, as well as additional analyses that you might perform if you had more time.


* Part 2 ‐ Experiment and metrics design


Part 2 expects you to design your experiment: what sample will you use to predict the probability of default and how will you create it? Moreover, how will you choose the methods for evaluating the quality of the model? It's worth providing a detailed justification of the chosen metric, taking into account all the advantages and disadvantages of it's application to the stated problem.


* Part 3 ‐ Predictive modeling


The last part of the task is dedicated to building a predictive model. It is expected that feature engineering (keep in mind potential data limitations and think about how to circumvent them, e.g. how can we ensure that our model is able to compare financials of both large and small companies), feature selection, model selection and model tuning techniques will be demonstrated in this part of the task. Additionally, it would be great if you could provide a description of the result obtained, the advantages and disadvantages of the final model (and/or the approaches you used), possible steps to improve it.


* Additional Task: ensuring production-grade performance

If you’d like, you can perform a bonus task to showcase your coding skills: here, we ask you to design your code in such a way as to automate the scoring process.



## Execution format
All parts could be executed in IPython Notebooks in reproducable way and stored in corresponding folders. However, you can earn additional points by fitting the prediction pipeline of a final model in a class with methods 'read_data', 'transform_data' and 'predict'. The example is in 'Additional Task' directory.

##### Good luck !
