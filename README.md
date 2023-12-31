# Video Enhancement 

This project focuses on enhancing the resolution of videos using super-resolution techniques. It utilizes a deep learning model to upscale low-resolution frames, resulting in improved visual quality.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Parameters](#parameters)
- [Contributing](#contributing)

## Introduction
Video enhancement through super-resolution is crucial for applications requiring higher visual fidelity. This project employs a deep learning approach to enhance video resolution by upscaling individual frames using a pre-trained model.

The process involves the following key steps:
1. Load the input video and extract frames.
2. Apply super-resolution to each frame using a deep learning model.
3. Save the enhanced frames to an output video.

## Requirements
- Python 3.x
- PyTorch
- torchvision
- ESRGAN
- Architecture

## Installation
1. Clone the repository:

   ```bash
   git clone https://github.com/ManaskrJha/Enhance-Video-Quality.git 
   cd Enhance-Video-Quality

2. Download Real-ESRGAN

   Download the pre trained model from the following repository:
   
   ```bash
   git clone https://github.com/xinntao/Real-ESRGAN.git
   cd Real-ESRGAN

3. Download the architecture provided in files.

## Usage
1. Provide input video:
2. Adjust parameters as needed.
3. View the enhanced video in the specified output directory.

## Parameters

- input_video_path: Path to the input video file.
- output_video_path: Path to save the enhanced video.
- model_weights: Path to pre-trained model weights.

## Contributing
Contributions are welcome! If you find any bugs or have suggestions for improvements, please feel free to open an issue or submit a pull request.

