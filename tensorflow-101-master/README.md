# TensorFlow 101: Introduction to Deep Learning

This repository includes the source codes and notebooks **mostly** captured in **[TensorFlow 101: Introduction to Deep Learning](https://www.udemy.com/tensorflow-101-introduction-to-deep-learning/?couponCode=TF101-BLOG-201710)** online course published on Udemy. Some implementations might have dedicated documentations linked to my personal blog.

<p align="center"><img src="https://i2.wp.com/sefiks.com/wp-content/uploads/2019/01/gsu_vincent.png" width="70%" height="70%"></p>

<p align="center">Vincent van Gogh style Galatasaray University</p>

# Advanced Deep Learning Applications

1- [Facial Expression Recognition](python/facial-expression-recognition.py) ( [Tutorial](https://sefiks.com/2018/01/01/facial-expression-recognition-with-keras/) )

This is a custom CNN model. Kaggle FER 2013 data set is fed to the model. This model runs fast and produces satisfactory results.

<p align="center"><img src="https://i2.wp.com/sefiks.com/wp-content/uploads/2017/12/pablo-facial-expression.png" width="70%" height="70%"></p>

2- [Real Time Facial Expression Recognition](python/facial-expression-recognition-from-stream.py) ( [Tutorial](https://sefiks.com/2018/01/10/real-time-facial-expression-recognition-on-streaming-data/) )

This is the adaptation of the same model to real time video.

<p align="center"><img src="https://sefiks.com/wp-content/uploads/2019/01/real-time-emotion-mark.png" width="70%" height="70%"></p>

3- [Face Recognition With Oxford VGG-Face Model](python/vgg-face.ipynb) ( [Tutorial](https://sefiks.com/2018/08/06/deep-face-recognition-with-keras/) )

Oxford Visual Geometry Group's VGG model is famous for confident scores on Imagenet contest. They retrain (almost) the same network structure for face recognition. This implementation is mainly based on convolutional neural networks, autoencoders and transfer learning. This is on the top of the leaderboard for face recognition challenges.

<p align="center"><img src="https://sefiks.com/wp-content/uploads/2019/01/face-recognition-demo.png" width="70%" height="70%"></p>

4- [Real Time Deep Face Recognition Implementation with VGG-Face](python/deep-face-real-time.py) ( [Demo](https://www.youtube.com/watch?v=tSU_lNi0gQQ) )

This is the real time implementation of VGG-Face model for face recognition.

<p align="center"><img src="https://sefiks.com/wp-content/uploads/2019/01/real-time-face-recognition-demo.png" width="70%" height="70%"></p>

5- [Face Recognition with Google FaceNet Model](python/facenet.ipynb) ([Tutorial](https://sefiks.com/2018/09/03/face-recognition-with-facenet-in-keras/))

This is an alternative to Oxford VGG model. Even though FaceNet has more complex structure, it runs slower and less successful than VGG-Face.

6- [Making Arts with Deep Learning: Artistic Style Transfer](python/style-transfer.ipynb) ( [Tutorial](https://sefiks.com/2018/07/20/artistic-style-transfer-with-deep-learning/) )

What if Vincent van Gogh had painted Istanbul Bosporus? Today we can answer this question. A deep learning technique named artistic style transfer enables to transform ordinary images to masterpieces.

<p align="center"><img src="https://i2.wp.com/sefiks.com/wp-content/uploads/2019/01/gsu_vincent.png" width="70%" height="70%"></p>

7- [Autoencoder and clustering](python/Autoencoder.ipynb) ( [Tutorial](https://sefiks.com/2018/03/21/autoencoder-neural-networks-for-unsupervised-learning/) )

We can use neural networks to represent data. If you design a neural networks model symmetric about the centroid and you can restore a base data with an acceptable loss, then output of the centroid layer can represent the base data. Representations can contribute any field of deep learning such as face recognition, style transfer or just clustering.

<p align="center"><img src="https://i0.wp.com/sefiks.com/wp-content/uploads/2018/03/autoencoder-and-autodecoder.png" width="70%" height="70%"></p>

8- [Convolutional Autoencoder and clustering](python/ConvolutionalAutoencoder.ipynb) ( [Tutorial](https://sefiks.com/2018/03/23/convolutional-autoencoder-clustering-images-with-neural-networks/) )

We can adapt same representation approach to convolutional neural networks, too.

9- [Transfer Learning: Consuming InceptionV3 to Classify Cat and Dog Images in Keras](python/transfer_learning.py) ( [Tutorial](https://sefiks.com/2017/12/10/transfer-learning-in-keras-using-inception-v3/) )

We can have the outcomes of the other researchers effortlessly. Google researchers compete on Kaggle Imagenet competition. They got 97% accuracy. We will adapt Google's Inception V3 model to classify objects.

<p align="center"><img src="https://i2.wp.com/sefiks.com/wp-content/uploads/2017/12/inceptionv3-result.png" width="70%" height="70%"></p>

10- [Handwritten Digit Classification Using Neural Networks](python/HandwrittenDigitsClassification.py) ( [Tutorial](https://sefiks.com/2017/09/11/handwritten-digit-classification-with-tensorflow/) )

We had to apply feature extraction on data sets to use neural networks. Deep learning enables to skip this step. We just feed the data, and deep neural networks can extract features on the data set. Here, we will feed handwritten digit data (MNIST) to deep neural networks, and expect to learn digits.

<p align="center"><img src="https://i0.wp.com/sefiks.com/wp-content/uploads/2017/09/mnist-sample-output.png" width="70%" height="70%"></p>

11- [Handwritten Digit Recognition Using Convolutional Neural Networks with Keras](python/HandwrittenDigitRecognitionUsingCNNWithKeras.py) ( [Tutorial](https://sefiks.com/2017/11/05/handwritten-digit-recognition-using-cnn-with-keras/) )

Convolutional neural networks are close to human brain. People look for some patterns in classifying objects. For example, mouth, nose and ear shape of a cat is enough to classify a cat. We don't look at all pixels, just focus on some area. Herein, CNN applies some filters to detect these kind of shapes. They perform better than conventional neural networks. Herein, we got almost 2% accuracy than fully connected neural networks.

# Curriculum

## Section 1 - Installing TensorFlow

1- [Installing TensorFlow and Prerequisites](https://www.youtube.com/watch?v=JeR2M46tLlE)

2- [Jupyter notebook](https://www.youtube.com/watch?v=W3IJfVL1upI)

3- [Hello, TensorFlow! Building Deep Neural Networks Classifier Model](python/DNNClassifier.py)

## Section 2 - Reusability in TensorFlow

1- [Restoring and Working on Already Trained DNN In TensorFlow](python/DNNClassifier.py)

The costly operation in neural networks is learning. You may spent hours to train a neural networks model. On the other hand, you can run the model in seconds after training. We'll mention how to store trained models and restore them.

2- [Importing Saved TensorFlow DNN Classifier Model in Java](java/TensorFlowDNNClassifier.java)

You can handle training with TensorFlow in Python and you can call this trained model from Java on your production pipeline.

## Section 3 - Monitoring and Evaluating

1- [Monitoring Model Evaluation Metrics in TensorFlow and TensorBoard](python/DNNClassifier.py)

## Section 4 - Building regression and time series models

1- [Building a DNN Regressor for Non-Linear Time Series in TensorFlow](python/DNNRegressor.py)

2- [Visualizing ML Results with Matplotlib and Embed them in TensorBoard](python/DNNRegressor.py)

## Section 5 - Building Unsupervised Learning Models

1- [Unsupervised learning and k-means clustering with TensorFlow](python/KMeansClustering.py)

We feel strong at supervised learning but today the more data we have is unlabeled. Unsupervised learning is mandatory field in machine learning.

2- [Applying k-means clustering to n-dimensional datasets in TensorFlow](python/KMeansClustering.py)

We can visualize clustering result on 2 and 3 dimensional space but the algorithm still works for higher dimensions even though we cannot visualize. Here, we apply k-means for n-dimensional data set but visualize for 3 dimensions.

## Section 6 - Tuning Deep Neural Networks Models

1- [Optimization Algorithms in TensorFlow](python/OptimizationAlgorithms.py)

2- [Activation Functions in TensorFlow](python/ActivationFunctions.py)

## Section 7 - Consuming TensorFlow via Keras

1- [Installing Keras](https://www.youtube.com/watch?v=qx5pivWvKC8)

2- [Building DNN Classifier with Keras](python/HelloKeras.py)

3- [Storing and restoring a trained neural networks model with Keras](python/KerasModelRestoration.py)

## Additional Documents

1- [How single layer perceptron works](python/single-layer-perceptron.py)

This is the 1957 model implementation of the perceptron.

2- [Gradient Vanishing Problem](python/gradient-vanishing.py) ( [Tutorial](https://sefiks.com/2018/05/31/an-overview-to-gradient-vanishing-problem/) )

Why legacy activation functions such as sigmoid and tanh disappear on the pages of the history?
