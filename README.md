Data Collection/Preparation

In this section, we gather and prepare the dataset necessary for training our models. The data involves images of plant leaves from various classes, each representing a different plant disease. The dataset is augmented to enhance model generalizability, involving transformations like rotation, zoom, and flips. This preparation ensures our models are trained on a robust dataset that simulates a variety of real-world conditions.

Modelling

The modelling section details the construction and training of convolutional neural networks (CNNs) designed to classify images of plant diseases. We use TensorFlow/Keras to build two separate models with different architectures to compare their performance. Each model includes layers for convolution, activation, pooling, and dense connections, tailored to extract features and perform classification tasks effectively.

Evaluation

Evaluation is conducted by applying the trained models to a separate test dataset that the models have not seen during training. We use metrics such as accuracy, precision, recall, and F1-score to assess the performance of each model. This section includes the setup for these metrics and discusses the results obtained from the models.

Interpretation

This final section interprets the outcomes of the models' performance. It includes a discussion on how different architectural choices and training parameters impacted the results. We analyze specific cases where the model performed well or poorly to understand the strengths and weaknesses of our approach. Comparisons between the models provide insights into the effectiveness of different neural network configurations for image-based plant disease classification.

