# Replicating Visual Question Answering (VQA) with OFA

This project aims to replicate the Visual Question Answering (VQA) task using the OFA (One-For-All) framework, specifically evaluating the performance of the OFA Base model. The goal is to reproduce the results reported in the OFA paper for the VQAv2 dataset.

## Project Structure

- **`main.ipynb`**: The primary script to load the OFA model, preprocess the VQAv2 dataset, and evaluate the VQA task.
- **`requirements.txt`**: Contains the dependencies required to run the project.

## Dataset

The VQA task in this project is evaluated on the **VQAv2 dataset**, as used in the OFA paper. The dataset includes:

- **Images**
- **Questions**
- **Answers**

For more details, visit the [VQAv2 dataset page](https://visualqa.org/).

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
2. **Install Dependencies**: Make sure you have Python 3.8 or later installed.

pip install -r requirements.txt


3. **Run the Evaluation**: Execute the main.ipynb script to preprocess the dataset and evaluate the OFA Base model on the VQA task.
python main.ipynb


Notes
Ensure that the transformers and datasets libraries are properly installed.
The preprocessing pipeline handles image resizing, tokenization, and loading ground-truth annotations.
References
OFA Paper: OFA: Unifying Architectures, Tasks, and Modalities Through a Simple Sequence-to-Sequence Learning Framework
VQAv2 Dataset: https://visualqa.org/
