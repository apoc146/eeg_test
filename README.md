# Seizure_Forecasting_Analysis_of_EEG_Data
By implementing seizure forecasting, a new therapeutic
strategy for epilepsy, providing patient warnings
and delivering preemptive therapy can be achieved. Epilepsy
prevention can be reached by the understanding, learning and
forecasting of seizures through the information of electroencephalogram
(EEG) signals. In this paper, a proposed methodology
utilizing feature extraction and Hidden Markov Model
(HMM) to classify EGG time series data is proposed and it is
demonstrated to accurately predict whether a signal is preictal
or interictal with up to 84% accuracy. Kmeans of Pyspark, a framework
learnt in the Big Data Analytics (EECS E6893), is used to
initialized the probabilities matrices of the HMM. This paper
uses the dataset provided by the kaggle competition ’American
Epilepsy Society Seizure Prediction Challenge’.

In order to run the application:

* Create and start an instance at the Google Cloud Platform
* Install Spark, Scipy, Numpy, scikit-learn, h5py and GitHub on your instance
* Clone this repo onto your instance
* Go to the repo's directory in cmd and type "python main.py"
