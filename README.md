# Recurrent-neural-network
A recurrent neural network (RNN) is a class of artificial neural networks where connections between nodes form a directed graph along a temporal sequence. This allows it to exhibit temporal dynamic behavior.

Problem Statement:- 
1.	Here is the time series data [110,125,133,146,158,172,187,196,210]. 
Build RNN/LSTM model to predict the next 10 digits.
2.	Write down the multiple applications of RNN.
             Applications of recurrent neural networks include:
•	Machine Translation
•	Robot control
•	Time series prediction 
•	Speech recognition 
•	Speech synthesis
•	Time series anomaly detection
•	Rhythm learning
•	Music composition
•	Grammar learning
•	Handwriting recognition
•	Human action recognition[
•	Protein Homology Detection
•	Predicting subcellular localization of proteins
•	Several prediction tasks in the area of business process management
•	Prediction in medical care pathways

3.	How to do select the inputs for a LSTM/RNN models. Explain in the terms of timesteps, samples and feature.
Ans - Samples - This is the len(dataX), or the amount of data points you have.
Time steps - This is equivalent to the amount of time steps you run your recurrent neural network. If you want your network to have memory of 60 characters, this number should be 60.
Features - this is the amount of features in every time step. If you are processing pictures, this is the amount of pixels. In this case you seem to have 1 feature per time step.
 The input to every LSTM layer must be three-dimensional
Samples. One sequence is one sample. A batch is comprised of one or more samples.
Time Steps. One time step is one point of observation in the sample.
Features. One feature is one observation at a time step.


4.	What are the disadvantages of MLP when dealing with sequence data.
         Ans- 
                The use of feedforward neural networks on sequence data raises two majors                         problems: Input & outputs can have different lengths in different examples. MLPs do not share features learned across different positions of the data sample. 
               Input & outputs can have different lengths in different examples
               MLPs do not share features learned across different positions of the data sample
