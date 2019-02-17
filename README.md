# Face Generation

## Project Overview

In this project, I have built and trained a DCGAN on a dataset of human faces. The goal of this project is to get a generator network to generate new images of faces that look as realistic as possble. Check the images at the end of the notebook to see the final results

## Project Instruction

### Instruction

1. Clone the repository and navigage to the downloaded folder.
	```
		git clone https://github.com/eswar3/face-generation-using-GAN.git
		cd face-generation-using-GAN
	```
2. Open the `face_generation.ipynb` file. Of course, you can find HTML version of the file.
	```
		jupyter notebook face_generation.ipynb
	```
3. Read and follow the instructions in the jupyter notebook.

4. This repository does not include the dataset of faces. You can find the instruction in notebook on how to downlaod it.

## Project Information

### Contents

- Pre-processed Data
- Define the Model
	- Discriminator
	- Generator
	- Build complete network
- Discriminator and Generator Losses
- Optimizers
- Training
- Generator samples from training

### Libraries

- [tensorflow](https://www.tensorflow.org/) (Generator and Discriminator)

### Accelerating the Training Process

For training the model I recommend you to use a GPU.

### Amazon Web Services

You can use Amazon Web Services to launch an EC2 GPU instance. (This costs money!)
