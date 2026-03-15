 IMDB Sentiment Analysis using TensorFlow
This project performs sentiment analysis on movie reviews using a neural network built with TensorFlow. The model is trained on the IMDB Movie Reviews dataset to classify reviews as positive or negative.
Technologies Used
* Python
* TensorFlow
* Keras
* TensorFlow Datasets
Dataset
The project uses the IMDB Movie Reviews dataset which contains 50,000 labeled movie reviews. The dataset is split into training and testing sets for building and evaluating the model.
 Model Architecture

The neural network model includes:

* Embedding Layer
* Global Average Pooling Layer
* Dense Layer with ReLU activation
* Output Layer for binary classification

 Training

The model was trained for **15 epochs** using the Adam optimizer and Binary Crossentropy loss function.

 Results

The model successfully learns to classify movie reviews as positive or negative. The training output and evaluation results are shown below.

