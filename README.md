# ML_model_HMM-POS-tagging
HMM POS tagging

Download the dataset and Create a dataframe named as IMDB then check the head, info, and describe methods on created dataframe IMDB.
Perform pre-processing steps like Removing Punctuations, Numbers, and Special Characters, Stop Words in dataset
Normalize review column by using Stemming or Lemmatization.
Preprocessed review should be included in the IMDB data frame as ‘cleaned_review’. Plot word cloud for the sentence.
Create two objects X and y. X will be the ‘cleaned_review' column of IMDB data frame and y will be the ' Sentiment' column.
  a. Perform label encoding technique for sentiment column.
  b. Create a TF-IDF object and split the data into training and testing sets. Train a Support Vector machine and Display the confusion Matrix.
  c. Create a BoW object and split the data into training and testing sets. Train a Support Vector machine model and Display the confusion Matrix.
  d. Compare BoW and TF-IDF
Build and display a dependency parser tree for the sentence
“I thought this movie did a down right good job”
Display the HMM POS tagging on the first 4 rows of ‘cleaned_review’.
