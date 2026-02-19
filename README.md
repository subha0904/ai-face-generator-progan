# Synthetic Face Generation using ProGAN

This project demonstrates the use of a pretrained **Progressive Growing GAN (ProGAN)** model from **TensorFlow Hub** to generate realistic synthetic human face images.
A randomly sampled latent noise vector is provided as input to the generator, and the resulting face image is saved locally as an output file.

# Key Features

- Generates synthetic face images using a pretrained GAN model  
- Uses TensorFlow Hub for easy model loading  
- Automatically saves the generated image as `new_face.png`  
- Simple implementation suitable for learning GAN fundamentals  


## Tech Stack

- Python  
- TensorFlow  
- TensorFlow Hub  
- NumPy  
- Pillow (PIL)  

## Installation

Install the required dependencies:

```bash
pip install tensorflow tensorflow-hub numpy pillow
