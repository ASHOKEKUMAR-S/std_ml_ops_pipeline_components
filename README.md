# std_ml_ops_pipeline_components

**std_ml_ops_pipeline_components** is a modular collection of Python scripts designed to support standardized Machine Learning Operations (MLOps) workflows. These components can be easily integrated into CI/CD pipelines for model training, inference, validation, and job monitoring.

## Repository Structure

std_ml_ops_pipeline_components/
├── ml_ops_pipeline/
│   ├── __init__.py
│   ├── trigger_job.py
│   ├── wait_for_completion.py
│   ├── validate_metric.py
│   └── validate_inference.py
├── .gitignore
├── README.md
└── requirements.txt


## 🚀 Components

Each script under `ml_ops_pipeline/` is responsible for a specific stage in the MLOps lifecycle:

- **`trigger_job.py`**: Triggers a job (e.g., training or inference) on an external platform like Databricks.
- **`wait_for_completion.py`**: Polls and waits for the triggered job to complete.
- **`validate_metric.py`**: Validates training metrics (e.g., accuracy, loss) against expected thresholds.
- **`validate_inference.py`**: Validates inference results using stored artifacts or references.

## ⚙️ Installation

Clone this repository and install the required packages:

```bash
git clone https://github.com/Ashoke238/std_ml_ops_pipeline_components.git
cd std_ml_ops_pipeline_components
pip install -r requirements.txt

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change. Make sure to write tests for any new functionality.