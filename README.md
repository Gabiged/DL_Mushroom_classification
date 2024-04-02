# DL_Mushroom_classification

Know Your Mushrooms
The aim of this work is to develop a model to help identify a variety of mushrooms.

The idea of this project is to use transfer learning on an architecture of our choice and fine-tune it to achieve the best results.

I will use this Kaggle dataset https://www.kaggle.com/maysee/mushrooms-classification-common-genuss-images

As my model I choose ResNet18. It is a convolutional neural network that is 18 layers deep. The pretrained version of the network trained on more than a million images from the ImageNet database. The pretrained network can classify images into 1000 object categories.

This work is based on 6,714 images that identify 9 mushrooms families;

Images in the dataset are not of the same sizes, which will require their unification for further work.
EDA part is in the file mushroom_EDA.ipynb. The problem is the dataset size limitations, so after unzipping initial dataset I have created separate subfolders for training, validation and testing.
The modeling part is in the file mushroom_model.ipynb
