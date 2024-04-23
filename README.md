# IntruDetect: Intrusion Detection System Using Deep Learning
### CREATOR: Calvin Seamons (Computer Science BA, BYU)

This repository contains the code and documentation for a project aimed at developing a sophisticated Intrusion Detection System (IDS) utilizing deep learning to analyze network traffic and detect anomalies, unauthorized access, and malicious activities in real time. Our goal is to enhance network security with higher efficiency and reduced false positives compared to traditional IDS solutions.

## Project Goal

The primary objective is to create a robust IDS that leverages deep learning techniques to accurately identify potential threats, thereby significantly enhancing network security.

## Approach

### Data Collection and Preparation
- **Datasets Used**: UNSW-NB15, which offers labeled instances of normal and various types of attack activities.
- **Preprocessing**: Normalization of values, encoding of categorical variables, and handling of missing data.
- **Feature Selection**: Identification of relevant features that distinguish between normal and malicious traffic.

### Model Development
- **Architectures**: Implementation of an MLP Binary classifier, MLP multi-class classifier, etc
- **Training**: Models are trained on preprocessed data, with hyperparameter tuning based on grid search results.

### Evaluation Metrics
- **Metrics**: Accuracy, precision, recall, F1 score, and area under the ROC curve (AUC).
- **Detection Capabilities**: Focused on minimizing false positives and negatives to enhance reliability.

## Measures of Success

- **Detection Rate**: High success rate in identifying known and zero-day attacks.
- **False Positive/Negative Rates**: Minimization of false metrics to ensure real-world application feasibility.
- **Real-time Performance**: Capability to detect threats in real-time with minimal latency.
- **Scalability and Adaptability**: Ability to scale and adapt to new network environments and attack vectors.

## Available Resources

- **Datasets**: Access to UNSW-NB15 for model training.
- **Computational Resources**: GPUs available for efficient real-time analysis.
- **Software and Tools**: Deep learning frameworks like TensorFlow or PyTorch
- **Expertise**: Support from academic advisors and cybersecurity experts.

## Repository Structure

- `data_analysis.ipynb`: Notebook containing data preparation and exploratory analysis.
- `MLP_Binary_Classifier.ipynb`: Notebook with the implementation of a multi-layer perceptron binary classifier model.

## Getting Started

To get started with this project, clone the repository and install the required dependencies. Ensure you have access to the necessary datasets and computational resources.

```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your suggested changes.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---
