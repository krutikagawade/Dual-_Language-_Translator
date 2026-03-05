# Dual Language Translator (English → French & Hindi)

## Project Description

This project is a **Machine Learning based Dual Language Translator**.
It translates English words into **French and Hindi simultaneously**.

The system only translates **English words that contain 10 or more letters**.
If the word has **fewer than 10 letters**, the system displays the message:

`Upload Again`

## Features

* Translate English words into **French and Hindi**
* Condition check for **minimum 10 letters**
* GUI interface for user input and output
* Custom dataset used for training the model
* Built using Python and Machine Learning

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* Scikit-learn
* Tkinter (for GUI)

## Dataset

The dataset contains three columns:

* English
* French
* Hindi

Example:

| English     | French        | Hindi        |
| ----------- | ------------- | ------------ |
| development | développement | विकास        |
| environment | environnement | पर्यावरण     |
| technology  | technologie   | प्रौद्योगिकी |

File used:

`translator_dataset.csv`

## How to Run the Project

1. Install required libraries

```
pip install pandas scikit-learn
```

2. Open **Jupyter Notebook**

3. Run the notebook:

```
Dual_Language_Translator.ipynb
```

4. Enter an English word in the GUI.

5. The system will:

* Translate if the word has **10 or more letters**
* Display **Upload Again** if the word has fewer than 10 letters.

## Project Structure

```
Dual-Language-Translator
│
├── Dual_Language_Translator.ipynb
├── translator_dataset.csv
├── README.md
└── requirements.txt
```

## Example Output

Input:

```
development
```

Output:

```
French: développement
Hindi: विकास
```

Input:

```
school
```

Output:

```
Upload Again
```

## Author

Krutika Dattaram Gawade
