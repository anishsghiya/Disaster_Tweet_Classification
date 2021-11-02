# Disaster Tweet Classification
Hugging Face implementation of BERT model for disaster tweet clasification. 

# Dataset Used
For the implementation the dataset used is NLP Based Disaster Tweet Classification [Link to Dataset](https://www.kaggle.com/c/nlp-getting-started/overview)<br>

# Basic Introduction 
Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. So to make sure that the safety teams respond to the right tweets more often than the ones that might not be disaster related in an automated way an NLP based model is designed in order to attain this.

# Procedure
The following was the pipeline used for the complete project included the following steps :
> 1. Basic EDA
> 2. Pre-processing
>    * abbreviations fix 
>    * correcting spellings
>    * removing unwanted spaces
>    * remove URLs
> 4. Vectorization (Tf-IDF vectorizer)
> 5. Machine Learning 
>    * Logistic Regression
>    * Decision Tree Classification
>    * XGB Classifier
>    * MLP Classifier
> 6. Deep Learning
>    * Bi-directional LSTM with BatchNormalization
>    * BERT model 

# Leaderboard position
At the time of creating this repository I rank 25/891 teams. [Leaderboard](https://www.kaggle.com/c/nlp-getting-started/leaderboard)

# Author
Anish S Ghiya (@anishsghiya)
