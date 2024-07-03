IMPLEMENTATION OF DIFFUSION MODEL

specification: it takes one class (cars) of images from CIFAR10 dataset. The model is created using a UNet2DModel.
It is trained using a DDPM scheduler, a simple forward pass function, MSE loss function and Adam optimizer.
It is trained for 100 times.

results: we starts with a random noise and pass it to the trained model and a DDPM scheduler. We can see that the model successfully
transformes the image from 6 noise images to 6 different car iamges. 
