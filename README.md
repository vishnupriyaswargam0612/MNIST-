[Click here to view the project](https://2pm9xwx3qcruqqxmqh6mtv.streamlit.app/)**)
MNIST Handwritten Digit Recognition System
Project Overview
The MNIST Handwritten Digit Recognition System is a Machine Learning project developed to recognize handwritten digits from 0–9 using the famous MNIST dataset. The project uses deep learning techniques to train a model capable of accurately predicting handwritten numbers from image inputs.
This project demonstrates the implementation of image classification using Python and popular Machine Learning libraries.

Features


Handwritten digit recognition (0–9)


Trained on the MNIST dataset


Image preprocessing and normalization


Deep Learning model implementation


High prediction accuracy


User-friendly prediction workflow


Data visualization for results and accuracy



Technologies Used


Python


TensorFlow / Keras


NumPy


Matplotlib


Scikit-learn


Jupyter Notebook / Google Colab



Dataset
The project uses the MNIST dataset, which contains:


70,000 grayscale images


28x28 pixel handwritten digits


60,000 training images


10,000 testing images


Dataset Source:
MNIST Dataset

Project Workflow
1. Data Collection


Imported the MNIST dataset from Keras datasets.


2. Data Preprocessing


Normalized pixel values


Reshaped image dimensions


Converted labels into categorical format


3. Model Building


Implemented a Deep Neural Network using TensorFlow/Keras


Added Dense layers and activation functions


4. Model Training


Trained the model using training data


Evaluated using test data


5. Prediction


Predicted handwritten digits from image inputs


6. Visualization


Displayed sample digits and prediction outputs using Matplotlib



Model Accuracy
The model achieved high accuracy on the test dataset for handwritten digit classification.
Example:


Training Accuracy: 98%+


Testing Accuracy: 97%+



Folder Structure
MNIST-Project/│├── dataset/├── models/├── notebooks/├── images/├── app.py├── requirements.txt├── README.md└── mnist_model.h5

Installation and Setup
Clone the Repository
git clone https://github.com/your-username/MNIST-Project.gitcd MNIST-Project
Install Dependencies
pip install -r requirements.txt
Run the Project
python app.py

Sample Output


Input: Handwritten digit image


Output: Predicted digit with confidence score



Future Enhancements


Deploy as a web application


Real-time digit recognition using webcam


Improve model accuracy using CNN architecture


Add GUI interface for user interaction



Learning Outcomes
Through this project, I gained practical knowledge in:


Machine Learning concepts


Deep Learning basics


Neural Networks


Image Processing


Data preprocessing


Model training and evaluation



Author
Baladithya Sai Kumar
B.Tech Student | Aspiring Full Stack & Machine Learning Developer

License
This project is developed for educational and learning purposes.
