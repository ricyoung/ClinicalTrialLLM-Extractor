# ClinicalTrialLLM-Extractor Guidelines

## Environment Setup
- Python 3.x with Jupyter notebooks
- Key dependencies: pandas, numpy, openai, openrouter, matplotlib
- Install with: `pip install pandas numpy openai openrouter matplotlib requests`

## Data Pipeline Commands
- Data acquisition: `jupyter notebook 01_dataset_pull.ipynb`
- Data filtering: `jupyter notebook 02_simple_filtering.ipynb`
- LLM processing: `jupyter notebook 03_LLM_processor.ipynb`
- Analysis: `jupyter notebook paper_stats.ipynb`

## Code Style Guidelines
- Follow Jupyter notebook sequential cell execution pattern
- Store intermediate data in parquet format for efficient I/O
- Use pandas DataFrames as primary data structure
- Implement clear error handling for API calls with try/except blocks
- Use descriptive variable names with snake_case
- Group imports at the top of notebooks (standard library, then third-party)
- Include data validation steps between pipeline stages
- Document complex processing steps with markdown cells
- Store API keys in separate configuration cells