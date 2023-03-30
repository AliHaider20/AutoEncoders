Used 5 layered Complete AutoEncoder to extract image of size (3x256x256) features in the latent space of (3x16x16) and used that latent features to classify teat images using SVC which reached accuracy of 58% with just 10 epochs.


Future scope:

1. Adding a regressor Convolution layer to add weights in the latent space.
2. Use Variational AutoEncoder which is more powerful than a complete AC which uses mean and std to learn the latent space.
