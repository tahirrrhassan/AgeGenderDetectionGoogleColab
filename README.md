# Age & Gender Detection using Google Colab

[![Python application](https://github.com/tahirrrhassan/AgeGenderDetectionGoogleColab/actions/workflows/ci.yml/badge.svg)](https://github.com/tahirrrhassan/AgeGenderDetectionGoogleColab/actions/workflows/ci.yml) [![Version](https://img.shields.io/badge/version-1.0.0-blue)](https://github.com/tahirrrhassan/AgeGenderDetectionGoogleColab) [![License](https://img.shields.io/badge/license-GPL%203.0-blue)](https://github.com/tahirrrhassan/AgeGenderDetectionGoogleColab) [![Quality](https://img.shields.io/badge/quality-A%2B-brightgreen)](https://github.com/tahirrrhassan/AgeGenderDetectionGoogleColab)

This project includes a Jupyter Notebook designed for tasks related to detection, analysis, or processing workflows. The notebook provides step-by-step code and explanations to execute the specified detection operations effectively. Realtime Age and Gender detection using Open CV and pre-trained models through Google Colab.

## Age Detection Model:
age_deploy.prototxt | modelNweight/age_net.caffemodel

## Gender Detection Model:
gender_deploy.prototxt | gender_net.caffemodel

## OpenCV Face Detection Model:
opencv_face_detector.pbtxt | opencv_face_detector_uint8.pb

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Comprehensive Workflow**: Includes all necessary steps for data preprocessing, model training, and evaluation.
- **Customizable**: Easy to modify for specific detection tasks.
- **Visualization**: Provides clear visualizations for analysis.

## Installation

To use this notebook, ensure you have the following installed:

1. **Python (3.8 or later)**
2. **Jupyter Notebook or JupyterLab**

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

### Optional Setup
If a `requirements.txt` file is not provided, the key libraries to install include:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow keras
```

## Usage

1. Clone the repository:
   ```bash
   git clone "https://github.com/tahirrrhassan/AgeGenderDetectionGoogleColab/"
   cd AgeGenderDetectionGoogleColab/
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open the notebook file (`detection.ipynb`) and run the cells sequentially. Make sure to adjust paths or parameters if needed.

### Input Data
Ensure the input data is placed in the correct directory as specified in the notebook. The format and structure of the input data will be described within the notebook itself.

### Outputs
Results, including metrics and visualizations, will be generated and saved in the specified output folders.

## License
This project is licensed under the GPL License. See the `LICENSE` file for more details.
All the pre-trained models was downloaded from the link below: https://drive.google.com/uc?id=1_aDScOvBeBLCn_iv0oxSO8X1ySQpSbIS
