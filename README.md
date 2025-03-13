# ClinicalTrialLLM-Extractor

A tool for extracting and analyzing clinical trial data using Large Language Models.

## Overview

This project extracts structured information from clinical trials using LLMs, focusing on key parameters and outcomes. The pipeline includes data acquisition, filtering, LLM-based information extraction, and statistical analysis.

## Installation

```bash
git clone https://github.com/yourusername/ClinicalTrialLLM-Extractor.git
cd ClinicalTrialLLM-Extractor
pip install -r requirements.txt
```

## Project Structure

- `data/` - Raw and processed datasets
  - `raw/` - Original clinical trial data
  - `filtered/` - Filtered datasets
  - `processed/` - LLM-processed data
- `notebooks/` - Jupyter notebooks for pipeline stages
- `figures/` - Generated visualizations
- `results/` - Final analysis outputs

## Usage

1. Data acquisition: `jupyter notebook notebooks/01_dataset_pull.ipynb`
2. Data filtering: `jupyter notebook notebooks/02_simple_filtering.ipynb`
3. LLM processing: `jupyter notebook notebooks/03_LLM_processor.ipynb`
4. Analysis: `jupyter notebook notebooks/paper_stats.ipynb`

## License

This project is licensed under the MIT License - see the LICENSE file for details.