# Siamese Facial Recognition

## Description

This project is aimed at building a Siamese Neural Network for facial recognition using TensorFlow and OpenCV. The Siamese architecture is particularly useful for tasks involving verification or identification of objects that don't fall into distinct categories. In this case, we're focusing on facial recognition, where we want to determine whether two facial images belong to the same person or not.

## Features

- Collect positive and negative image pairs for training
- Implement a Siamese Neural Network for learning embeddings
- Train the model to recognize similarities between facial images
- Evaluate the model's performance on a test dataset
- Provide utilities to capture images from a webcam for dataset collection

## Dependencies

- Python 3.x
- TensorFlow
- OpenCV
- Matplotlib

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git

   ## Usage

### Capture images to build the dataset:
- Run the script `collect_images.py` to capture positive and negative image pairs. Use 'a' to capture an anchor image, 'p' for a positive image, and 'q' to quit.
- Ensure that you capture enough images to build a diverse dataset for training.

### Train the Siamese Neural Network:
- Run the script `train.py` to train the Siamese network using the collected dataset.
- Adjust hyperparameters and network architecture as needed for better performance.

### Evaluate the model:
- Use the test dataset to evaluate the performance of the trained model.
- Run the script `evaluate.py` to assess the model's accuracy and other metrics.

## Credits

- This project was inspired by [reference to the original work, if any].

## License

[Include the license information here.]

## Contributors

- Prathamesh Bhaskar, Anup Ghunawat

