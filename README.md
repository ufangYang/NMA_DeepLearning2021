
# Project
## "Comparison of several deep models in the classification of music genres" 
### by Ali Darzi, Yu-Fang Yang, Yaxin Liu, Jelena Sucevic

Abstract : 

While Convolutional Neural Networks (CNNs) are widely used for image classification, they show promise for audio signal processing as well. Music genre classification, which is the core of the music recommender systems, can benefit from such models. Previous research (Choi et al., 2017) has shown that music classification can take advantage of CNNs’ extraction of features.  In this project, we thus compare the classification performance of three models: 1) a simple CNN; 2) a pretrained ResNet, and 3) a recently introduced model, the multi-layer perceptrons (MLP)-mixer  (Toistikhin et al., 2021). The GZTAN dataset, consisting of 1000 music clips (each 30-second long) in 10 genres is used in this study, while they are fed into the deep neural network models after mel-spectrogram transformation. We hypothesize that while the MLP-mixer, pretrained CNN, and a simple CNN are well suited for the classification of the music data, they will result in the most accurate to the least accurate models, respectively. The preliminary results show that the models pretrained on the ImageNet perform better than the simple CNN models. This shows that, despite pretraining on natural images, there is a transfer learning to mel-spectrogram classification, suggesting that utilization of the extraction of basic features in one domain can be useful for feature detection in other modalities. In addition, the pretrained model with fewer hidden layers (ResNet 18) was more accurate than the deeper Network (ResNet 34). For future works, we expect the accuracy in the classification of music genres will be higher using MLP-mixer than pretrained ResNet18 CNN. 

<img width="977" alt="image" src="https://user-images.githubusercontent.com/33165978/135158570-733d9c77-bd19-4fbe-819f-4bfa3537c9af.png">
<img width="977" alt="image" src="https://user-images.githubusercontent.com/33165978/135158583-1fc2bc87-cbf7-4686-b9ee-9baccad032d0.png">
<img width="977" alt="image" src="https://user-images.githubusercontent.com/33165978/135158604-0adf3e22-5b88-4fb7-b15a-8111947497ae.png">
<img width="977" alt="image" src="https://user-images.githubusercontent.com/33165978/135158613-2f48ebd5-df71-465b-b3f5-7a2a4ff0db2a.png">


