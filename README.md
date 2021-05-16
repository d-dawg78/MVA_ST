#### Final Project Submission for the Time Series course at the École Normale Supérieure (Master MVA)!

#### Group: Dorian Desblancs, Clément Berger

#### Abstract:

In this project we studied the work done by John Atkinson and Daniel Campos in their article Improving BCI-based emotion recognition by combining EEG feature selection and kernel classifiers [1]. Their paper presents a method to recognize emotions using EEG signals. More precisely, they aim to classify arousal and valence. Their method is split into two sections. The first is centered around feature extraction, and makes use of the minimum-Redundancy-Maximum-Relevance (mRMR) technique [7]. The second is centered around emotional classification, and makes use of a Support Vector Machine (SVM) classifier. While the paper demonstrates the method to be competitive against other state-of-the-art models, our implementation of their pipeline failed to generate the same results. Most notably, they achieved more than 60% accuracy on the DEAP data set [3] for each emotion using 8-fold classification. We were unable to break 50%.

The DEAP data set can be found here: http://www.eecs.qmul.ac.uk/mmv/datasets/deap/
