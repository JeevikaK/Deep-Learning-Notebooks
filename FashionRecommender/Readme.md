<h1>Fashion Recommender</h1>
<p>This project involves training Convolutional Neural Networks (CNN) to classify images from the Fashion MNIST dataset using a three-layer and four-layer model. The goal is to predict clothing items and suggest complementary items for fashion recommendations.</p>

## Requirements
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- OpenCV
- Matplotlib

Install the required dependencies by running:
```bash
pip install tensorflow numpy pandas scikit-learn opencv-python matplotlib

## Setup

1. Clone the repository and install dependencies:

    ```bash
    git clone <repository_url>
    cd <repository_directory>
    pip install -r requirements.txt
    ```

2. Prepare the Fashion MNIST dataset: Download and extract the Fashion MNIST dataset to the `dataset/` folder. You can download it from [here](https://github.com/zalandoresearch/fashion-mnist).

## Model Architectures

### Three-Layer CNN Model

The three-layer CNN includes:

- **Conv2D** (32 filters, 3x3 kernel)
- **MaxPooling2D** (2x2 pooling)
- **Dropout** (0.25 rate)

The model is compiled using `categorical_crossentropy` loss and the `Adam` optimizer.

### Four-Layer CNN Model (Not Implemented in Code Example)

The four-layer CNN includes an additional **Conv2D** layer for increased depth, offering more feature extraction.

