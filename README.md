```markdown
# Data Cleaning in Python

This project demonstrates the process of cleaning a messy, **mock** healthcare dataset using Python, focusing on handling missing values, inconsistent data formats, and other common data cleaning tasks.

## Project Structure

- `healthcare_messy_data/`
  - `healthcare_messy_data.csv`: The original messy healthcare dataset used for cleaning.

- `healthcare_mock_data_cleaning.ipynb`: Jupyter Notebook containing the data cleaning process, including code and explanations.

- `healthcare_cleaned_data/`
  - `healthcare_cleaned_data.csv`: The cleaned and processed healthcare dataset.


## Key Features

- **Handling Missing Values**: Techniques to identify and replace or remove missing data.
- **Data Type Conversion**: Ensuring consistent data types across the dataset by replacing NaN with np.nan, as well as other standard data wrangling techniques.
- **Data Standardization**: Standardizing text data for uniformity.

## Getting Started

### Prerequisites

- Python 3.x
- Google Collab or Jupyter Notebook, whichever you like -- I used Google Colab
- pandas library

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/JosephMurage/data-cleaning-in-python.git
   cd data-cleaning-in-python
   ```
#### For Jupyter Notebook installation
   ```bash
   pip install pandas jupyter
   ```

### Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook healthcare_mock_data_cleaning.ipynb
   ```

2. Follow the steps in the notebook to understand the data cleaning process.

### Results

- **Original Data**: The original messy data is available in `healthcare_messy_data/healthcare_messy_data.csv`.
- **Cleaned Data**: The cleaned data is saved in `healthcare_cleaned_data/healthcare_cleaned_data.csv`.

## Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request with your improvements.

## License

This project is licensed under the MIT License.

---
