# LexiGuard - Toxic Comment Classification

## Summary

**LexiGuard** is designed to combat online toxicity, fostering healthy dialogue. We aim to build a PoC Streamlit application that scores comments on their toxicity, aiding moderators in digital channels. Beneficial for companies, NGOs, and individuals, our project helps ensure safer online interactions. It features a toxic comment classifier and a dashboard for moderators to manage conversations efficiently.

## Installation

### Prerequisites

Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

### Setting up the Environment

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/lexiguard/LexiGuard.git
    cd LexiGuard
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Data Preparation

1. Download the dataset from the Kaggle Toxic Comment Classification Challenge:
    - Go to [Kaggle Challenge](https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data).

2. Place the `all_data.csv` file in the `data` folder within the project directory.

## Usage

Run the notebooks in the following order for the complete workflow:

1. `1) Data preparation for EDA.ipynb`
2. `2) Data Exploration - EDA.ipynb`
3. `3) Balancing the data - Undersampling.ipynb`
4. `4) Data cleaning for modeling and feature engineering.ipynb`
5. `5.1) Modeling Baseline.ipynb`
6. `5.2) Modeling LogisticRegression.ipynb`
7. `5.4) Modeling-RFC.ipynb`
8. `5.5) Modeling Fasttext.ipynb`
9. `5.6) Modeling-LSTM-GB.ipynb`

After running through the notebooks, execute `LSTM_streamlit.py` to launch the Streamlit application for a web interface.

## Contributors

This project is based on a collaborative effort by:

- [Bambuzera André Oliveira](https://github.com/Bambuzera)
- [CalleRosa40 Michael Schickenberg](https://github.com/CalleRosa40)
- [PurviDParmar](https://github.com/PurviDParmar)
- [ericmartinez1189](https://github.com/ericmartinez1189)