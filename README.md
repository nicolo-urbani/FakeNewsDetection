# Fake News Detection 
Fake News Detection - A Comparative Study of Deep Learning Computational Methods

Advanced Machine Learning **Project** - *A.Y. 2023/24*

**Team**:
*   **Mattia Piazzalunga** - 851931
*   **Nicolò Urbani** - 856213

## Benchmark Datasets:

*   **WELFake dataset** - Verma et al.
*   **ISOT dataset** - Ahmed et al.

## Abstract
”Fake news” are a central issue in today’s society, a phenomenon
intensifid by the advent of social media which has facilitated their
dissemination. Automatically detecting them, therefore, becomes a
fundamental challenge involving research. In this paper, the state-of-
the-art has been achieved on two benchmark datasets for ”fake news
detection”: ISOT and WELFake, achieving 100% accuracy in classi-
fying news from the former and 97% from the latter. Additionally,
a custom neural network was built, which, with a 99.96% parameter
reduction, achieved accuracy close to the most performant model stud-
ied in this analysis, based on BERT. Back Translation and Dataset
Combination proved unhelpful techniques in attempting to improve
model generalization for this type of task.

## Requirements

Before executing the Python code, make sure you have the following packages installed:

```bash
pip install contractions
pip install spacy
pip install tensorflow
pip install keras
pip install inflect
pip install -q -U tensorflow-text
pip install -q tf-models-official

```

## Setting Directory Base Path

In the code section 'Main global variables & functions' set the base path directory in where you have stored the project files:


```bash 
python path_to_drive_folder = "/content/drive/MyDrive/Advanced_Machine_Learning"
```

Change this path according to your directory structure.

## Necessary Folders

Ensure the following folders exist within your project directory:

    datasets
    preprocessed_dataset
    models
    txt

## Running the Code

After setting up the directory structure and installing the required packages, you can run the Python code provided.




