This project implements a supervised machine learning pipeline for classifying human activities using smartphone motion sensor data from the MotionSense dataset (by Malekzadeh et al.). The goal is to recognize six common daily activities using time-series data from accelerometer and gyroscope sensors.

Our model is a fully connected neural network (FCNet) built using TensorFlow/Keras. It learns to classify time-series sensor data into activity classes without requiring handcrafted features.

Our best model achieved an average cross-validation accuracy of 93.44%.
