# PLQY Predictor (PREDQY)

## MIT License
MIT License. Free to use.

## Overview
The PLQY Predictor is a Python-based graphical user interface (GUI) application that allows users to input two SMILES (Simplified Molecular Input Line Entry System) strings and get a prediction of the Photoluminescence Quantum Yield (PLQY). There is also code snippets that show training for OLED, in two different datasets.

## Prerequisites
Before running the PLQY Predictor, ensure you have the following installed:
- Python 3.8 or above
- `pip` for installing Python packages
- (Optional) A virtual environment manager like `conda` or `venv`

## Dependencies

- You can download the model from [here](https://drive.google.com/drive/u/1/folders/1kqHjEo4z5aOUw9aQf7mNxjz8u_MwgJJ9).

- copy PLQY_ORIG.keras into a folder called "model"

  
To write a file structure in a GitHub README or similar markdown document, you would typically use a code block to represent the directory and file layout. For the given file structure, which includes a directory named models and a file named play_app, you could represent it like this:

```
PREDQY/
├── models/               # Directory containing model files
│   └── PLQY_ORIG.keras   # Keras model file
└── play_app              # python script file
│
└── requirements          # requirements
```

Model Performance on Korean PLQY Dataset

![image](https://github.com/user-attachments/assets/966a96a4-e6d6-46b3-a0f3-fab365827f6c)

## How to predict the PLQY of a molecule

First you would locate the model

![Screenshot from 2024-11-17 03-12-55](https://github.com/user-attachments/assets/c91476e5-8ffe-4359-bd18-6fb66469f491)

![Screenshot from 2024-11-17 03-13-43](https://github.com/user-attachments/assets/52114ee3-9546-450f-a293-d8d19bc0454e)


After having loaded the model, you will type in the first and second smiles string and the press "Get PLQY"
![Screenshot from 2024-11-17 03-11-37](https://github.com/user-attachments/assets/cc1dcc1f-db08-4716-be94-adb758672aca)

The model will then predict the PLQY of the two smiles strings 

### Cloning the Repository

To clone the PREDQY repository and navigate into the project directory, follow these steps:

1. Open a terminal or command prompt.

2. Clone the repository using the following command:

   ```bash
   git clone git@github.com:kikiluvbrains/PREDQY.git

3. Navigate to the cloned repository
   ```
   cd PREDQY


## Installation

### Using pip
Then install the required packages using `pip`:

```bash
pip install -r requirements.txt
```
### Finally, run the application
```
python plqy_app.py
```

