## Project Description
This project implements a **Convolutional Autoencoder** to denoise images that were intentionally corrupted with **Gaussian noise**.  
The autoencoder is trained by feeding it noisy images as input and learning to reconstruct the original clean images as output.  
This approach allows the model to capture image features while filtering out random noise.

---

## Input vs Noisy Images
Here is an example of a clean image and the same image after adding Gaussian noise:

**Clean Image & Noisy Image**
![Clean Image](/assets/AE2.png)

---

## Denoising Results
After training, the autoencoder can take noisy input images and reconstruct cleaner versions:

**Input (Noisy Data that Needs Denoising)**
![Noisy Input](/assets/AE3.png)

**Output (Denoised Result)**
![Denoised Image](/assets/AE3.png)

---

## Tech Stack
- **Python**
- **TensorFlow / Keras**
- **NumPy, Pandas**
- **OpenCV**
- **PIL** 
- **Matplotlib**
- **scikit-image**
