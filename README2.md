# Book Recommendation System

## Overview
This project implements a **Book Recommendation System** using the **Goodbooks-10k dataset**.  
It recommends books based on user preferences by analyzing book ratings and similarities.  
The project demonstrates how recommendation systems work using **Collaborative Filtering** and **Content-Based Filtering** approaches.


## Dataset
The **Goodbooks-10k dataset** contains:
- **Books metadata**: title, authors, publication year, ISBN, image URL, etc.
- **Ratings data**: ratings given by users (from 1 to 5 stars).
- **Tags & genres**: book themes, categories, and keywords.

The dataset consists of:
- **Books.csv** → Information about 10,000 books.
- **Ratings.csv** → Over 6 million ratings from users.
- **Tags.csv** → User-generated tags for books.
- **Book-Tags.csv** → Mapping between books and tags.

Source: [Goodbooks-10k on Kaggle](https://www.kaggle.com/zygmunt/goodbooks-10k)



## Project Flow
1. **Data Loading & Exploration**
   
2. **Data Preprocessing**
   
3. **Exploratory Data Analysis (EDA)**
  
4. **Recommendation Models**
   
5. **Model Evaluation**
   
6. **Results & Recommendations**


## Project Structure

```plaintext
Book-Recommendation-System/
│
├── data/ 
│   ├── books.csv               # Book details (book_id, title, authors, etc.)
│   ├── ratings.csv             # Ratings given by users to books
│   ├── tags.csv                # Mapping of tag_id to tag names
│   ├── book_tags.csv           # Mapping of books to tags
│   ├── to_read.csv             # List of books users want to read
│ 
├── notebooks/ 
│   ├── Book_Recommendation_System.ipynb  # Main Jupyter Notebook for model building & analysis
│ 
├── src/
│   ├── __init__.py
│   ├── data_preprocessing.py   # Functions for loading and cleaning dataset
│   ├── recommendation.py       # Core recommendation functions
│   ├── visualization.py        # Graphs & plots for EDA
│
├── README.md                   # Project documentation
├── requirements.txt            # List of Python dependencies
├── .gitignore                  # Ignore unnecessary files
└── LICENSE                     # License file (if applicable)
```




## Technologies Used
- **Python** (NumPy, Pandas, Matplotlib, Seaborn)
- **Scikit-learn**
- **Surprise** (for collaborative filtering)
- **Jupyter Notebook**



## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/book-recommendation-system.git
   cd book-recommendation-system
