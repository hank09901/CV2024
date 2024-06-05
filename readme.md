<!-- This is a readme file for you to execute our code -->
# Readme
This is a readme file for you to execute our final_code.py

# 2024NTU Computer Vision Project-VIVOTEK

## Description

Briefly describe the purpose of the project and what it does.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Environment Setup](#environment-setup)

## Prerequisites

List the software and hardware requirements. For example:

- Python 3.8.19
- Operating System: Linux
- (Any other specific requirements)

## Environment Setup
### Directory Structure

* Please put test videos parallel to the code.py as shown below.
![file_structure](https://github.com/hank09901/CV2024/blob/main/image/file_structure.png)
### Using Virtual Environment-Anaconda



1. **Go to correct directory**
    ```bash
     cd cv_final
2. **Create new conda environment:**
   ```bash
    conda env list
    conda create --name cv_final(you can choose the name you like) python=3.8.19
    conda activate cv_final(you can choose the name you like)
3. **Using python-V to check the version of python**
   ```bash
    python -V
4. **Install the required packages:**
    ```bash
     conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
     pip install -r requirements.txt

* If torch cannot be installed, you should check out whether your cuda version is campatible with your torch version
* Our cuda is 12.0 version


5. **Run the code:**
    ```bash
     
     python3 final_code.py --weights crowdhuman_yolov5m.pt

6. **Get output.json in "./" directory**









