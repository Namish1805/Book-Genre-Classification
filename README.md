# 📚 Book Genre Classification using Metadata

This project aims to classify books into genres based on their metadata features such as **author popularity**, **book length**, and **number of keywords**. We use machine learning techniques to build and evaluate a classifier.

## 🔍 Problem Statement

Given metadata about a book, predict its genre. The goal is to help categorize books efficiently without needing to manually read or tag them.

### Features used:
- `author_popularity` – A numerical score showing how popular the author is.
- `book_length` – Total number of pages in the book.
- `num_keywords` – Number of keywords/tags associated with the book.

### Target:
- `genre` – The book's genre (e.g., mystery, fantasy, etc.)

---

## 🧠 Model Used

We use a **Random Forest Classifier**, which is an ensemble machine learning model that combines multiple decision trees to improve accuracy and avoid overfitting.

---

## 🛠️ Installation & Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/book-genre-classification.git
   cd book-genre-classification
