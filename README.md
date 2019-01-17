# MNIST-Digit-Recogniser
MNIST Digit Recogniser using 2 Layer NN and CNN

# API Used
- Keras with Tensorflow

# CNN Architecture
<img src="https://github.com/zed1025/MNIST-Digit-Recogniser/blob/master/architecture.png">

# For 2 Layer NN
- Layer 1 (for flattening the image into a (#training examples, 784) vector)

  Flatten()
- Layer 2

  Dense(512, activation=tf.nn.relu)
- Layer 3

   Dense(10, activation=tf.nn.sigmoid)
   
   
   
# Results
- For CNN (98.62% accuracy)

  [0.061862983450492175, 0.9862]
  
  Optimizer used: adam
- For 2 layer NN (98.43% accuracy)

  [0.06278382793604251, 0.9843]
  
  Optimizer used: adam
  
  
  # Notes
  - See [this](https://gist.github.com/stared/dfb4dfaf6d9a8501cd1cc8b8cb806d2e) for plotting loss.
