# Makam & Usul: A Statistical Study of Rhythmic-Modal Patterns

## Overview
This repository contains the final project for the ethnomusicology class of 2025 at Universitat Pompeu Fabra, focusing on the statistical analysis of relationships between makam (modal) and usul (rhythmic) patterns in Turkish classical music. The project uses the SymbTr corpus, a comprehensive collection of Turkish makam music, to investigate correlations and patterns between these two fundamental components.

## Project Description
The study examines the statistical relationships between makams and usuls to identify patterns and preferences in Turkish classical compositions. By analyzing the frequency of specific makam-usul pairings, we can gain insights into traditional compositional practices and potentially discover underlying principles that govern these relationships.

## Getting Started

### Prerequisites
- Python 3.10 or higher
- Git

### Installation and Setup
1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/ethnomusicology-project.git
   cd ethnomusicology-project
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Clone the SymbTr repository** (contains ~2200 annotated Turkish makam music pieces)
   ```bash
   git clone https://github.com/MTG/SymbTr.git
   ```

## Data Processing and Analysis

1. **Data Preprocessing**
   - Open [code/data_preprocessing.ipynb](code/data_preprocessing.ipynb)
   - Set the path to your local SymbTr repository in the notebook
   - Run the notebook to generate the processed dataset
   - This will create the `data` directory and populate it with the necessary CSV files

2. **Correlation Analysis**
   - Open [code/correlation_analysis.ipynb](code/correlation_analysis.ipynb)
   - Run the notebook to perform statistical analysis and generate visualizations
   - The notebook provides detailed insights on makam-usul correlations, frequency distributions, and significant patterns

## Data
The `data` directory (generated when running the preprocessing notebook) contains processed datasets used in the analysis:
- [makam_usul_counts.csv](data/makam_usul_counts.csv): Frequency counts of makam-usul pairs extracted from the corpus

## Methodology
This project employs statistical methods to analyze the co-occurrence patterns of makams and usuls in the SymbTr corpus. The analysis includes:
- Frequency analysis of makam-usul pairs
- Correlation tests to identify significant relationships
- Visualization of distribution patterns and outliers

## Results
The key findings of this analysis are presented in the correlation analysis notebook, including:
- Most common makam-usul pairings
- Statistical significance of observed relationships
- Visualizations of patterns and distributions

## Acknowledgments
- The [SymbTr corpus](https://github.com/MTG/SymbTr) by the Music Technology Group at Universitat Pompeu Fabra

## Contributors
This project was developed as a collaborative effort between Sergio Cárdenas and me for our ethnomusicology class.

## License
This project is licensed under the MIT License - see the LICENSE file for details.