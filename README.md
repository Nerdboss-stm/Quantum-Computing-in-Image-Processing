# Quantum Computing Applications in Digital Image Processing

## Introduction

This project explores the intersection of quantum computing and digital image processing. By utilizing quantum mechanics principles such as superposition and entanglement, it demonstrates the potential of quantum algorithms to improve image classification, compression, segmentation, and security. The research aims to address challenges associated with classical approaches and showcases innovative methods for efficient and accurate image processing.

## Table of Contents

1. [Features](#features)
2. [Datasets](#datasets)
3. [Methodology](#methodology)
    - [Classification](#classification)
    - [Compression](#compression)
    - [Segmentation](#segmentation)
    - [Cryptography](#cryptography)
4. [Challenges Faced](#challenges-faced)
5. [Limitations](#limitations)
6. [Future Work](#future-work)
7. [Contributors](#contributors)
8. [References](#references)

---

## Features

- **Quantum Classification**: Improved accuracy using quantum-inspired support vector machines.
- **Quantum Compression**: High fidelity image compression with minimal distortion.
- **Quantum Segmentation**: Detailed segmentation leveraging quantum-enhanced clustering.
- **Quantum Cryptography**: Advanced encryption ensuring data security using quantum principles.

---

## Datasets

- **MNIST**: 70,000 grayscale images of handwritten digits, preprocessed for compatibility with both classical and quantum methods.

---

## Methodology

### Classification

- **Quantum Approach**: 
  - Utilized amplitude encoding to prepare quantum circuits.
  - Achieved 90% accuracy on the MNIST dataset, outperforming classical SVM's 74%.
  - Trade-off: Quantum SVM required significantly more computation time (299.97 seconds vs. 0.89 seconds for classical SVM).

- **Classical Approach**: 
  - Implemented using Support Vector Classifiers with dimensionality reduction (PCA).
  - Focused on robustness and computational efficiency.

---

### Compression

- **Quantum Compression**: 
  - Encoded images using amplitude encoding and reconstructed them with high fidelity.
  - Metrics: Achieved superior Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity Index (SSIM).

- **Classical Compression**: 
  - Principal Component Analysis (PCA) for dimensionality reduction.
  - Effective but introduced more artifacts compared to the quantum approach.

---

### Segmentation

- **Quantum Segmentation**: 
  - Variational quantum algorithms optimized segmentation boundaries.
  - Leveraged quantum clustering for enhanced feature recognition.

- **Classical Segmentation**: 
  - Used K-Means clustering and traditional edge detection techniques.
  - Reliable but less detailed and refined.

---

### Cryptography

- **Quantum Cryptography**: 
  - Utilized Quantum Arnold Transform and chaotic systems for secure pixel scrambling.
  - Achieved robust encryption with metrics like entropy and PSNR.

- **Classical Cryptography**: 
  - XOR-based encryption providing randomness and simplicity.

---

## Challenges Faced

1. **Software Issues**: 
   - Compatibility issues with Qiskit updates led to switching to Cirq.
   - Documentation challenges for Qiskit made Cirq a more accessible alternative.

2. **Hardware Constraints**: 
   - High computational demand limited scalability on local systems.
   - Current quantum simulators added significant overhead.

3. **Cloud Service Limitations**: 
   - Encountered vCPU limits and subscription errors on AWS.
   - Transitioned to Azure and then to Google Colab Pro for improved accessibility.

---

## Limitations

- **Quantum Hardware**: The limitations of current quantum systems (e.g., qubit instability and error rates).
- **Computational Overhead**: Long execution times for quantum algorithms due to simulator inefficiencies.
- **Scalability**: Challenges in processing large datasets on available quantum platforms.

---

## Future Work

- Optimizing quantum algorithms to reduce computational costs and improve scalability.
- Exploring error-corrected qubits to enhance reliability and performance.
- Expanding quantum applications to domains like cryptography, medical imaging, and large-scale optimization.
- Advocating for better documentation and beginner-friendly quantum libraries.

---

## Contributors

- **Saran Teja Mallela**
- **Praneeth Puppala**
- **Tanmai Veerapaneni**
- **Hussain Shaik**
- **Uday Kiran Kodeboyina**
  
---

## References

1. Wang, Z., Xu, M., & Zhang, Y. (2022). Review of Quantum Image Processing.
2. Caraiman, S., & Manta, V. I. (2015). Image segmentation on a quantum computer.
3. Schuld, M., Sinayskiy, I., & Petruccione, F. (2015). Introduction to quantum machine learning.
4. Yan, F., & Iliyasu, A. M. (2017). Survey on quantum image processing techniques.

---

This README provides a comprehensive overview of the project, including features, methodologies, challenges, and directions for future development. If you encounter any issues or have suggestions, feel free to contribute!
