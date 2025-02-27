# TrafficSignRecognition

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)

## Description

TrafficSignRecognition is an image recognition project that leverages transfer learning to identify European traffic signs. The project is implemented using Jupyter Notebooks and aims to provide a robust model for recognizing various traffic signs.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)

## Installation

To get started with the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/imgmaterial/TrafficSignRecognition.git
    cd TrafficSignRecognition
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Project Structure

```
TrafficSignRecognition/
├── dataset/                # Contains unpacked GTSRB dataset
├── processed_data/         # Contains the processed GTSRB images for model training
├── main.ipynb/             # The main notebook for dataprocessing and model training      
├── requirements.txt        # Project dependencies
└── README.md               # Project documentation
```
