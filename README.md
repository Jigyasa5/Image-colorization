# Image Colorization using Autoencoder 

## Project Overview

This project performs **Image Colorization** by converting grayscale images into color images using  **Autoencoder** .

---

## Features

- Convert grayscale images to color
- Autoencoder architecture
- Trained on COCO 2017 dataset
- Predict colors for new grayscale images
- Visualize input, predicted, and original images

---

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- KaggleHub
- Google Colab

---

## Dataset

**Dataset:** COCO 2017

The dataset contains thousands of real-world images used for training the autoencoder.

Download using:

```python
import kagglehub

path = kagglehub.dataset_download("awsaf49/coco-2017-dataset")
```

Dataset Structure:

```
coco2017/
│
├── train2017/
├── val2017/
└── test2017/
```

---
## Results

Results:

- Test Loss: **0.01**
- Test MAE: **0.067**

---

##  Output

The model generates:

```
Input (Grayscale)
        ↓
Autoencoder
        ↓
Predicted Color Image
        ↓
Comparison with Original Image
```



## Run the Project

1. Download the COCO 2017 dataset.
2. Load and preprocess images.
3. Train the autoencoder.
4. Save the trained model.
5. Test on new grayscale images.

---



## 📜 License

This project is intended for educational and learning purposes.
