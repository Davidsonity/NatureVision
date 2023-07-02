## Project Title: Nature Scene Classifier
![Sample Nature Image](https://user-images.githubusercontent.com/96771321/214588217-b037c3e3-bbb3-4e52-9da7-3459cbdc27b4.jpg)

### Introduction
The objective of this project is to build a powerful deep learning neural network that can classify images of buildings, forests, glaciers, mountains, seas, and streets with high accuracy. Transfer learning techniques are used, and three pre-trained models are evaluated: Xception, InceptionV3, and VGG16.

### Dataset
The dataset used in this project is called "Natural Scenes Image Classification" and contains approximately 25,000 images of size 150x150 distributed across six categories: buildings, forests, glaciers, mountains, seas, and streets. The dataset is originally published on [Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) and was provided by Intel for an image classification challenge.

### Project Structure
The project is structured into the following sections:

1. Data Preprocessing: This section involves importing the necessary libraries, setting up the directory paths, and visualizing random images from the dataset.

2. Model Building: In this section, three pre-trained models (Xception, InceptionV3, and VGG16) are built and trained using the dataset. Each model is evaluated for accuracy and performance.

3. Comparing Results: The results from each model are compared by plotting the accuracy per iteration.

4. Saving the Model: The best model (Xception) is saved for future use.

5. Testing the Model: The saved model is loaded and used to predict and classify images from a test dataset. The predicted labels are compared with the actual labels to evaluate the model's performance.

### Results
The project achieves good accuracy in classifying the images, with the Xception model showing slightly higher validation scores compared to InceptionV3 and VGG16. The accuracy over the test set is measured to be 95.65%.

### Deployment
The project is deployed and accessible through the following link: [Nature Scene Classifier App](https://davidsonity-nature-scene-classifier-app-0f6zht.streamlit.app/). This web application allows users to upload their own images and obtain predictions for the corresponding nature scenes.

### Usage
To run this project, follow these steps:

1. Set up the environment with the necessary libraries and dependencies.
2. Download the dataset from the provided Kaggle link or any other suitable source.
3. Extract the dataset and ensure the directory paths in the code are correctly set to the dataset's location.
4. Run the code sections sequentially to preprocess the data, build and evaluate the models, compare the results, save the best model, and test the model on new images.
5. Observe the visualizations and performance metrics to analyze the model's accuracy and effectiveness.

### Conclusion
The project demonstrates the effectiveness of transfer learning techniques in building powerful image classification models. By leveraging pre-trained models such as Xception, InceptionV3, and VGG16, accurate predictions can be achieved even with limited training data. This project can serve as a starting point for more advanced image classification tasks and can be further improved by fine-tuning the pre-trained models or exploring other architectures.

> Deployment Site: [Nature Scene Classifier App](https://davidsonity-nature-scene-classifier-app-0f6zht.streamlit.app/)
>
> View Notebook: [GitHub Notebook](https://github.com/Davidsonity/Nature-Scene-Classifier/blob/main/n
