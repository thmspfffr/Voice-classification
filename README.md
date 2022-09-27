# Voice-classification

Attempts at classifying the emotional tone of human voices using the RAVDESS dataset (using TensorFlow / Keras, model fitting in Google Colab)

Approaches the problem through a series of steps:

(1) Preprocessing, specifically spectral analysis
(2) Regular neural network (3 layers)
(3) Convolutional neural network 
(4) Further preprocessing, specifically data augmentation (e.g. adding noise)
(5) Re-running of the convolutional neural network 
(6) Hyperparameter optimization through random search

After data augmentation and hyperparameter optimization, the convolutional neural network achieves a classification accuracy of ~83%, which is quite competetive compared to other/similar appropaches (e.g. Zised et al., 2020)
