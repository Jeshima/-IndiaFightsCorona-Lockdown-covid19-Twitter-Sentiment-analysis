# -IndiaFightsCorona-Lockdown-covid19-Twitter-Sentiment-analysis
 I qt worked on corona virus tweet streams With hashtags #covid19,#indiafightscorona,#lockdown 
 I did generate the dastset from the stream and procesed according to the working of deep learning algorithms work flow.
 I reframed my datset with 2 parameters-- tweets full text and sentiment score and worked on 4 algorithms mam.  
 
 
 SET 1- DEEP LEARNING ALGOTITHMS: 
 1.CNN -(used 1csv with train_test_split method ) Accuracy-0.73368 
 2.LSTM- (used 2csv file seperate for trainingand testing) Training accuracy-0.9457,loss-0.1605 Testing accuracy-0.6557,loss-0.3442 
 3.FFNN-( used 2csv file seperate for trainingand testing) Training accuracy-0.28,loss-622.3 Testing accuracy-0.14893,loss-141.82 
 4.ANN with TFIDF Vectorizer(used 1 csv wth train_test_split)
 The different Ann epoches and models with different learning rate and different drop out value ,Training accuracy ranged btween 0.4752 to
 0.6270 and the Validation accuracy ranged 0.2353 constantly
 On comparing the above 4 algorithms 
 I came to a conclusiom with my understanding Sentiment analysis in tweets can be done efficiently in this order. 
 CNN > LSTM > ANN > FFNN.  
 
 SET 2-MACHINE LEARNING
 I did try with Linear Support vector Classifier --1 csv train_test_split method 
 Training accuracy - 0.6666 Testing accuracy(f1score)-0.59471  
 
 And with Naive bayes classifier--1 csv train_test_split method 
 Training accuracy - 0.64 Test accuracy -0.5486  
 
 SET 3- MODEL CLASSIFICATIONS: 
 I compared my datasets efficiency with 4 models . 
 The accuracies of the model classificatiom are: 
 1.Baseline Model - 62.86% 
 2.Reduces Model-65.71% 
 3.Regularized Model-66.86% 
 4.Dropout Model-67.43% 
 
 Efficient modeling order for tweet data-set 
 Dropout model > Regularized model > Reduced model > Baseline model .
