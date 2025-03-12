# Anime Face Generation using GAN

This project focuses on generating anime faces using Generative Adversarial Networks (GAN). The dataset used is the [Anime Face Dataset](https://www.kaggle.com/datasets/splcher/animefacedataset) from Kaggle, which contains a collection of anime face images.

## Project Structure

The project is organized as follows:

root
|
|-- anime_images
|   |
|   |-- images
|   |   |
|   |   |-- 0_2000.jpg
|   |   |-- 1_2000.jpg
|   |   |-- ...
|
|-- generated
|
|-- main.ipynb
|
|-- README.md



# Environment Setup

Follow the steps below to set up a Conda environment for running GAN models with PyTorch.

```bash
conda create --name gan python==3.10.14
conda activate gan
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126
pip install matplotlib tqdm ipywidgets
```