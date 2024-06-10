# Movement-recognition-DS-project
# Movement Recognition Data Science Project

## Overview

This project focuses on recognizing different types of human movements using machine learning techniques. The goal is to accurately classify movements based on sensor data, which has numerous applications in areas such as health monitoring, sports analytics, and human-computer interaction.

## Key Findings

1. **Data Collection and Preprocessing**:
   - The dataset used includes data of four types of movement such as idle, walking, stair, and running from accelerator.
   - Extensive preprocessing steps, such as normalization and feature extraction, were performed to prepare the data for modeling.

2. **Exploratory Data Analysis**:
   - Visualizations of the sensor data revealed distinct patterns corresponding to different types of movements.
   - Correlation analysis helped in understanding the relationships between different sensor readings.

3. **Modeling**:
   - Two machine learning models were trained: Decision Tree Classifier and Support Vector Machines (SVM).
   - Hyperparameter tuning was performed to optimize model performance.

4. **Evaluation**:
   - The best performing model was the Support Vector Machines with rbf kernel, achieving an accuracy of 99.8% and cross validation score of 98.6%.
   - Confusion matrix analysis showed that the model effectively distinguished between most movement types with minimal misclassification.


## Repository Structure
├── data
│ ├── idle
│ ├── running
│ ├── stairs
│ └── walking
├── Final project.ipynb
├── README.md
└── requirements.txt

## Getting Started

### Prerequisites

- Python 3.8+
- Required libraries are listed in `requirements.txt`.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/TianaLina/Movement-recognition-DS-project.git
   cd Movement-recognition-DS-project
2. Install dependencies
   pip install -r requirements.txt
## Usage
Run "Final project.ipynb" and enjoy :)

## Results
The Support Vector Machine was the top performer with an accuracy of 99%, effectively classifying various human movements. Detailed evaluation metrics and visualizations are available in the final project notebook.

## Contact
For any questions or suggestions, feel free to contact me at [t.dulina62@gmail.com].


