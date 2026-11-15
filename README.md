# CMPE 257: SLIM Fake-News Detection

This project reproduces the SLIM (Systematically-selected Limited Information) framework for fake-news detection.

The project investigates whether fake news can be detected using limited information instead of the complete article text. We use the ReCOVery and Fake_And_Real_News datasets.

## Project Components

- Data preprocessing and quality checks
- XLNet full-text baseline model
- Keyword-based SLIM model
- Sequence-based SLIM model
- Metadata-based SLIM model
- Model evaluation using accuracy, macro-F1, and AUC

## Reference Paper

[Is Less Really More? Fake News Detection with Limited Information](https://kdd.org/exploration_files/p20-Is_Less_Really_More.pdf)

## Authors' Repository

[SLIM GitHub Repository](https://github.com/kappakant/SLIM)

## Datasets

The datasets are loaded directly from the authors' public repository during notebook execution.

## Main File

- `CMPE_257_Project.ipynb`
