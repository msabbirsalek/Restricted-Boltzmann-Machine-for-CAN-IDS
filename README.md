# A Novel Hybrid Quantum-Classical CAN IDS

This repository contains the IPYNB scripts for a novel hybrid quantum-classical Controller Area Network (CAN) Intrusion Detection System (IDS). 
  - Decoding_using_OpenDBC.ipynb: This script is to be used for decoding CAN messages using the OpenDBC repository.
  - CNN_feature_extraction.ipynb: This script is to be used CAN image construction from decoded CAN messages and to extract features from the CAN images using a Classical Neural Network (CNN).
  - Train_RBM.ipynb: This script is to be used to train a quantum Restricted Bolztmann Machine (RBM) model to classify CAN images into normal (i.e., non-attack) CAN images and attck CAN images. The other necessary files to run this script can be found in the repository developed by Marek Subocz at https://github.com/mareksubocz/QRBM/tree/master/qrbm
