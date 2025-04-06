# Name : Jayadev Goksula
## Question 1 : Implementing a Basic Autoencoder
- Load MNIST Data: The dataset is loaded and normalized to have pixel values between 0 and 1.
- Define Autoencoder Model:
  - Encoder: Compresses the image into a lower-dimensional representation (latent space).
  - Decoder: Reconstructs the image from the latent space.
- Train the Autoencoder: The autoencoder is trained using binary cross-entropy loss with the original MNIST images as both input and target.
- Original vs. Reconstructed Images: The original and reconstructed images are displayed to visualize how well the model performs.
- Modify Latent Dimension: The latent space is modified to 16 dimensions, and the model is retrained. The effect of a smaller latent space on image reconstruction is analyzed.
