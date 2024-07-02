# PyTorch Image Prediction System

This repository contains a simple PyTorch-based image prediction system. It demonstrates how to use a pre-trained AlexNet model from torchvision to classify an image from the web.

## Features

- **Image Download**: Downloads an image from a given URL.
- **Image Preprocessing**: Applies necessary transformations to prepare the image for the model.
- **Model Loading**: Uses a pre-trained AlexNet model.
- **Inference**: Predicts the class of the image and provides the top-5 class probabilities.
- **Visualization**: Displays the input image and prediction results.

## Requirements

- Python 3.6+
- PyTorch 1.6+
- torchvision 0.7+
- numpy
- matplotlib
- PIL

## Installation

```bash
git clone https://github.com/xPoleStarx/pytorch-image-predict.git
cd pytorch-image-predict
```
## Example Output

The system will output the predicted class for the input image along with the prediction confidence. Additionally, it will display the top-5 class predictions with their respective probabilities.

```shell
Predicted Class: Border collie
Confidence: 23.63%

Top-5 Predictions:
1. Border collie - 23.63%
2. English springer, English springer spaniel - 7.99%
3. Saluki, gazelle hound - 5.92%
4. Collie - 5.38%
5. Boston bull, Boston terrier - 3.76%
