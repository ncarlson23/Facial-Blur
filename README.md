# Facial-Blur
This is a privacy tool that uses the Azure Computer Vision Face API to detect and blur faces in images. The code is developed in python and runs in Jupyter Notebook or Google Colab. Read more about Azure Cognitive Services and the Face API here:
https://docs.microsoft.com/en-us/azure/cognitive-services/computer-vision/overview-identity


## How to use this application
1. This tool runs best in a notebook environment, such as Google Colab or Jupyter Notebook. First, upload a copy of this repository to either of these environments by using the github link associated with this repository.

2. Make sure that the project contains the IPYNB file as well as the config.json file and the temp folder.

3. Fill out the config.json file for your specific Azure credentials. You must have an Azure account in order to run this application. You need your subscription ID, location, Key1, and endpoint URL.

4. Find an image to use in the application. The image must contain human faces. It can either be a local image or an image URL from the internet. 

5. Follow the guidelines in the IPYNB file and insert URLS where necessary. 

6. To view the blurred results, open the temp folder and click on test.png.


