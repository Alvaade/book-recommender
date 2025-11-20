# Book Recommender

The Book Recommender is a data science project that implements a Singular Value Decomposition (SVD) algorithm, a collaborative filtering technique based on matrix factorization, to create a personalized book recommendation system. The project's primary goal is to train a machine learning model that can accurately predict a user's rating for a book they have not read and suggest relevant reading material.

The system is trained using the Goodbooks-10k-extended dataset, which is derived from Goodreads data. 

Link to the dataset: https://github.com/malcolmosh/goodbooks-10k-extended

---

## Features

- Collaborative filtering using the SVD algorithm
- Predicts user ratings on a 1-5 star scale with an average error of approximately 0.64 (MAE)
- Generates a personalized book suggetsions based on learnt user preferences
- Utilizes a large dataset with nearly 6 million ratings from over 53 000 users

---

## Techical Specifications

- **Algorithm**: Singular value decomposition (collaborative filtering)
- **Environment**: Python 3, Jupyter Notebook
- **Libraries**: scikit-surprise, pandas, matplotlib
- **Dataset**: Goodbook-10k-extended (`ratings.csv` and `books_enriched.csv`)

---

## Getting Started

Requirements:
- Python 3 and pip
- The required Python libraries
- Internet connection to fetch the dataset from the repository links

1. Clone the repository:
```bash
git clone https://github.com/Alvaade/book-recommender.git
cd book-recommender
```

2. Install dependecies
```bash
pip install pandas scikit-surprise matplotlib
```
If installation of `scikit-surprise` fails with a "Microsoft Visual C++ 14.0 or greater is required" error, you must install the Microsoft C++ Build Tools (part of Visual Studio Build Tools) to compile the C extensions.

3. Run the application (Jupyter Notebook):
- Start a Jupyter Notebook server:
```bash
jupyter notebook book_recommneder.ipynb
```
- Open and run the cells in `book_recommender.ipynb`

---

## Contributors
- Ade Aiho
- Tommi Halla
- Heta Hartzell
- Jonne Roponen
