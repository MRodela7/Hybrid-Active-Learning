# Hybrid-Active-Learning
Developed a self-switching algorithm which alters between Uncertainty Sampling, Diversity Sampling and Query by Committee to chose the best uncertain data for the model to train on using Active Learning.
The base machine learning model used was Random Forest Classifier, imported from scikit learn library. 
Uncertainity Sampling Algorithm, Diversity Sampling and Query by Committee Algorithms were coded from scratch (without external library imports).
The hyrid active learning model was tested using RNA-seq data of lung cancer paitents, taken from the TCSA database.
It was tested agaist small generated "good data" where the model performance was significant (greater than 90% within the first three iterations, when compared against a non-hybrid model). 

This was a group project by three fellow coursemates and myself. My role was to contribute in the desiging of the switiching algorithm and write the smpling and base machine learning model algorithm. I also worked on testing and model evaluation.
