# Faces-GAN

A simple Generative Adversarial Network (GAN) for synthesizing human faces using the LFW (Labeled Faces in the Wild) dataset.

---

## Demo

### Generated Faces Over Time

**Epoch 10**  
![Faces at Epoch 10](Faces/face10.png)

**Epoch 250**  
![Faces at Epoch 250](Faces/face250.png)

**Epoch 500**  
![Faces at Epoch 500](Faces/face500.png)

**GIF of Generated Faces (Epochs 1–500)**  
![GIF of faces](https://github.com/nov8r/Faces-GAN/blob/main/Faces/Faces.gif)

---

## Features

- Uses the real LFW dataset (color images, resized to 64×64)
- Fully connected generator and discriminator (simple, non-DCGAN)
- Label smoothing for real images
- Dropout and batch normalization for stability
- Saves training images every 10 epochs
- Automatically creates a GIF to visualize progress over time

## Author

Project by **Ethan Posey**  
Original coursework: CSC 351: Machine Learning
