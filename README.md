# Training Convolutional Neural Networks to Categorize Clothing with PyTorch


## For my mom, this is how it works
- We teach the computer using labeled images
- we teach it how a shoe looks like, a sandal, a tee and so on
- this is our model
- We then test our model by making it predict labels of unlabeled images (our test dataset)
- we rank it's accuracy using labels that had been assigned to the test images manually
- its accuracy is how many labels it predicts correctly out of the total


**Getting started**
- Install pytorch using this official guide: https://pytorch.org/get-started/locally/
- Install Jupyter using this guide: https://jupyter.readthedocs.io/en/latest/install.html
- Open Terminal
- Run: `git clone https://github.com/SimiCode/MNSIT_Fashion_prediction.git`
- `cd` into cloned folder
- Run: `jupyter notebook`
- Selct Notebook and GO

Here are some of the images from the dataset we’ll be using to the train the network:
![Training data](https://cdn-images-1.medium.com/max/800/1*GLzztrL9GinZLuAzlhU8Fw.png)


## Results
The neural network should achieve an accuracy from 88%–90%, which is quite good compared to the 91.6% benchmark of 2-layered CNNs on the MNIST-Fashion dataset. Note that the MNIST-Fashion dataset is much harder to train on than the original MNIST-digit dataset. If we want to achieve a higher accuracy, we would have to add more layers, preprocess the data more to normalize it better, and increase the number of epochs.


Here’s some predictions made by the neural network: As you can see, the last prediction is wrong (such wrong predictions are what cause our accuracy to reduce).
![Predictions](https://cdn-images-1.medium.com/max/800/1*7vrz-IiO9C4rE5R0GQl7sA.png)


**Inspiration:** https://towardsdatascience.com/training-convolutional-neural-networks-to-categorize-clothing-with-pytorch-30b6d399f05f by Albert Lai
