# ASL Machine Learning Interpreter Application

Welcome to the repository of our ASL (American Sign Language) Machine Learning Interpreter application. This project is designed to recognize and interpret sign language from static images and live videos. 

## Repository Structure

The repository is structured as follows:

- **Model 1.ipynb**: This Jupyter notebook contains the model that classifies static images of ASL letters. The model was trained on the MNIST dataset for ASL. After running through all 35 epochs, we achieved a testing accuracy of 98.4%.

- **Model 2**: This directory contains 'Model 2.ipynb', a Jupyter notebook that classifies live videos of ASL signs (3 labels) from video data. It also has the functionality to generate sentences based on the past signs. The 'model_2_accuracy_96.1%' folder contains the saved model with a testing accuracy of 96.1%.

- **Model 3.ipynb**: This Jupyter notebook contains the model that classifies live videos of ASL letters (26 letters) from video data and has the ability to generate words or sentences. The 'model_3_accuracy_52%' folder contains the saved model with a testing accuracy of 52.31%.

- **sign-language-mnist**: This directory contains all the training data from the MNIST dataset that we used for 'Model 1.ipynb'.

- **MP_Data**: This directory contains the feature vectors that were obtained from extracting the keypoints from the latest model iteration.

- **Logs**: This directory contains all the logs of loss and accuracy metrics from our training sessions.

## Getting Started

To use this project, clone the repository to your local machine. Install the necessary dependencies (listed in the requirements.txt file) and execute the Jupyter notebooks ('Model 1.ipynb', 'Model 2.ipynb', and 'Model 3.ipynb').

Please note that due to the intensive computations required by the models, it is recommended to run the notebooks on a machine with a powerful GPU.

