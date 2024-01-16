
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
![100 iterations of a sample](./Images/100 iterations of a sample.png)

## Neural Network Architecture
The project demonstrates the effectiveness of ML models in topology optimization. Various architectures were used and evaluated, and their performances were compared in terms of optimization efficiency and accuracy.

![Encoder-Decoder Net Model](./Images/Encoder-Decoder Net Model.png)
![Smaller Network](./Images/Smaller Network.png)
![Tiny Neural Network](./Images/Tiny Neural Network.png)

## Results
![Comparison of output from the Encoder-Decoder model and the ground truth](./Images/Results.png)

- Loss vs Epochs Plot
![Encoder Decoder Model- Loss vs. Epochs Plot](./Images/Encoder Decoder Model- Loss vs. Epochs Plot.png)
![Smaller Model- Loss vs. Epochs Plot](./Images/Smaller Model- Loss vs. Epochs Plot.png)
![Tiny Network Model- Loss vs. Epochs Plot](./Images/Tiny Network Model- Loss vs. Epochs Plot.png)

- Loss vs Epochs for different learning rates
![Training Loss vs. Epoch- Encoder Decoder Model](./Images/Training Loss vs. Epoch- Encoder Decoder Model.png)


## Contributions
Contributions to this project are welcome. Please read the contribution guidelines before submitting your contributions.
