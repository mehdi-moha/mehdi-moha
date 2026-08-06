# 🎓 Academic Portfolio

A structured academic portfolio by **Mehdi Mohammadi**, documenting projects, assignments, simulations, reports, notebooks, and independent implementations across multiple areas of computer science and engineering.

This repository includes work in **software engineering**, **digital systems**, **computer architecture**, **machine learning**, **statistical pattern recognition**, **data mining**, **deep learning**, **computer vision**, **robotics**, **fuzzy systems**, **evolutionary computation**, and **digital image processing**.

The portfolio intentionally separates **from-scratch algorithmic implementations** from applied projects that use standard scientific computing, machine learning, simulation, or deep learning tools.

---

## 📌 Repository Structure

| Folder | Academic Stage | Main Topics |
|---|---|---|
| [`AAS`](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/aas) | AAS in Computer Software | Digital logic circuits and PSpice-based simulation |
| [`BSc`](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/bsc) | BSc in Software Engineering | Algorithms, AI, compiler design, VHDL CPU design, computer architecture, electronics, and microprocessors |
| [`1st MSc`](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-1) | MSc in Computer Systems Architecture | Digital image processing and neural networks |
| [`2nd MSc`](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2) | MSc in Artificial Intelligence and Robotics | Machine learning, deep learning, computer vision, data mining, robotics, fuzzy systems, evolutionary computation, and statistical pattern recognition |

---

## ⭐ Selected Highlights

| Functional Area | Highlighted Projects |
|---|---|
| From-Scratch Machine Learning | Bayesian Classification, K-Means, EM/GMM |
| From-Scratch Pattern Recognition | Parametric Classification, KNN/MED/MMD, Linear Discriminant Functions, MLP Backpropagation |
| Data Mining from Scratch | ChiMerge, DBSCAN, AdaBoost |
| Visual Recognition and Image Classification | Persian Handwritten Digit Recognition - HODA, Flower Species Classification, German Traffic Sign Recognition |
| Generative Deep Learning | DCGAN for Persian Digit Generation, VAE for Persian Digit Reconstruction and Generation |
| Vision-Language Modeling | Image Captioning on Flickr8k |
| Medical AI and Health Data Analysis | Chest X-Ray Pneumonia Detection, Diabetes Prediction Analysis |
| Semantic Segmentation | Pet Segmentation with U-Net |
| Image Processing and Restoration | Digital Image Processing in MATLAB, Image Denoising Methods Comparison |
| Digital Systems and Embedded Design | Mano’s Basic Computer CPU in VHDL, 8051 Digital Clock, LED Matrix Controller |
| Optimization, Fuzzy Control, and Robotics | Artificial Bee Colony, Multiobjective GA, Fuzzy HVAC Control, Grid Wall Following, Robotic Arm Kinematics |

---

## 🧭 Contents

