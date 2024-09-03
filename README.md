# Black & White to Colored Image Conversion Using GANs

## Description
This project implements a Generative Adversarial Network (GAN) to convert grayscale images into colored images. The model combines U-Net and ResNet architectures and achieves highly realistic colorization. This approach offers a practical solution for various applications, including the enhancement of historical photographs and artistic image transformations.

## Technologies Used
- **TensorFlow**: Framework for building and training the GAN model.
- **Keras**: High-level API within TensorFlow for streamlined model development.
- **Python**: Programming language used for implementation.
- **NumPy & Pandas**: For data manipulation and preprocessing.
- **OpenCV**: For image processing tasks.
- **Matplotlib**: For visualizing training progress and colorization results.
- **L*a*b Color Space**: Used to represent the color channels for better image colorization.
- **Anaconda**: Environment management and package handling.
- **Jupyter Notebook**: For interactive development and experimentation.

## Features
- **Advanced GAN Architecture**: Utilizes a U-Net generator and a Patch Discriminator for effective image colorization.
- **Pretraining**: Incorporates ResNet-based pretraining to enhance colorization accuracy and reduce training time.
- **Loss Functions**: Combines GAN loss with L1 loss for more realistic and vibrant results.

## Getting Started
To run this project:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/gan-colorization.git
    ```

2. Navigate to the project directory and set up the environment:
    ```bash
    cd gan-colorization
    conda create --name gan-colorization python=3.8
    conda activate gan-colorization
    pip install -r requirements.txt
    ```

3. Prepare your grayscale image dataset and place it in the `data` directory.

4. Run the provided Jupyter Notebook or Python script to train and evaluate the model.

## Contribution
Contributions are welcome! Please feel free to open issues or submit pull requests.
