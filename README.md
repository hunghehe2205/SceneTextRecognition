# STR (Scene Text Recognition) Project

## Overview

This project implements a **Scene Text Recognition (STR) pipeline** consisting of **text detection** and **text recognition** stages. The goal is to extract and recognize text from images, which is useful for applications like OCR (Optical Character Recognition) and automated document analysis.

## Project Structure

The project is organized into the following Jupyter notebooks:

1. **STR\_Full.ipynb** - This notebook is for inferencing
2. **STR\_Detection.ipynb** - Dedicated to detecting text regions in images.
3. **STR\_Recognition.ipynb** - Focuses on recognizing text from detected regions.

## Dataset
I use icdar2003 for this task.

## Model Arch
The project uses **Convolutional Recurrent Neural Networks (CRNN)** for text recognition which use ResNet34 as pre-trained model and GRU in RNN.
In terms of detecting, I use YOLOv11

