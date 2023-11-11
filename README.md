#Pipeline for this project:-

Import TensorFlow and other libraries
Load the dataset
Build an input pipeline with tf.data
Build the generator
Define the generator loss
Build the discriminator
Define the discriminator loss
Define the optimizers and a checkpoint-saver
Generate images
Training
Restore the latest checkpoint and test the network
Generate some images using the test set


Pix2Pix Image to Image Translation With a Conditional GAN
• The dataset used for this project is the New York Facade Database, which contains a collection of facade images from various buildings in New York
City.
⚫ in order to train the model, a total of 1096 images were used, each with dimensions of 256x256x3 pixels.
• The Pix2Pix GAN network was employed for this project, which involved implementing an encoder-decoder model utilizing the U-net architecture for the generator model. 
The discriminator model utilized a PatchGAN architecture.
⚫ This involved designing and implementing the network architecture, training the model on the dataset, fine-tuning the model based on performance metrics, 
and using the trained model to generate new images from input images. Additionally, hyperparameter tuning 
and regularization techniques may have been employed to optimize the model's performance.
