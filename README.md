# Claim Check-Worthiness of Tweets

## Project Overview
This project implements a binary classification model to identify **“check-worthy” tweets**-tweets containing claims that may require fact-checking due to their potential for widespread negative impact. The model is trained and evaluated on a labeled tweet dataset and achieves an F1-score of 80% on the test set.

---

## Tech Stack
- Data Analysis
- Support Vector Machine (SVM)
- BERT (Bidirectional Encoder Representations from Transformers)
- NLTK (Natural Language Toolkit)
- spaCy (Industrial-Strength Natural Language Processing)

---

## Repository Structure

| File/Folder                  | Description                                                    |
|-----------------------------|----------------------------------------------------------------|
| `F2_Claim_Check_Worthiness_train.csv` | Raw training data                                            |
| `F2_Claim_Check_Worthiness_test.csv`  | Raw test data                                                |
| `preprocessed_train.csv`               | Cleaned and tokenized training data                          |
| `preprocessed_test.csv`                | Cleaned and tokenized test data                              |
| `main.ipynb`                          | End-to-end notebook: data loading, preprocessing, feature extraction, model training, and evaluation |

---

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or VS Code with Jupyter extension

### Installation & Usage

1. **Clone the repo**  
   ```bash
   git clone https://github.com/janak11111/Claim-Check-worthiness-of-Tweets.git
   cd Claim-Check-worthiness-of-Tweets

3. **Run the notebook:**
- Open `main.ipynb` in Jupyter Notebook or VS Code.
- Execute all cells sequentially to reproduce data preprocessing, model training, and evaluation steps.
