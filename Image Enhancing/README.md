# Purpose of Image Enhancing Project
Initially, an autoencoder program was created to remove noise in an image. Several CNNs were used in the architecture of the autoencoder. 
The neural network was then trained and tested on the MINST dataset. The results were acceptable. However, the quality of images is not only 
affected by noise but also by their resolution. Therefore, in the next project step, a Super Resolution Image Enhancer was programmed. 
This program works with a Generative Adversarial Network (GAN), which also uses CNNs and furthermore VGG19 for its architecture. GANs are relatively 
effective at correctly recovering/predicting lost information from pixels and thereby improving the resolution of an image. However, with my current hardware, 
it was not possible to train the GAN sufficiently, so image enhancement was limited. A future project could be to link the autoencoder and the Super Resolution program.
