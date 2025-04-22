# 📚 Book Genre Classification Using Metadata

This project demonstrates how **machine learning** can be used to classify the genre of a book using simple metadata features. With the growing number of digital books and the need for automated categorization in online libraries, such systems can save time and improve the organization of book collections.

---

## 🎯 Objective

To build a **supervised machine learning model** that can predict the **genre** of a book based solely on its metadata, without relying on the full text or description of the book.

---

## 📝 Problem Statement

Given a dataset of books with metadata like:
- Author's popularity score
- Book length (number of pages)
- Number of associated keywords

...the task is to classify each book into its **correct genre** such as `mystery`, `fantasy`, `romance`, etc.

---

## 🧠 ML Algorithm Used

We use a **Random Forest Classifier** because:
- It is robust to overfitting.
- It works well with small-to-medium datasets.
- It can estimate feature importance.
- It’s easy to understand and interpret.

---

## 📊 Features in the Dataset

| Feature Name        | Type    | Description                                                                 |
|---------------------|---------|-----------------------------------------------------------------------------|
| `author_popularity` | Float   | Numerical value indicating how popular the author is                        |
| `book_length`       | Integer | Total number of pages in the book                                           |
| `num_keywords`      | Integer | Number of metadata keywords/tags used to describe the book                  |
| `genre`             | String  | The target class (book genre) to predict                                    |

The dataset includes **100 samples** and multiple genre labels (multiclass classification).

---



