INTRODUCTION: - 
Fashion Recommender System is a Project based on ML Recommendation Systems.
Almost all big tech companies nowadays, uses this method to make UI more accessible, like, Amazon, Myntra, UrbanClab, other e - commerce platforms.

WORKING (A BRIEF IDEA)
It uses fashion product images as input.
Through inputs, the project uses CNN to extract required parameters and converts it into multi-dimensional vectors.
As, we are using pre-trained model like ResNet50, it enhances our model accuracy in order to feature extraction and feature selection.
these multi-dimensional vectors are subject to be projected on multi-dimensional space. through which, we uses eucleadean distance to figure out the closest resemblence fashion product.
on the basis of this eucledean distance method, we recommend at most 5 fashion product from our almost 90k dataset of fashion products.

FUTURE SCOPE: - 
This Project is 90% Backend driven and rest 10% Frintend. But in Future scope, i will try to make it more User - friendly and accessible to all users.

Technology Stack: - 
  1) CNN - convolution Neural Network (Deep Learning model)
  2) tensorflow 2.16.1 - Python Library
  3) ResNet50 - pre-trained model on imageNET.
  4) python - 3.11.1

Get Started Steps: -
 Step 1) Download all zip file and extract it into your local system and download pre-requisite modules, such as tensorflow, streamlit, etc... in terminal
           pip install python streamlit
 Step 2) Type in terminal window 'streamlit run server.py'
 Step 3) Here you go, enjoy 
