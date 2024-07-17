# VQA-final-home-work
Tokyo University DL lesson final project-VQA
----------------------------------------------
Description
----------------------------------------------
This project utilizes VisualBERT for training a Visual Question Answering (VQA) model. Due to the large size of the dataset, the training and validation data are not included in this repository. Only the JSON data package for VQA is provided. The training data was not placed in the data folder because the training was conducted on Google Colab and the data was stored locally for faster access. Therefore, make sure to modify the dataset paths in the main.py file before running the script.

Data
-----------------------------------------------
Due to the large file size, the training and validation datasets are not uploaded. Only the VQA JSON data package is included. During training, the data was stored locally to optimize read speeds, especially when running in Google Colab. Therefore, please ensure you update the dataset paths in the main.py file before executing it.

Pre-trained Model Loading
-----------------------------------------------
This project uses the VisualBERT pre-trained model for training. Specifically, the VisualBERT-vqa config.json and bert config.json are required. Ensure these files are correctly downloaded and loaded by the functions in main.py before running the script.


Model Loading
-----------------------------------------------
The uploaded model version has been trained for at least 50 epochs. Ensure that main.py correctly reads model.pth during execution.


Contact Information
--------------------------------------------------
For any questions or inquiries, please contact me at: sunkaiqing527@gmail.com
