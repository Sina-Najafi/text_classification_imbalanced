# text_classification_imbalanced
in this problem we have an imbalanced dataset which contains three labels -1,0,1. samples with the label 0 must be removed 
and then I create a 2-class classification model using classic ML models. the classification is about the sentence being grammatically right(1) or 
wrong(-1). label 0 samples are unacceptable samples. the challenge here is that the dataset is imbalanced{label(1) : 5, label(-1): 1} and we have to
get more than 50% of both classes right and have the highest recall possible which is hard because the imbalanced dataset makes it easy for the model to 
learn to give out just class 1 as output.
some feature extraction and selection is done and in the end I have used an ensemble model(majority voting)
