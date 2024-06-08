Data Collection/Preparation

In this section, I gather and prepare the dataset necessary for training the models. The data involves images of plant leaves from various classes, each representing a different plant disease. The dataset is augmented to enhance model generalizability, involving transformations like rotation, zoom, and flips. This preparation ensures the models are trained on a robust dataset that simulates a variety of real-world conditions.

Modelling

The modelling section details the construction and training of convolutional neural networks (CNNs) designed to classify images of plant diseases. I use TensorFlow/Keras to build two separate models with different architectures to compare their performance. Each model includes layers for convolution, activation, pooling, and dense connections, tailored to extract features and perform classification tasks effectively.

Evaluation

Evaluation is conducted by applying the trained models to a separate test dataset that the models have not seen during training. I use metrics such as accuracy, precision, recall, and F1-score to assess the performance of each model. This section includes the setup for these metrics and discusses the results obtained from the models.

Interpretation

This final section interprets the outcomes of the models' performance. It includes a discussion on how different architectural choices and training parameters impacted the results. I analyze specific cases where the model performed well or poorly to understand the strengths and weaknesses of the approach. Comparisons between the models provide insights into the effectiveness of different neural network configurations for image-based plant disease classification.


- Data Setup Instructions:
To ensure seamless operation of the Jupyter Notebook in Google Colab, please follow these steps to set up the data and model files in your Google Drive:

- Access Data and Model Files:

Use the provided shareable links to access the folders and files necessary for this project. You will find links to the full dataset, a separate test dataset folder, and two .h5 model files.

- Add to Your Google Drive:

For each shareable link, open the link and then choose "Add shortcut to My Drive" or "Make a copy" to add the data and model files to your own Google Drive. This step is crucial for ensuring the paths in the Jupyter Notebook correspond to the actual data locations in your Google Drive.

- Folder Structure:

Ensure that the structure of the folders and files in your Google Drive matches the paths specified in the Notebook. The main folder should contain:
> The full dataset folder
> The test dataset folder
> Two .h5 files for the models
> A file with labels for the dataset


