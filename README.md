# Book Recommender System

This project implements a Book Recommender System using both **Popularity-Based** and **Collaborative Filtering** techniques. It provides book recommendations based on user input or the most popular books. The system uses a dataset that includes books, user ratings, and book metadata.

## Features

- **Popularity-Based Recommendation:** Recommends the top 50 most popular books based on the number of ratings and average ratings.
- **Collaborative Filtering Recommendation:** Recommends books similar to a given book using cosine similarity between user ratings.
- **Flask Web App:** A simple web interface built with Flask for users to get recommendations by entering a book title.

## Technologies Used

- **Python**: Core programming language for data processing, model creation, and Flask API.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Scikit-learn**: For computing cosine similarity.
- **Flask**: A lightweight web framework to deploy the recommendation system.
- **HTML/CSS**: For the front-end design of the website.
- **Bootstrap**: For responsive design and components.
- **Pickle**: For saving and loading model data (such as ratings and book details).

## Dataset

The system uses the following datasets:

1. **Books.csv**: Contains book details such as title, author, and ISBN.
2. **Users.csv**: Contains user information, including user ID and age.
3. **Ratings.csv**: Contains user ratings for each book, linked by ISBN.

The datasets are used for both training the recommendation models and displaying book details.

## Run the Application
To run the Flask app, execute the following command:
python app.py

The application will be available at http://127.0.0.1:5000 in your web browser.

## Usage
**Home Page** :
The home page displays the Top 50 Popular Books, including details such as title, author, number of ratings, and average rating.

**Recommendation Page** : 
On the recommendation page, enter a book title, and the system will suggest similar books based on collaborative filtering. You will receive recommendations with the book's title, author, and an image of the book cover.

**Book Details** : 
The system also provides detailed information about books, including the number of ratings and average rating.

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/book-recommender-system.git
cd book-recommender-system
