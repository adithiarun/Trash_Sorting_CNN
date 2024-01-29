# Waste Sorting CNN
I created a convolutional neural network to identify different types of waste (paper, plastic, glass, metal, cardboard). In order to improve the performance of the model, I implemented metrics to measure its performance and tuned the model until it performed well. 

The next part was deploying the model on a Raspberry Pi to identify waste in realtime. I had a camera connected to the Raspberry Pi which would take a picture of the object in front of it. Code was implemented on the Pi to convert the image into a form that could be fed into the model.

Project required knowledge of OpenCV, TensorFlow, Keras, and ML concepts.
