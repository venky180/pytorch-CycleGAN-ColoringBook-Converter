layout: page
title: "Coloring Book Generator"
permalink: /readme


## Project Name

CycleGAN Coloring Book Generator

## Description

The CycleGAN Coloring Book Generator is a project that employs the CycleGAN (Cycle-Consistent Generative Adversarial Network) architecture to transform normal photos into coloring book versions. By leveraging the power of CycleGAN, the project enables the conversion of images from one domain (normal photos) to another domain (coloring book line drawings) without the need for paired training data. The generator network learns to map images from the source domain to the target domain, while the discriminator network provides feedback to ensure the realism of the generated coloring book images. This project provides a user-friendly interface to facilitate the seamless generation of coloring book versions from user-supplied photographs.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [Dataset](#dataset)
- [Training](#training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To use this project locally, follow the steps below:

1. Clone the repository: `git clone https://github.com/venky180/pytorch-CycleGAN-ColoringBook-Converter.git
2. Install the required dependencies: `pip install -r requirements.txt`


## Features

- Conversion of normal photos into coloring book versions using CycleGAN.
- Training of the CycleGAN model on user-supplied datasets.
- User-friendly interface for seamless interaction and effortless generation of coloring book images.
- Real-time preview of the generated coloring book transformation.

## Technologies

The project is implemented using the following technologies:

- Python: Programming language used for development.
- PyTorch: Deep learning framework for training and implementing the CycleGAN model.
- Check Original Repo: https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix
- OpenCV: Library for image processing and manipulation.

## Dataset

The project requires a dataset of normal photos for training the CycleGAN model. The dataset should consist of unpaired images, containing only normal photos without corresponding coloring book line drawings. The dataset can be collected from various sources or created manually by gathering a diverse range of normal photos.

## Training

The project involves training the CycleGAN model on the unpaired dataset of normal photos. The `train_cyclegan.py` script handles the training process, including data loading, model configuration, and optimization.

## Results

The quality and realism of the generated coloring book images depend on the training data, model architecture, and the inherent characteristics of the input photos. The project aims to provide visually appealing coloring book versions that capture the essence and content of the original photos, bridging the gap between digital photography and traditional coloring activities.

## Contributing

Contributions to the project are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