- [🧠 From-Scratch Implementations](#from-scratch-implementations)
- [📊 Applied Machine Learning and Comparative Studies](#applied-machine-learning-and-comparative-studies)
- [🤖 Deep Learning Projects](#deep-learning-projects)
- [👁️ Computer Vision Projects](#computer-vision-projects)
- [🚀 Independent Projects](#independent-projects)
- [🖼️ Digital Image Processing and Neural Networks](#digital-image-processing-and-neural-networks)
- [🧬 Evolutionary Computation, Fuzzy Systems, and Robotics](#evolutionary-computation-fuzzy-systems-and-robotics)
- [💻 Algorithms, Artificial Intelligence, and Compiler Design](#algorithms-artificial-intelligence-and-compiler-design)
- [🖥️ Digital Systems, Hardware, and Low-Level Design](#digital-systems-hardware-and-low-level-design)
- [🛠️ Tools and Technologies](#tools-and-technologies)
- [📄 Notes](#notes)
- [⚖️ Copyright & Usage](#copyright--usage)

---

<a id="from-scratch-implementations"></a>

## 🧠 From-Scratch Implementations

Projects in this section were implemented from first principles.  
The **From Scratch** label is used only for projects where the core algorithmic logic was manually implemented without relying on machine learning or deep learning libraries.

---

### 📌 Machine Learning from Scratch

- 📌 [**Bayesian Classification from Scratch**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/machine-learning/Computer_Assignment_ML1)  
  Multivariate Gaussian classification implemented from first principles, including manual maximum likelihood parameter estimation, covariance matrix computation, discriminant function implementation, decision-boundary analysis, and interactive point classification.

- 🔵 [**K-Means and EM/GMM from Scratch**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/machine-learning/Computer_Assignment_ML2)  
  Manual implementation of K-Means clustering and Expectation-Maximization for Gaussian mixture modeling. Includes Euclidean distance computation, centroid updates, posterior probability estimation, covariance updates, animated convergence visualization, and contour-based analysis.

---

### 📊 Statistical Pattern Recognition from Scratch

- 📊 [**Parametric Classification from Scratch**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/statistical-pattern-recognition/Computer%20Assignment%20%231)  
  Bayesian classifiers with manual maximum likelihood estimation, discriminant functions, leave-one-out cross-validation, confusion matrices, and misclassification analysis on Iris and Liquid datasets, plus empirical/theoretical error evaluation on the Normal dataset.

- 🔍 [**KNN, MED, and MMD from Scratch**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/statistical-pattern-recognition/Computer%20Assignment%20%232)  
  Non-parametric and distance-based classification using manually implemented KNN, Parzen window volume, Euclidean distance, Mahalanobis distance, minimum mean distance, and class-centroid-based decision rules.

- 📐 [**Linear Discriminant Functions from Scratch**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/statistical-pattern-recognition/Computer%20Assignment%20%233)  
  Implementation of perceptron learning, least-squares classification, and multi-category logistic discrimination. Includes one-vs-rest and one-vs-one classifiers, spatial visualization, and ambiguous decision-region analysis.

- 🧠 [**MLP Backpropagation from Scratch**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/statistical-pattern-recognition/Computer%20Assignment%20%234)  
  Manual 3-4-2 multilayer perceptron implementation with sigmoid activations, adaptive learning rate, normalized inputs, trained weights, confusion matrix, and misclassification analysis.

---

### 🧩 Data Mining from Scratch

- 🧩 [**ChiMerge Discretization from Scratch**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/data-mining/ChiMerge)  
  Chi-square-based continuous attribute discretization implemented from first principles. Includes manual chi-square statistics, interval merging based on statistical significance, and automated binning across Iris dataset features.

- 🌀 [**DBSCAN Clustering with Animated Visualization from Scratch**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/data-mining/DBSCAN)  
  Density-based clustering implemented from scratch with epsilon-neighborhood computation, core/border/noise labeling, cluster expansion using a seed list, and animated visualization on smiley-face and two-spiral datasets.

- 🚀 [**AdaBoost Classifier from Scratch**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/data-mining/AdaBoost)  
  AdaBoost ensemble learning implemented from scratch for nonlinear binary classification. Uses weak single-layer linear classifiers, manual weighted resampling, sample-weight updates, weak learner weighting, and final classification visualization.

---

### 🧠 Deep Learning from Scratch

- 🧠 [**Dynamic MLP from Scratch**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/deep-learning/HW02%20%28MLP%20from%20Scratch%29)  
  Manual implementation of forward propagation, backpropagation, gradient descent, cross-entropy loss, sigmoid activation, and configurable multilayer neural-network architectures in MATLAB. Includes both Cell-based and Eval-based implementations for cardiovascular disease prediction and XOR learning.

---

### 🔁 Neural Networks from Scratch

- 🔁 [**Hopfield Shapes: Pattern Recovery from Scratch**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-1/neural-networks/Hopfield-Shapes-From-Scratch)  
  Discrete Hopfield neural network implemented from scratch in MATLAB for associative memory and binary pattern recovery. The model stores 11×11 geometric patterns and reconstructs corrupted circle, square, and triangle inputs using Hebbian learning and synchronous neuron updates.

---

<a id="applied-machine-learning-and-comparative-studies"></a>

## 📊 Applied Machine Learning and Comparative Studies

Projects in this section use standard machine learning libraries, built-in classifiers, or comparative workflows.  
They are intentionally separated from From-Scratch implementations.

- 📈 [**Dimensionality Reduction and Multi-Classifier Comparison**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/machine-learning/Computer_Assignment_ML3)  
  Comparative machine learning workflow using PCA, Kernel PCA, and multiple classifiers in MATLAB and Python. The MATLAB version uses built-in classifiers, while the Python version uses scikit-learn classifiers including LDA, Naive Bayes, SVM, neural network, and decision tree models.

- 🩺 [**Diabetes Prediction Analysis**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/statistical-pattern-recognition/Final%20Project)  
  Comparative diabetes prediction study using supervised machine learning models in scikit-learn. Includes dataset cleaning, categorical encoding, numerical feature standardization, SMOTENC class-imbalance handling, ExtraTrees-based feature selection, and evaluation using accuracy, precision, recall, F1-score, confusion matrices, and classification reports.

---

<a id="deep-learning-projects"></a>

## 🤖 Deep Learning Projects

- ✍️ [**Persian Handwritten Digit Recognition - HODA**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/deep-learning/HW03)  
  Fully-connected neural network for 10-class Persian handwritten digit classification using the HODA dataset. Includes image padding, resizing, normalization, dropout, regularization, Comet ML Bayesian hyperparameter optimization, ModelCheckpoint, training/validation curves, and held-out test evaluation.

- 🌸 [**Flower Species Classification**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/deep-learning/HW04)  
  CNN-based TensorFlow/Keras classifier for five flower species: daisy, dandelion, roses, sunflowers, and tulips. Includes stratified train/validation/test splitting, data augmentation, optimizer comparison, EarlyStopping, ReduceLROnPlateau, and held-out test evaluation.

- 🎨 [**DCGAN for Persian Digit Generation**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/deep-learning/HW05/DCGAN)  
  Deep Convolutional GAN for generating Persian handwritten digits using the HODA dataset. Includes convolutional generator and discriminator networks, adversarial training, label smoothing, fixed-noise sample visualization, and generator export.

- 🧬 [**VAE for Persian Digit Reconstruction and Generation**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/deep-learning/HW05/VAE)  
  Variational Autoencoder for Persian digit reconstruction and generation using a 16-dimensional latent space, reparameterization trick, reconstruction loss, KL-divergence regularization, latent sampling, and separate encoder/decoder export.

- 🖼️ [**Image Captioning on Flickr8k**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/deep-learning/Final_Project%20%28Image_Captioning%29)  
  Encoder-decoder image captioning model using Xception visual features and LSTM-based text modeling. Includes caption cleaning, tokenizer-based vocabulary construction, beam search decoding, repetition control, and sample caption generation.

---

<a id="computer-vision-projects"></a>

## 👁️ Computer Vision Projects

- 👁️ [**Computer Vision Assignments**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/computer-vision)  
  Collection of computer vision assignments covering color-space conversion, Gaussian noise injection, spatial filtering, Canny edge detection, histogram equalization, K-means color quantization, thresholding, affine and perspective transformations, contour detection, Hough Circle Transform, and object counting.

- 🚦 [**German Traffic Sign Recognition**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/computer-vision/CV_Final_Project)  
  TensorFlow/Keras CNN classifier for the GTSRB traffic sign dataset with 43 classes. Includes CLAHE illumination enhancement, normalization, convolutional blocks, Batch Normalization, Dropout, Global Average Pooling, EarlyStopping, ReduceLROnPlateau, and official test-set evaluation.

---

<a id="independent-projects"></a>

## 🚀 Independent Projects

- 🏥 [**Chest X-Ray Pneumonia Detection**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/independent-projects/chest_xray_pneumonia_detection)  
  PyTorch deep CNN for binary classification of chest radiographs into Normal and Pneumonia classes. The project uses a leakage-aware patient/group-level split, grayscale preprocessing, weighted cross-entropy, threshold optimization with Youden’s J statistic, ROC/PR analysis, calibration evaluation, confusion matrix, training curves, and prediction visualization.

- 🌫️ [**Image Denoising Methods Comparison (From Scratch with Research Report)**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/independent-projects/denoising-methods)  
  Independent research-style image processing project with a complete report and from-scratch implementation of Gaussian smoothing, linear diffusion, and Perona-Malik anisotropic diffusion. The study compares denoising performance using PSNR, SSIM, edge preservation index, diffusivity analysis, contour visualization, and metric sensitivity analysis.

- 🐾 [**Pet Segmentation with U-Net**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/independent-projects/unet_pet_segmentation)  
  PyTorch U-Net for binary semantic segmentation of pet images from the Oxford-IIIT Pet dataset. Includes breed-stratified splitting, Albumentations preprocessing, Group Normalization, combined Cross-Entropy and Focal Tversky loss, mixed precision training, validation-based threshold tuning, connected-component post-processing, and official test-set evaluation.

---

<a id="digital-image-processing-and-neural-networks"></a>

## 🖼️ Digital Image Processing and Neural Networks

### 🖼️ Digital Image Processing

- 🖼️ [**Digital Image Processing in MATLAB**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-1/digital-image-processing)  
  MATLAB implementations of fundamental digital image processing techniques, including gamma correction, JPEG compression quality analysis, RGB channel manipulation, color quantization, histogram equalization, piecewise linear transformations, bit-plane slicing, spatial filtering, noise reduction, edge detection, morphological operations, Laplacian sharpening, and image quality metrics such as MSE and PSNR.

---

### 🧠 Neural Networks

- 📈 [**SineNet: Function Approximation**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-1/neural-networks/SineNet)  
  Feedforward neural network for noisy sine-function approximation with train/validation/test splitting, regression visualization, and predicted-versus-actual comparison.

- 📊 [**FFNN Regression: Multi-Input Prediction**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-1/neural-networks/ffnn-regression)  
  Feedforward neural network for regression analysis on a tabular dataset with four input features and one target output using tansig/purelin activations and MSE-based performance evaluation.

- 🔢 [**Hopfield Digits: Pattern Recognition**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-1/neural-networks/hopfield-digits)  
  Hopfield recurrent neural network for handwritten digit recognition and associative recall under varying salt-and-pepper noise levels, with iterative convergence visualization across multiple time steps.

---

<a id="evolutionary-computation-fuzzy-systems-and-robotics"></a>

## 🧬 Evolutionary Computation, Fuzzy Systems, and Robotics

- 🐝 [**Artificial Bee Colony Optimization**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/evolutionary-computation/Artificial-Bee-Colony)  
  Swarm intelligence optimization for Rastrigin function minimization using employed bees, onlooker bees, scout bees, roulette-wheel selection, stagnation handling, exploration-exploitation balancing, convergence visualization, and contour analysis.

- 🎯 [**Multiobjective Genetic Algorithm**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/evolutionary-computation/Multiobjective-GA-with-Constraints)  
  NSGA-II-based constrained bi-objective optimization with non-dominated sorting, Pareto-front generation, linear and nonlinear constraint handling, and visualization of Pareto-optimal solutions.

- 🌡️ [**Thermal Comfort Control System**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/fuzzy-methods-and-systems/fuzzy-hvac-power-control)  
  Mamdani fuzzy inference system for HVAC power dissipation control using temperature and relative humidity inputs, Gaussian, triangular, and trapezoidal membership functions, 15 fuzzy rules, min-max inference, centroid defuzzification, and surface visualization.

- 🧭 [**Grid Wall Following**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/robotics/Grid_Wall_Following)  
  Grid-based maze navigation using right-hand and left-hand wall-following strategies, directional priority rules, visited-cell tracking, maximum-iteration termination, animated path visualization, and performance metrics including success rate, path length, and mean steps.

- 🦾 [**Robotic Arm Kinematics and Workspace Analysis**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/msc-2/robotics/Arm_Kinematics_Analysis)  
  Analytical and simulation-based study of robotic arm kinematics using MATLAB. Includes forward and inverse kinematics derivation for a custom 3-DOF RRP robotic arm with transformation matrices, workspace reachability conditions, and elbow-up/elbow-down configurations. Also includes PUMA 560 workspace simulation using Denavit-Hartenberg parameters, cumulative transformation matrices, real-time 3D animation, and end-effector trajectory visualization.

---

<a id="algorithms-artificial-intelligence-and-compiler-design"></a>

## 💻 Algorithms, Artificial Intelligence, and Compiler Design

- 🔗 [**Algorithms Design Projects**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/bsc/algorithms-design)  
  Dynamic programming projects including Matrix Chain Multiplication, Subset Sum with state tracking, and space-optimized Binomial Coefficient calculation using Pascal’s Triangle.

- 🧭 [**Maze Solver with BFS and A\***](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/bsc/artificial-intelligence/MazeSolver)  
  Pathfinding implementation using Breadth-First Search and A* Search with Manhattan-distance heuristic. Includes route optimization comparison, node expansion analysis, and queue-operation metrics.

- 🔣 [**Simple Parser**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/bsc/principles-of-compiler-design/Project)  
  Stack-based operator-precedence parser for arithmetic-expression syntax analysis using shift/reduce operations, grammar validation, and error detection.

---

<a id="digital-systems-hardware-and-low-level-design"></a>

## 🖥️ Digital Systems, Hardware, and Low-Level Design

- 🧮 [**Mano’s Basic Computer CPU Implementation in VHDL**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/bsc/bachelor-project)  
  Complete hardware implementation of Mano’s Basic Computer CPU architecture in structural VHDL. Includes control unit, 16-bit ALU, registers, memory unit, data bus, control flags, Fetch-Decode-Execute cycle, interrupt mechanism, and memory-reference, register-reference, and I/O instruction support.

- 🧱 [**Computer Architecture Lab - Processor Design**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/bsc/computer-architecture-lab)  
  8-bit ALU and datapath implementation using Proteus simulation, 74LS181 ALU chips, 74-series registers, and control-signal management for multi-bit calculations.

- 🔌 [**Electronic Circuit Designs**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/bsc/electronic-lab)  
  Electronic circuit design, simulation, verification, component testing, and performance measurement using Multisim-based laboratory experiments.

- ⏱️ [**8051 Digital Clock in Assembly**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/bsc/microprocessor-1/Digital_Clock)  
  Real-time digital clock using 8051 Assembly Language with Timer0 interrupts, external interrupt handling, BCD conversion, hour/minute adjustment, and automatic 24-hour reset functionality in a Multisim simulation environment.

- 💡 [**8×8 LED Matrix Display Controller**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/bsc/microprocessor-lab/micro-project)  
  LED scrolling display controller using BASCOM-AVR with timer interrupts, dynamic scanning, speed control, pause/resume functionality, pattern animation, and lookup-table design in Proteus.

- 🧩 [**Digital Logic Circuits Lab**](https://github.com/mehdi-moha/Academic-Portfolio/tree/main/aas/computer-logic-circuits-lab)  
  Implementation and verification of digital logic circuits using PSpice software. Includes gate-level circuit design, simulation, and analysis for combinational and sequential logic experiments.

---

<a id="tools-and-technologies"></a>

## 🛠️ Tools and Technologies

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/MATLAB-FF8C00?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Pascal-00599C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/VHDL-4B0082?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Assembly-555555?style=for-the-badge" />
  <img src="https://img.shields.io/badge/BASCOM--AVR-006400?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PSpice-8B0000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Proteus-1E90FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Multisim-4682B4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ModelSim-2F4F4F?style=for-the-badge" />
  <img src="https://img.shields.io/badge/QuestaSim-2F4F4F?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-2E8B57?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Deep%20Learning-DC143C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Computer%20Vision-1E90FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Pattern%20Recognition-20B2AA?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data%20Mining-DAA520?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Digital%20Systems-708090?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Optimization-8A2BE2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Robotics-4169E1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Simulation-8B008B?style=for-the-badge" />
</p>

---

<a id="notes"></a>

## 📄 Notes

This repository is intended as a structured academic archive and portfolio.

It includes source code, notebooks, simulation files, reports, presentations, datasets where applicable, and project documentation from multiple academic stages.

Some projects are implemented from scratch, while others use standard scientific computing, simulation, machine learning, or deep learning tools. These categories are intentionally separated throughout this README.

---

<a id="copyright-and-usage"></a>

## ⚖️ Copyright & Usage

All intellectual property rights to the original contents of this repository, including but not limited to source code, documents, reports, figures, datasets, and written materials created by Mehdi Mohammadi, are exclusively owned by Mehdi Mohammadi.

Any form of copying, reproduction, modification, redistribution, publication, or commercial use of these original materials, in whole or in part, is strictly prohibited without prior written permission from the author.

Any third-party materials included in this repository remain subject to their respective licenses and belong to their original authors or rights holders.

© 2026 Mehdi Mohammadi. All rights reserved.
