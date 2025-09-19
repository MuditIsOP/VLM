# Visual Question Answering (VQA) Project

## Overview
This project implements a Visual Question Answering (VQA) system using modern architectures like BLIP-2. The goal is to enable a model to answer questions based on visual inputs.

## Directory Structure
- `src/`: Contains the main source code for models, data processing, training, and evaluation.
- `requirements.txt`: Lists the Python dependencies required for the project.
- `config.yaml`: Configuration file for model and training parameters.
- `train.py`: Main script to train the VQA model.
- `inference.py`: Script to perform inference on new images and questions.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/MuditIsOP/VLM.git
   cd VLM
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage
- To train the model:
  ```
  python train.py
  ```

- To perform inference:
  ```
  python inference.py --image <image_path> --question <your_question>
  ```

## License
This project is licensed under the MIT License.
