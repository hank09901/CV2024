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

* Please put test videos parallel to the final_code.py as shown below.
![file_structure](https://github.com/hank09901/CV2024/blob/main/image/file_structure.png)
### Using Virtual Environment-Anaconda



1. **Go to correct directory**
    ```bash
     cd B10901142
2. **Download Checkpoint of yolov5 person/head pretrained model from the following link below and put it in the "./B10901142" Directory**
    ```bash
     [crowdhuman_yolov5m.pt](<https://drive.google.com/file/d/16V7D0R6tyhW-2ia1juipeEsjgG0I7N-Z/view?usp=sharing>)
* The checkpoint is crowdhuman_yolov5m.pt which should be put in the same directory as final_code.py as shown in "Directory Structure" above
3. **Create new conda environment:**
   ```bash
    conda env list
    conda create --name cv_final(you can choose the name you like) python=3.8.19
    conda activate cv_final(you can choose the name you like)
4. **Using python-V to check the version of python**
   ```bash
    python -V
5. **Install the required packages:**
    ```bash
     conda install pytorch torchvision torchaudio pytorch-cuda=12.1 -c pytorch -c nvidia
     pip install -r requirements.txt

* If torch cannot be installed, you should check out whether your cuda version is campatible with your torch version
* Our cuda is 12.0 version


6. **Run the code:**
    ```bash
     
     python3 final_code.py --weights crowdhuman_yolov5m.pt
* crowdhuman_yolov5m.pt is the checkpoint of yolov5 person/head pre-trained model 
7. **Get output.json in "./" directory**









