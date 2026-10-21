# Machine Learning Assignment

This project contains PyTorch implementations for machine learning tasks, including perceptron, regression, digit classification, language identification, convolution, and attention. It also includes a small character level GPT example.

## Project files

- `machinelearning/models.py` - model implementations
- `machinelearning/autograder.py` - assignment checks
- `machinelearning/backend.py` - datasets and training utilities
- `machinelearning/chargpt.py` and `gpt_model.py` - character level text generation example
- `machinelearning/data/` - provided datasets
- `machinelearning/input.txt` - text used by the example

## Setup and run

Install Python 3 and the required packages:

```bash
pip install torch numpy matplotlib
```

Run the assignment checks from the `machinelearning` directory:

```bash
cd machinelearning
python autograder.py
```

To run the character level GPT example, run `python chargpt.py` from the same directory.
