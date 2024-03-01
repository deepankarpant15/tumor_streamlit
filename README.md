
# Brain_Tumor_Detection

This repository contains code for a brain tumor detection application built using Streamlit. The application allows users to upload MRI images and receive predictions about the presence of a brain tumor.

**Features:**

* Allows users to upload MRI images for analysis
* Provides real-time predictions about the presence of a brain tumor.

* Built using Streamlit for a user-friendly interface.

* Uses a deep learning model trained on MRI images for classification.



## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`requirement.txt`

`pip install Pillow==9.5.0`


## Installation


* Clone this repository to your local machine.

* Install the required dependencies 
```bash
 pip install -r requirements.txt.
```
    
* Run the Streamlit app using streamlit run
```bash
streamlit run app.py.
```
    
## Usage

* Upload an MRI image using the file uploader.

* Click on the "Predict" button to receive predictions about the presence of a brain tumor.

* View the prediction results on the app interface.
## Credits
* The deep learning model for brain tumor detection is based on TensorFlow and Keras.

* Streamlit is used for building the web application interface.

* MRI images for training and testing the model were obtained from [Kaggle](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection),[Dataset2](https://www.kaggle.com/datasets/preetviradiya/brian-tumor-dataset).

Repository for [reference](https://github.com/marshall4471/streamlt_brain_cancer) .