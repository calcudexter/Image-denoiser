## Denoising Images with Deep Learning  
This repository contains a fully convolutional autoencoder for noise removal from images. Due to limited computational resources it contains model trained only for low resolutions, nevertheless, the same idea can be flawlessly extended to higher resolution domain. The pros of using deep learning is that it can be seamlessly applied to any kind of image if the training dataset is fine and it removes the need for hardcoding known techniques, namely wavelet transform, etc. into the model's working.  

### Results :  
 * **Grayscale : Dataset vs Noisy Samples** :  
 ![Pure vs Noisy](assets/img_comparison.png "Pure vs Noisy")  


 * **Grayscale : Noisy samples vs Reconstructed Images** :  
 ![Noisy vs Recon](assets/denoised_images.png "Noisy vs Reconstructed")


 * **Color : Original Image Reconstructions** :
 ![Reconstructions](assets/original.png "Reconstructions")  


 * **Color : Noise Removal** :
 ![Noise removed](assets/fine_tuned.png "Noise removed")

The reconstucted images shown above are blurred due to computational constraints on the model architecture.  
**PS** : The saved model can be found in ```model``` directory and it is recommended to run the code in ```Google Colab``` to prevent dangling dependencies.
