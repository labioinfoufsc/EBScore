This repository contains a machine learning model based on a decision tree algorithm for the validation of *Trypanosoma* epitopes. The model was trained and evaluated using data obtained from [IEDB](https://www.iedb.org/) and [UniProtKB](https://www.uniprot.org/uniprotkb) databases. 

# Dataset

The dataset used for model training and validation is available at:
- [https://doi.org/10.5281/zenodo.11388652](https://doi.org/10.5281/zenodo.11388652)

Data was preprocessed using [EpiBuilder](https://github.com/bioinformatics-ufsc/EpiBuilder) and complementary java code available in `/assets` folder. The dataset was evaluated using key algorithms with the [Orange Data Mining](https://orangedatamining.com) tool, the file is also available in `/assets` folder.

# Usage Instructions (Google Colab)

To use this project in Google Colab, follow these steps: 
1. Open the .ipynb file with [Google Colab](https://colab.research.google.com/)
2. Install the required dependencies for running the project, use the following command:
```bash
!pip install pandas matplotlib seaborn numpy scikit-learn
```
3. Upload the dataset file to your workspace
4. Run the model using CTRL+F9

# Contribution
Contributions are welcome! To suggest improvements or corrections, open an issue or submit a pull request.

# Citation

## To cite our dataset

Bruna Caroline Russi, Renato Simões Moreira, Pablo Daniel Cuña Cabrera, & Silvio César Cazella. (2024). Trypanosoma Epitope Dataset: Valid Epitopes and Randomly Generated Peptides with Biochemical Metrics and AI-Generated Scores (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.

## To cite and to know more about the dataset creation process

Russi, B. C., Moreira, R. S., Cabrera, P. D. C., & Cazella, S. C. (2024). Concepção de dataset de epítopos lineares de células B de organismos do gênero Trypanosoma para treinamento de algoritmos baseados em aprendizado de máquina. In C. S. Dias, E. T. Albergaria, & Z. S. N. Reis (Eds.), Anais do II Simpósio CI-IA Saúde da UFMG: Inteligência artificial responsável no ensino, pesquisa e práticas em saúde (pp. 70–72). Universidade Federal de Minas Gerais. http://hdl.handle.net/1843/78914
