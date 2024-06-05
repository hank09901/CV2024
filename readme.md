<!-- This is a readme file for you to execute our code -->
# Readme
This is a readme file for you to execute our code.py

# 2024NTU Computer Vision Project-VIVOTEK

## Description

Briefly describe the purpose of the project and what it does.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Environment Setup](#environment-setup)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Prerequisites

List the software and hardware requirements. For example:

- Python 3.8.19
- Operating System: Linux
- (Any other specific requirements)

## Environment Setup

### Using Virtual Environment-Anaconda

1. **Create new conda environment:**
   ```bash
    conda create --name cv_final(you can choose the name you like) python=3.8.19
    conda activate cv_final(you can choose the name you like)
2. **Using python-V to check the version of python**
   ```bash
    python -V
3. **Install the required packages:**
    ```bash
     conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia

if torch cannot be installed, you should check out whether your cuda version is campatible with your torch version

4. **Go to correct directory**
    ```bash
     cd cv_final
5. **Run the code:**
    ```bash
     
     python3 algorithm_repeat_hank.py --weights crowdhuman_yolov5m.pt
6. **Get output.json in "./" directory**








