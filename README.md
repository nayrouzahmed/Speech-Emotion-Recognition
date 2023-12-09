# Speech-Emotion-Recognition
Speech is the most natural way of expressing ourselves as humans. It is only natural then to extend this communication medium to computer applications. Speech emotion recognition (SER) systems is defined as a collection of methodologies that process and classify speech signals to detect the embedded emotions.

Steps done in this project to achieve the goal of this assignment:

Write the function that load and plot the waveform of the audio files

Create the feature Space by working on the attributes of the signal in the time domain and frequency domain and create another feature space by converting the audio into a melspectogram and use this as the feature space

Split the data into 70% training and validation and 30% testing. Use  5%  of  the  training  and  validation  data  for validation.

Build the CNN  architecture. For the time domain or frequency domain feature space, the feature space will be 1 dimensional, therefore in the architecture we will be using 1D convolutions. While  in  melspectogram  feature  space,  the  audio  is represented as an image, therefore we will be using 2D convolutions.

Compare between the performance of the learned models (Different features, different learning models) by realizing the following. a.Compute the accuracy and F-Score for each model. b.Plot the confusion matrices and find the most confusing classes. 
