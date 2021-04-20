# dark-image-enhancement
A deep convolutional autoencoder (with skip connections) solution to enhance dark and noisy images

Optimized for cityscape dataset input images, with added gaussian noise. Find out more [here](https://github.com/silvia-lara/dark-image-enhancement/blob/master/printing_mod_capstone.pdf).

## Results on Cityscape Dataset
Given a picture with artificial noise and darkening (Noisy), our UNET architecture recovers the original image (Original) with much higher fidelity than other State Of The Art models:

![Screenshot 2021-04-20 at 10 13 29 AM](https://user-images.githubusercontent.com/62934649/115327290-3d0db280-a1c1-11eb-9bb9-9ad2b715ef0c.png)

## Results on MNIST
The result is even more evident in the case of the MNIST dataset.

[Our method](https://github.com/silvia-lara/dark-image-enhancement/blob/master/printing_mod_capstone.pdf):

![Screenshot 2021-04-20 at 10 17 47 AM](https://user-images.githubusercontent.com/62934649/115327585-c91fda00-a1c1-11eb-811b-84c8bbf595b8.png)


[LIME](https://sites.google.com/view/xjguo/lime):

![Screenshot 2021-04-20 at 10 17 55 AM](https://user-images.githubusercontent.com/62934649/115327575-c6bd8000-a1c1-11eb-999b-ba81f16234dd.png)
