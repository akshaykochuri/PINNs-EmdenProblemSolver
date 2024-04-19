# Solving Lane Emden Equation Using Physics Informed Neural Network (PINNs)

## Abstract
This repository explores the application of Physics Informed Neural Networks (PINNs) to solve the Lane Emden Equation, comparing its performance with Artificial Neural Networks (ANNs). The study investigates the effectiveness of PINNs in capturing the principles of the Lane Emden Equation by incorporating them into the neural network architecture. It includes experiments adjusting collocation points and implementing optimization strategies to enhance solution accuracy and efficiency. The results demonstrate that PINNs outperform ANNs in accurately modeling the Lane Emden Equation while maintaining low computational costs. Additionally, it examines the impact of optimization techniques on convergence and solution precision.

## Contents
- [Introduction](#introduction)
- [Steps Involved in Training the Model](#steps-involved-in-training-the-model)
- [Why PINNs](#why-pinns)
- [Optimizations Implemented](#optimizations-implemented)
- [Results](#results)
- [Final Model](#final-model)
- [Comparisons with the Model in the Paper](#comparisons-with-the-model-in-the-paper)
- [Conclusion](#conclusion)
- [References](#references)
- [Work Distribution](#work-distribution)

## Introduction
This section provides an overview of Physics Informed Neural Networks (PINNs) and their relevance in solving differential equations such as the Lane Emden Equation. It discusses the merging of learning with physics-based models and the challenges addressed by PINNs in scientific and engineering domains.

## Steps Involved in Training the Model
Details the process of training the model, including incorporating physics constraints, defining network architecture and loss function, and training using optimization techniques.

## Why PINNs
Discusses the advantages of using PINNs over conventional numerical integration techniques, emphasizing their adaptability and generalization capabilities.

## Optimizations Implemented
Describes the optimization strategies implemented in the project, including introducing a parameter 'k' and adjusting the learning rate dynamically using 'ReduceLROnPlateau'.

## Results
Presents the results of experiments conducted with various configurations, showcasing the Mean Squared Error (MSE) for different models.

## Final Model
Details the optimal configuration of the final model, including the number of collocation points, neurons per layer, and hidden layers, along with the optimized parameter 'k'.

## Comparisons with the Model in the Paper
Compares the performance of the final model with the results presented in the referenced research paper.

## Conclusion
Summarizes the findings of the study, highlighting the advantages of using PINNs for solving complex differential equations and the impact of optimization strategies on model performance.

## References
Lists the research paper and other resources referenced in the project.

## Work Distribution
Specifies the contributions of team members to different aspects of the project.

## Certificate
[Certificate.pdf](Certificate.pdf)

## Colab Notebook
[Colab Notebook](https://colab.research.google.com/drive/1CRu3obh_TYVR5kCeEYqkEvbSJHsQfEeF?usp=sharing)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
