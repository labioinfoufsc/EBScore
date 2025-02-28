This repository contains a machine learning model based on a decision tree algorithm for the validation of *Trypanosoma* epitopes. The model was trained and evaluated using data obtained from IEDB and UniProt databases. 

# Dataset

The dataset used for model training and validation is available at:
- [https://doi.org/10.5281/zenodo.11388652](https://doi.org/10.5281/zenodo.11388652)

Data was preprocessed using [EpiBuilder](https://github.com/bioinformatics-ufsc/EpiBuilder) and complementary java code available in `/assets` folder. The dataset was evaluated using key algorithms with the Orange Data Mining tool, the file is also available in `/assets` folder.

# Usage Instructions (Google Colab)

## To use this project in Google Colab, follow these steps: 
1. Open the .ipynb file with [Google Colab](https://colab.research.google.com/)
2. Install the required dependencies for running the project, use the following command:
```bash
!pip install pandas matplotlib seaborn numpy scikit-learn
```
3. Upload the dataset file to your workspace
4. Run the model using CTRL+F9

## Contribution
Contributions are welcome! To suggest improvements or corrections, open an issue or submit a pull request.
