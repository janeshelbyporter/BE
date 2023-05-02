Wireless capsule endoscopy (WCE) has become an irreplaceable tool for diagnostic inspection of the Gas- trointestinal (GI) tract. Accurate recognition of polyps in WCE images is a difficult task due to the complicated characteristics. Therefore, an automatic computer-aided diagnosis system is crucial to assist physicians to analyze and separate polyp images. We aim to develop an automated system for polyp detection in WCE images based on deep learning models which is an improvement to the neural network that contains more computational layers that allow for higher levels of abstraction and prediction in the data. We first present pre-trained VGG-16 model with the help of transfer learning approach for image classification problems in WCE images. We presented a comparison of four different methods to perform transfer learning using VGG-16 model. We have shown that transfer learning framework will be beneficial as it saves time of training the CNN models from scratch and can be vital in the field of medicine in the future. Also, we presented how VGG-16 could be used as a feature extraction tool to improve the performance of classical classifiers such as Random Forest and Support Vector Machine. At the end, we included a deep feature learning method, named stacked sparse autoencoder, to recognize polyps in the WCE images.

The code for each of these models can be found above. The four methods we used to retrain the VGG model can be found in: 
- BE_VGG16_Untrained.ipynb
- BE_VGG16_Haif-Trained.ipynb
- BE_VGG16_Block_Trained.ipynb
- BE_VGG16_Retrained.ipynb

BE_VGG16_Block_Trained.ipynb also contains the code for VGG-16 + SVM and VGG-16 + Random Forest.

Simple_SVM.ipynb and Simple_Random_Forest.ipynb show the performance of SVM and Random Forest Classifiers on the WCE dataset.

Autoencoder_Deep-Polyp-Copy2 is a preliminary version of an autoencoder for this dataset. Currently, it is not achieving the expected performance, but future studies hope to improve it. 
