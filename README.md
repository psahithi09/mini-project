# mini-project

My project involved developing an asthma risk prediction system that utilizes environmental data collected through sensors. We harnessed the power of deep learning, specifically a 1D Convolutional Neural Network (1DCNN), to train our predictive model using a naturally acquired dataset from these sensors.

In real-time, our system provides risk assessments for asthma, indicating whether the likelihood is high, low, or medium. It does so by illuminating LED lights as a visual indicator. Here's a streamlined breakdown of the process:

Data Collection: We obtained atmospheric data from patients using sensors.

Model Training: We trained a 1DCNN model with this dataset to predict asthma risk levels.

Data Transmission: Data collected by the sensors, which were connected to ESP32, was transmitted to a Raspberry Pi using MQTT protocol.

Inference: The Raspberry Pi houses the trained 1DCNN model. The data received is then sent to the model for asthma risk prediction.

By condensing the description, we emphasize the key components and steps involved in your project's asthma risk prediction system.
