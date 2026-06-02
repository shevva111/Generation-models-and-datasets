Code for generation of sythetic tabular datasets and csv files representing each models output

## Repository Structure

- `distilgpt2.ipynb`: Fine-tuning and synthetic data generation using DistilGPT-2.
- `OPT125M.ipynb`: Fine-tuning and generation using OPT-125M.
- `OPT350M.ipynb`: Fine-tuning and generation using OPT-350M.
- `OPT1_3b.ipynb`: Fine-tuning and generation using OPT-1.3B.
- `synthetic_results.ipynb`: Utility and privacy evaluation of generated datasets.
- `student-mat.csv`: Original Student Performance dataset.
- `synthetic_students_typed*.csv`: Generated synthetic datasets.
- `synthetic_privacy_metric.csv`: Privacy metric results.

## How to Reproduce

1. Install the required dependencies.
2. Run the model notebooks to generate synthetic datasets.
3. Run `synthetic_results.ipynb` to reproduce the evaluation results.
4. Compare the generated results with the tables reported in the thesis.
