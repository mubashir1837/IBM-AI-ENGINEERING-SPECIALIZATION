# IBM AI Engineering Project

A comprehensive project focused on Artificial Neural Networks and machine learning applications for aircraft damage detection and classification.

## Project Overview

This repository contains two main components:

### 1. Artificial Neural Networks (ANN)
An educational notebook demonstrating the fundamentals of building neural networks from scratch, including:
- Network architecture design
- Forward propagation implementation
- Weighted sum computation at each node
- Node activation functions
- Complete prediction pipeline

### 2. Final Project: Classification and Captioning Aircraft Damage
An advanced machine learning project using pretrained models to:
- **Classify** aircraft damage into two categories: "dent" and "crack"
- **Generate captions** and summaries of aircraft damage images using Transformer-based models

#### Key Features:
- Feature extraction using VGG16 pretrained model
- Automated aircraft damage detection
- Natural language generation for damage descriptions
- Real-world applicable damage detection system

## Dataset

The project uses the [Aircraft Damage Detection Dataset](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/ZjXM4RKxlBK9__ZjHBLl5A/aircraft-damage-dataset-v1.tar) from Roboflow.

**License:** CC BY 4.0

## Requirements

All project dependencies are listed in `requirements.txt`. The project uses:
- NumPy for numerical computations
- Jupyter/IPython for interactive notebooks
- Deep learning frameworks (specified in notebooks)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd IBM-AI-ENGINEERING
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the notebooks:
```bash
jupyter notebook
```

Then open either:
- `Artificial Neural Networks.ipynb` - to learn ANN fundamentals
- `Final-Project-Classification-and-Captioning-v1.ipynb` - to see the aircraft damage classification project

## Project Structure

```
IBM-AI-ENGINEERING/
├── Artificial Neural Networks.ipynb           # Educational ANN notebook
├── Final-Project-Classification-and-Captioning-v1.ipynb  # Main classification project
├── requirements.txt                           # Project dependencies
└── README.md                                  # This file
```

## Usage

### Running the ANN Notebook
The `Artificial Neural Networks.ipynb` walks through building a neural network from scratch and understanding how forward propagation works. This is great for learning the fundamentals.

### Running the Final Project
The `Final-Project-Classification-and-Captioning-v1.ipynb` contains:
1. **Part 1** - Classification Problem (classify damage as 'dent' or 'crack')
2. **Part 2** - Image captioning and summarization (generate descriptions of damage)

## Learning Outcomes

By completing this project, you will understand:
- How neural networks work at a fundamental level
- Feature extraction using pretrained models (VGG16)
- Transfer learning for image classification
- Natural language generation with Transformers
- End-to-end machine learning pipeline implementation

## License

This project includes materials from IBM Skills Network and uses the Roboflow Aircraft Dataset (CC BY 4.0).

## Notes

- This project is part of the IBM AI Engineering specialization on Coursera
- All notebooks are designed to be run in Jupyter environments
- Required datasets and models are downloaded/generated during notebook execution

---

For more information on the original courses and materials, visit [IBM Skills Network](https://skills.network/).
