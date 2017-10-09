# VisTA
Visualization by Topic Allocation. Using topic probability dissimilarity to discover a latent feature space for understanding twitter user stances and their community structure
To run the visualization portion of the code, open the Recent_LDA folder. 'TopicMDS.ipynb' enables you to visualize the user structure for the target topics of "Atheism", "Legalization of Abortion","Climate Change is a Real Concern", "Hillary Clinton", and "Feminist Movement" by changing the value of target based upon the list of targets, called targets.

To see the stance classification and scoring portion of the code, open 'KNN&Scoring.ipynb' and once again, change the target to the topic that you wish to evaluate.

The RBMUsers Folder already contains the created documents for the users of the controversial topics based on the SemEval 2016 dataset. However, if you wish to create the documents from scratch, you must open the DocCreationTfIdfClassifiers Folder and insert your Twitter access credentials in 'User Document Creation.ipynb'

To run the supervised classifiers on the SemEval 2016 dataset, run 'SVMandNaiveBayes.ipynb'

To see the tf-idf k-means clustering implementation for topics, run 'K-means Tf-IDF.ipynb'

I have uploaded the relevant GloVe files from the Stanford NLP group. The SemEval 2016 dataset is in the stance folder.
