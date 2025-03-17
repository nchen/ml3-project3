# Histopathologic Cancer Detection

This project work is to solve the Kaggle problem: <https://www.kaggle.com/competitions/histopathologic-cancer-detection/overview>

## Environment Setup: Make sure that Tensorflow is using the correct GPU

I am using a Alienware x14 laptop for this project, with a `NVIDIA GeForce RTX 3060 Laptop GPU` installed. Operation system is Windows 11.

At first, when running the model, I saw from the Windows system's task manager that the Tensorflow seems not be using my Nvidia GPU, but instead it could be using another builtin video adapter called `Intel(R) Iris(R) Xe Graphics`, which is quite weak, so I tried for figure out how to configure Tensorflow to use my NVIDIA GeForce GPU.

The final workable software versions are the following:

- pyenv-win
- Python 3.10.5
- tensorflow 2.10.0
- CUDA 11.2.2
- cuDNN 8.1.1
- `numpy<2`

## Note

The training and testing datasets are not included because it's too large.

You can go to Kaggle website to download the data.
