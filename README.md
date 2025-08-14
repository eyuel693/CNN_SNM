# Support Vector Machines (SVMs)

This repository compares three different approaches to MNIST digit classification:

- **A Support Vector Machine (SVM) classifier trained directly on raw pixel data**

- **A Convolutional Neural Network (CNN) trained end-to-end.**

- **A hybrid model that uses a CNN for feature extraction, followed by an SVM classifier.**

The experiments demonstrate that effective feature extraction is crucial for achieving high accuracy in image classification tasks. While SVMs trained on raw pixel data struggle due to their lack of spatial awareness, CNNs are highly effective at capturing hierarchical patterns directly from images. The combined approach of using CNN-based feature extraction with an SVM classifier yielded the best overall performance, confirming that leveraging deep learning for feature representation and classical machine learning for classification can produce superior results.







