# McCulloch-Pitts-Neuron
```markdown
# McCulloch-Pitts Neuron Triangle Classification

A Python implementation of McCulloch-Pitts neurons for detecting points inside a triangular region, with comparative analysis of different activation functions.

![Activation Function Comparison](https://raw.githubusercontent.com/yourusername/repo-name/main/images/comparison_plot.png)

## Project Description
This project demonstrates how different activation functions in McCulloch-Pitts neurons can be used to classify points within a triangular region. The implementation includes:

- Generation of 2000 random points in a defined space
- Three boundary-checking neurons for triangle edges
- Five different activation functions for final classification
- Visual comparison of results
- Quantitative performance analysis

## Key Features
- **Supported Activation Functions**:
  - Step Function
  - Sign Function
  - Sigmoid
  - Hyperbolic Tangent (Tanh)
  - Rectified Linear Unit (ReLU)
  
- **Visualization**:
  - Side-by-side comparison of activation function results
  - Clear triangle boundary visualization
  - Interactive matplotlib plots

- **Analysis Tools**:
  - Automatic point counting for each region
  - Compatibility comparison with baseline (step function)
  - Validation tests for edge cases

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/repo-name.git
cd repo-name
```

2. Install dependencies:
```bash
pip install numpy matplotlib
```

## Usage
Run the main script:
```bash
python triangle_classification.py
```

The script will:
1. Generate random points
2. Classify points using different activation functions
3. Display comparative visualizations
4. Print performance statistics
5. Show validation test results

## Results
### Sample Output
```
![image](https://github.com/user-attachments/assets/904606b2-4437-49e2-a498-4c5bb6219334)

```

### Visualization
The script generates a 2x3 grid of plots showing classification results for each activation function.

## Contributing
Contributions are welcome! Please open an issue first to discuss proposed changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
