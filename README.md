#EEG Signal Analysis


DATA :The EEG device used in the experiment is the Emotiv Epoc X 14 channel headset

Data Acquisition :several students with varying levels of education (High school, Middle school, Undergraduate) were invited to watch an online lecture and recorded their EEG data and brain waves during the lecture. Experiment began by asking them several questions to understand their knowledge base and picked several videos that they would be able to understand and several videos that they wouldn't be able to understand. Then recorded their EEG data, Brain waves, and added a binary variable that indicated whether the student understood the lecture or not. (1 = Understood the lecture | 0 = Did not understand the lecture). All of recordings were then appended to a single dataset (EEG data.csv).

Experiment The data contains eeg signals from 14 electriodes. In this experiment, eeg signal is split in to chunks of 2 seconds and then alpha beta, theta and delta components from all these electrodes are used as features to make a classification model. The classification models include, SVM, Logestic regresssion model, two of ensomble model (Random forrest and XG boost) and an Artificial neural network model.

Among all the classifiers SVM outperformed all others with highest F1 score of 0.93


please find the link to the data set at : https://www.kaggle.com/datasets/madyanomar/eeg-data-distance-learning-environment?resource=download
