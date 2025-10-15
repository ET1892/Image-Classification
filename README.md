### CIFAR10 Image Classification

This project focuses on classifying images from the CIFAR10 dataset using a Convolutional Neural Network (CNN). The goal is to build a model capable of recognising 10 classes of objects and animals, evaluate its performance, and visualise the learning process.

**Key Features:**
- Classifies 10 different classes of images including animals, vehicles, and everyday objects.
- Visualises training progress with accuracy graphs over epochs.
- Evaluates the model on test images and provides confidence predictions.
- Summarises accuracy per class in a clear table for analysis.

**Technical Stack:**
- **Frontend:** (Julia)
- **Backend:** Julia, using the Flux.jl library for machine learning.
- **Dataset:** CIFAR10.
- **Machine Learning:** Convolutional Neural Network with convolutional, pooling, and dense layers.
- **Evaluation & Visualisation:** Accuracy graphs over 100 epochs, test prediction examples, class-wise accuracy table.

**Project Highlights:**
- Test predictions are visualised with confidence indicators (e.g., correctly identifying a frog image).
- Accuracy table shows model performance across all CIFAR10 classes, helping identify strengths and weaknesses.
- Provides a foundation for more advanced image recognition tasks and experimentation with CNN architectures.

**Lessons Learned:**
- Working with CIFAR10 provides a good balance of dataset size and complexity for learning CNNs.
- Analysing misclassifications helps refine model design and training strategies.
- Future improvements could include deeper networks, data augmentation, and advanced regularisation techniques.

**Repository:**  
- [GitHub Link](https://github.com/ET1892/CIFAR10-Classification)

This project demonstrates the process of training and evaluating a CNN on a real-world image classification dataset and visualising the results for insight and analysis.
