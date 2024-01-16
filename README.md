
# Machine Learning Models for Topology Optimization

## Overview
This project explores the integration of Machine Learning (ML) and Deep Learning (DL) techniques in the field of topology optimization. Leveraging the TOP dataset, the study presents a comprehensive approach to optimizing structural designs using advanced neural network architectures.

### Key Features
- Utilization of the TOP dataset comprising 10,000 scenarios for robust ML model training.
- Implementation of various neural network architectures, including an Encoder-Decoder Net model inspired by the U-Net architecture.
- Detailed analysis of neural network performance in structural optimization tasks.

## Neural Network Architectures
1. **Encoder-Decoder Net Model**: A complex model designed for detailed image processing.
2. **Smaller Network**: A streamlined version of the U-Net architecture, offering a compact design.
3. **Tiny Neural Network**: A lightweight model, ideal for simpler tasks.

## Dataset
The TOP dataset consists of solutions for 10,000 randomly generated scenarios on a 40×40 grid. It provides a detailed view of the optimization process over 100 iterations, ensuring a thorough understanding of topology optimization challenges.

![Dataset Image](./Images/top_dataset_pics.png)

#### 100 iterations of a sample
![100 iterations of a sample](./Images/100%20iterations%20of%20a%20sample.png)

## Neural Network Architecture
The project demonstrates the effectiveness of ML models in topology optimization. Various architectures were used and evaluated, and their performances were compared in terms of optimization efficiency and accuracy.

#### Encoder Decoder Model
![Encoder-Decoder Net Model](./Images/Encoder-Decoder%20Net%20Model.png)

#### Smaller Model
![Smaller Network](./Images/Smaller%20Network.png)

#### Tiny Network Model
![Tiny Neural Network](./Images/Tiny%20Neural%20Network.png)

## Results

### Comparison of Output
![Comparison of output from the Encoder-Decoder model and the ground truth](./Images/Results.png)

### Loss vs Epochs Plot

#### Encoder Decoder Model
![Encoder Decoder Model- Loss vs. Epochs Plot](./Images/Encoder%20Decoder%20Model-%20Loss%20vs.%20Epochs%20Plot.png)

#### Smaller Model
![Smaller Model- Loss vs. Epochs Plot](./Images/Smaller%20Model-%20Loss%20vs.%20Epochs%20Plot.png)

#### Tiny Network Model
![Tiny Network Model- Loss vs. Epochs Plot](./Images/Tiny%20Network%20Model-%20Loss%20vs.%20Epochs%20Plot.png)

### Loss vs Epochs for Different Learning Rates
![Training Loss vs. Epoch- Encoder Decoder Model](./Images/Training%20Loss%20vs.%20Epoch-%20Encoder%20Decoder%20Model.png)


## Contributions
Contributions to this project are welcome. Please read the contribution guidelines before submitting your contributions.
