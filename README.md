This project implements a supervised machine learning pipeline for classifying human activities using smartphone motion sensor data from the MotionSense dataset (by Malekzadeh et al.). The goal is to recognize six common daily activities using time-series data from accelerometer and gyroscope sensors.

Our model is a fully connected neural network (FCNet) built using TensorFlow/Keras. It learns to classify time-series sensor data into activity classes without requiring handcrafted features.

Our best model achieved an average cross-validation accuracy of 93.44%.

**EEE4114F ML Project Code Part 1.ipynb** contains the preliminary analysis of the data. **Standard_Training.ipynb** is where you will find our training and evaluation from start to finish. **6_Input_Features.ipynb** and **Increased_Hidden_Layers.ipynb** is where we assessed variations in our training process.

This project was developed for educational purposes as part of the EEE4118F Digital Signal Processing course assignment. It is not intended for production use.
