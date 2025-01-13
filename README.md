
# Deep Learning Image Classification with PyTorch

A comprehensive implementation of handwritten digit classification using PyTorch and the MNIST dataset, achieving 97.16% validation accuracy.
![image](https://github.com/user-attachments/assets/c021d5e4-dadd-4a85-ae44-8d592a61e9df)


## Project Overview

This project demonstrates:
- Implementation of a neural network for MNIST digit classification
- Training process visualization and analysis
- Model performance optimization
- Numeric representation visualization of handwritten digits

![image](https://github.com/user-attachments/assets/2f13be7a-7fed-4b84-a9ba-bdfb8b403c78)


## Key Features

- **High Accuracy**: Achieves 97.92% training accuracy and 97.16% validation accuracy
- **Efficient Training**: Converges in 40 epochs with steady performance improvement
- **Visualization**: Includes loss and accuracy plots for model performance analysis
- **Clean Implementation**: Well-structured PyTorch code with clear documentation

## Model Architecture

- Input Layer: 784 neurons (28x28 pixel images)
- Hidden Layer 1: 128 neurons with ReLU activation
- Hidden Layer 2: 64 neurons with ReLU activation
- Output Layer: 10 neurons (one for each digit)

## Results

The model demonstrates excellent learning progression:
- Training Loss: 1.665795 → 0.073921
- Validation Loss: 0.760273 → 0.095744
- Training Accuracy: 55.24% → 97.92%
- Validation Accuracy: 82.01% → 97.16%

## Requirements

```
torch
torchvision
matplotlib
numpy
```

## Usage

1. Clone the repository
2. Install dependencies
3. Run the Jupyter notebook
4. Experiment with hyperparameters

## Future Improvements

- Implement data augmentation
- Experiment with different architectures
- Add real-time prediction capabilities
- Integrate with web interface

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## Author

Rhythm Bhavsar

## Acknowledgments

- PyTorch Team
- MNIST Dataset creators
- Deep Learning Community

---
⭐ Star this repository if you find it helpful!
