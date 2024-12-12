# Mutagenicity Prediction Project

## Description

This project is focused on predicting mutagenicity using machine learning and cheminformatics tools. It is divided into two phases, each with distinct approaches and methodologies. The project is designed to run on Mac computers using Python 3.9 and can also be accessed via Google Colab for added convenience.

### Phase 1 - Structural Fingerprints
- Utilizes **RDKit** to extract structural and physical fingerprints.
- Developed as a **Jupyter Notebook** for local use on Mac computers.
- Can be run on Google Colab using the provided link: [Phase 1 Colab Link](https://colab.research.google.com/drive/11APpA_6nEir-n2ndRC-0cJenXXEQRWCZ?usp=sharing).
- Originally created in Google Colab and later downloaded for local editing. The `requirements.txt` file was generated using `pip freeze` from the local environment.

### Phase 2 - CDK Fingerprints
- Fully accessible through **Google Colab**: [Phase 2 Colab Link](https://colab.research.google.com/drive/1A98ukUjOxOOz_yY34ZF2Sqz9LKuQRqq8?usp=sharing).
- Uses **PaDEL-Py**, a Java-based software requiring additional setup for local use. Google Colab eliminates the need for Java installation, making the project more accessible.
- Phase 2 is not currently available for download, however, feel free to download the notebook directly from the Google Colab link. Additional software will be required. 

---

## Features
- Extracts, sorts, and processes data features using **PyTDC**.
- Exports the training dataset as a **CSV** file.
- Implements and evaluates machine learning algorithms:
  - **Random Forest Classifier**
  - **k-Nearest Neighbor**
- Assesses models using **ROC AUC** metrics.
- Reports **feature importance** through tables and visual graphs.

---

## Requirements

### Local Setup (Mac)
Ensure you have the following installed:
- **Python 3.9**
- Required Python packages listed in `requirements.txt`:
  ```bash
  pip install -r requirements.txt


