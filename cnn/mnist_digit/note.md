# Vanilla CNN Note 🍦🏞️
- The most fundamental practice for CNN is handwritten digit classification, therefore, we'll be using this dataset for our very very first exploration in detail!

## Dataset 📖
MNIST handwritten digit dataset (source: https://docs.pytorch.org/vision/main/generated/torchvision.datasets.MNIST.html)

| Data Set | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| -------- | -------- | -------- |
| Train Set  | 5923  | 6742 | 5958 | 6131 | 5842 | 5421 | 5918 | 6265 | 5851 | 5949 |
| Test Set  | 980 | 1135 | 1032 | 1010 | 982 |  892 | 958 | 1028 | 974 | 1009 |

The data consists of the 28 * 28 image (which get converted to tensor) and its label

## Architecture 🏗️
in our CNN model, we'll divide the architecture in 2 separate module instead, for simplicity:
1. **The Convolution Operation Module**
   -
2. **The Classification Module**
