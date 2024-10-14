# Tuberculosis Vision Scan

![Project Banner](./templates/tbscanlogo.jpg)


## Introduction

Tuberculosis (TB) is one of the leading causes of death worldwide. Early detection is crucial for successful treatment. This project uses deep learning to classify chest X-ray images to detect signs of tuberculosis. With an accuracy of 93.5%, this project demonstrates an efficient model for the automatic detection of TB from medical images.

## Project Overview

The **Tuberculosis Vision Scan** project leverages the **VGG16** deep learning architecture to classify X-ray images as either TB-positive or TB-negative. The project includes a complete end-to-end pipeline, from data preprocessing and model training to deployment on AWS with a robust MLOps setup.

## Key Features

- **Model Architecture:** Implemented VGG16 for image classification, fine-tuned for tuberculosis detection, achieving an accuracy of 93.5%.
  
- **Model Tracking & Logging:** Utilized MLflow and DagsHub for tracking experiments, logging models, and managing version control, ensuring efficient monitoring and reproducibility.

- **Pipeline Management:** Employed DVC (Data Version Control) for orchestrating data versioning and lightweight experiment tracking, facilitating smooth data management.

- **CI/CD Pipeline:** Automated deployment using AWS EC2, ECR, and GitHub Actions, ensuring smooth model updates and continuous integration with Docker containers.

- **Web Development:** Developed a Flask web application for real-time interaction with the model, allowing users to upload medical images and receive TB detection results in a user-friendly interface.


## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/VivekShinde7/Tuberculosis-Vision-Scan.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Tuberculosis-Vision-Scan
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Setup MLflow and DVC for experiment tracking and versioning.



## Workflows
1. update config.yaml
2. update secrets.yaml [optional]
3. update params.yaml
4. update the entity
5. update the configuration manager in src config
6. update the components
7. update the pipeline
8. update the main.py
9. update the dvc.yaml



## Future Work

- Improve model accuracy by experimenting with other deep learning architectures (e.g., ResNet, EfficientNet).
- Implement a more robust cross-validation scheme to evaluate the model's generalizability.
- Integrate explainability tools like SHAP or LIME to visualize model decisions.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
