# BERT_emotion_analysis
This project contains some trial versions and some work-in-progress code that perform emotion analysis, along with the datasets required to perform the analysis.

## Contents
It contains the following files:
  1. friends_finetune_31.ipynb --- emotion analysis code (being used currently)
  2. friends_train.csv --- training dataset in the format accepted by friends_finetune_31.ipynb
  3. friends_test.csv --- testing dataset in the format accepted by friends_finetune_31.ipynb
  4. friends_dev.csv --- dataset for validation in the format accepted by friends_finetune_31.ipynb
  5. friends_train_nofilter.csv --- training dataset in the format accepted by friends_finetune_31.ipynb without any filter
  6. friends_test_nofilter.csv --- testing dataset in the format accepted by friends_finetune_31.ipynb without any filter
  7. friends_dev_nofilter.csv --- dataset for validation in the format accepted by friends_finetune_31.ipynb without any filter
  8. 

## Output files
The program friends_finetune_31.ipynb will produce the folowing files:
  1. classification_report_nofilter.txt / classification_report.txt (depending on what kind of dataset file we use)
  2. classification_report_optimized.txt --- produced by the code for comparison purposes
  3. comparisons.csv --- a csv file containing the emotions that were correctly/wrongly predicted
  
  
  
  
  
 The filtering criteria is: Consider all those dialogues that are atleast 3 words long and have the possessive "I" in it.
 
 # Some other papers that have used the same dataset are:
  1. EmotionX-IDEA: Emotion BERT -- an Affectional Model for Conversation by Huang et al (August 2019)
      https://arxiv.org/pdf/1908.06264v1.pdf
      https://paperswithcode.com/paper/emotionx-idea-emotion-bert-an-affectional/review/
      
  2. EmotionX-KU: BERT-Max based Contextual Emotion Classifier by Yang et al (June 2019)
      https://arxiv.org/pdf/1906.11565v1.pdf
      https://www.groundai.com/project/emotionx-ku-bert-max-based-contextual-emotion-classifier/1
      code: https://github.com/KisuYang/EmotionX-KU
      
