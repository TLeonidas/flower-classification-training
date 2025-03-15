# Flower Classification Training - Deep Learning 🌸

This repository contains the full training process for a ResNet50-based model that classifies 102 species of flowers.

The model achieved **97.3% validation accuracy** on the Oxford 102 Flower Dataset.

## Project Overview
This project was originally developed as part of the AI Programming with Python Nanodegree by Udacity.  
It demonstrates the power of transfer learning by fine-tuning a ResNet50 and training a custom classifier to achieve high accuracy in flower species recognition.

## 📂 Repository Structure
| Folder/File               | Description |
|---------------------------|-------------|
| `flower-classification.ipynb` | Full training and evaluation notebook |
| `images/training_process.png` | Training loss/accuracy visualization |
| `images/confusion_matrix.png` | Confusion matrix visualization |
| `README.md`               | Project documentation |

## Dataset
The model was trained on the [Oxford 102 Flower Dataset](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html), a dataset containing images of 102 flower species.

## Training Process
- **Transfer Learning with ResNet50**
- **Custom Classifier Training:** Fully connected layers trained on top of ResNet50
- **Data Augmentation:** Resizing, cropping, normalization
- **Optimization:** Adam optimizer with CrossEntropyLoss
- **Evaluation:** Confusion matrix and accuracy metrics

## 📊 Model Performance
| Metric | Score |
|--------|------|
| **Validation Accuracy** | **97.3%** |
| **Training Loss** | **19.8%** |
| **Validation Loss** | **6.7%** |

**Confusion Matrix:**  
*(See `images/confusion_matrix.png` for detailed misclassification analysis.)*

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/TLeonidas/flower-classification-training.git

2. Open and run the flower-classification.ipynb notebook in Jupyter.

## Related Work
Inference Model Repository: [TLeonidas/uk-flower-classification](https://github.com/TLeonidas/uk-flower-classification)

## License
This project is open-source under the MIT License.
