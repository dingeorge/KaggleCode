Attached are three files: One M2017-train.csv with 800+ of original Professor Moody grading data and another, the M2017_test_students.csv  data with missing GRADE column.  Finally M2017_sample_submission is the file you will submit to Kaggle of course after filling up the GRADE column.
The fourth  is not included, it has real grades and it will be used to calculate your prediction error.

 Your job is to predict the grades in the testing file, adding to it GRADE attribute  with predicted grades.  This submission will be handled though kaggle not sakai (instructions coming). Kaggle will automatically calculate your prediction error.  In this case, of Professor Moody data, it will be a fraction of grades which you have predicted incorrectly. 



FOR THIS PREDICTION CHALLENGE:  Clean or free style prediction only, Do not use any R library functions. Just follow examples from data101/laboratory, the CleanPrediction0 example from MISC category (not the one with rpart).  Just your own rules implmented for example like I did through the decision vector. Refine your prediction by looking at which graded you got wrong on the training data and try to capture them. But beware of overfitting since it may not work on testing data (remember we are predicting the future...)

WHAT TO SUBMIT:  Kaggle submission is a MUST, cannot be late - per instruction follow the attached M2017_sample_submission . You can only submit it ONCE. But you can refine your predictor on R studio as many times as you want before submitting the final csv file with predicted grades to Kaggle. ALSO - Kaggle will only be open on the last day of submision - TUESDAY.  

Plus: power points explaining what you did. Plus  your R code.  So 3 elements of submission: Kaggle file, ppt and code. We will check the top solutions  for the consistency of code - i.e. did you really get such a small error using this code?