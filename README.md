# ARI2129-Group-Project-Part-B

This project focuses on the use of data augmentation techniques with popular machine learning frameworks, including TensorFlow, PyTorch, and OpenCV. Data augmentation is an essential step in the preprocessing pipeline of machine learning models, particularly for image classification tasks, because it improves model generalization by artificially expanding the training dataset.

## Introduction

### Question 3: Data Augmentation in Mainstream Machine Learning Frameworks
In Question 3, we look at how data augmentation is implemented with two popular machine learning (ML) frameworks: TensorFlow and PyTorch. The ImageDataGenerator class in TensorFlow allows for the application of a variety of image transformations. Similarly, PyTorch includes the transforms module, which enables advanced image manipulation techniques. By applying these tools to the COTS dataset, we show how effective each framework is at generating augmented data. The task entails creating Jupyter Notebooks for both frameworks, and producing multiple augmented images per input. The results are then saved and analyzed using comparative metrics to determine the differences with the original images.

### Question 4: Implementing Data Augmentation Techniques Using OpenCV
In Question 4, we look at how to implement data augmentation techniques with OpenCV. Unlike TensorFlow and PyTorch, OpenCV requires a more manual approach to transformations. This question addresses both photometric and geometric distortions, including brightness variation, contrast adjustment, rotation, saturation, shearing and translation. We use these techniques on the same subset of the COTS dataset as in Question 3, resulting in multiple augmented images per input. The goal is to compare OpenCV results to TensorFlow and PyTorch results, which will provide insights into the practical application and effectiveness of custom augmentation implementations.

## Motivation:

Data augmentation is an important technique in the field of machine learning, especially for image classification. It entails creating new training examples by applying various transformations to the original dataset, thereby increasing its size and variability without collecting additional data. This process improves the generalization capabilities of machine learning models, making them more resistant to variations in input data and less prone to overfitting.

## Getting Started

### Prerequisites

- Python 3.x
- Python libraries: `os`, `cv2`, `matplotlib`, `numpy`, `ImageDataGenerator`, `Image from PIL`, `shutil`, `re`, `pandas` & `seaborn` [TO ADD THOMAS]
- Important libraries (auto-install): `tensorflow` & `structural_similarity from skimage.metrics`

### Installation

Clone the repository:
   ```
   git clone https://github.com/AFLucas-UOM/ARI2129-Group-Project-Part-B.git
   ```

## Usage

1. Navigate to the project directory:
   ```bash
   cd ARI2129-Group-Project-Part-B
   ```

2. For Question 3, open the Jupyter Notebooks for TensorFlow and PyTorch:
   ```bash
   jupyter notebook "Question 3/1. TensorFlow/Q3-a.ipynb"
   jupyter notebook "Question 3/2. PyTorch/Q3-b.ipynb"
   ```

3. For Question 4, open the Jupyter Notebook for OpenCV:
   ```bash
   jupyter notebook "Question 4/1. JupyterNotebook & PDF/Q4.ipynb"
   ```

4. Follow the instructions in each notebook to run the cells and generate augmented images.

## Additional Resources

- [TensorFlow Documentation](https://www.tensorflow.org/)
- [PyTorch Documentation](https://pytorch.org/)
- [OpenCV Documentation](https://opencv.org/)
- [COTS Dataset Paper](https://github.com/dylanseychell/COTSDataset/)

## Acknowledgments

This project was developed as part of an academic assignment. Unit: `ARI2129` at the `University of Malta`.

## Distribution of Work

- TensorFlow implementation (question 3-a): [Andrea Filiberto Lucas](mailto:andrea.f.lucas.22@um.edu.mt)]
- PyTorch implementation (questions 3-b): [Thomas Koppens](mailto:thomas.koppens.22@um.edu.mt)
- OpenCV implementation (question 4): [Sean David Muscat](mailto:sean.muscat.22@um.edu.mt)]


## Contact

For any inquiries or feedback, please contact [Andrea Filiberto Lucas](mailto:andrea.f.lucas.22@um.edu.mt), [Sean David Muscat](mailto:sean.muscat.22@um.edu.mt) & [Thomas Koppens](mailto:thomas.koppens.22@um.edu.mt)