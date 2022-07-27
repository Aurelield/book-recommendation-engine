# 'Which books could we recommend you?: a book recommendation engine






<img src="https://images.theconversation.com/files/45159/original/rptgtpxd-1396254731.jpg?ixlib=rb-1.1.0&q=30&auto=format&w=600&h=400&fit=crop&dpr=2" width="1280" height="650">



<!-- Add banner here -->

This project aims to built a book recommendation engine with machine learning. This project has been mainly inspired by another project in this article https://randerson112358.medium.com/build-a-book-recommendation-system-using-python-machine-learning-ca6259d70319

The dataset has been taken from https://www.kaggle.com/datasets/sootersaalu/amazon-top-50-bestselling-books-2009-2019?resource=download.



# Table of contents

<!-- After you have introduced your project, it is a good idea to add a **Table of contents** or **TOC** as **cool** people say it. This would make it easier for people to navigate through your README and find exactly what they are looking for.

Here is a sample TOC(*wow! such cool!*) that is actually the TOC for this README. -->

- [Table of contents](#table-of-contents)
- [Dataset contents](#dataset-contents)
- [Goal](#goal)
- [Demo Preview](#demo-preview)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Issues](#issues)

## Dataset contents

 Data originally come from  the Amazon website from 2009 to 2019. The dataset contains 550 books.
 data has been categorized into fiction and non-fiction using Goodreads
 The dataset contains 550 rows (with some duplicate values).
 One row means one book data.
 The table has 7 columns:
- Name (Title of the book)
- Author of the book
- User rating: the score is out of 5 stars
- Reviews
- Price (As at 13/10/2020)
- Year: the Year(s) it ranked on the bestseller
- Genre: Whether fiction or non-fiction

## Goal

The project aims to build a content based recommendation engine using Python and machine learning.
In this project the content based recommendation engine ranked books according to the similarity of the recommended books and the highest rated book. In order to get this rank, we used a function called similarity scores.

# Main steps

- I cleaned the dataset from duplicate rows. I wanted to get only unique rows in order to properly rank the books based on the "user rating" column.
- I printed the book with the highest rating.
- I choose the attributes(columns)that could be helpful to determine recommended books that the user may like. I used 2 columns from the dataset: Name and Authors. I created another column called "book_id" in order to get the cosine similarity scores with the new 'fit_tranformed' column "combined_features".
- I sorted new data after the cosine similarity scores.
- I printed the five top recommended books based on selected columns and the highest rated book.

## Demo Preview



<img width="608" alt="Capture d’écran 2022-07-07 à 01 25 30" src="https://user-images.githubusercontent.com/82478538/177659473-de19db27-20fd-4817-b2c7-83d80902759d.png"> <img width="584" alt="Capture d’écran 2022-07-07 à 01 26 18" src="https://user-images.githubusercontent.com/82478538/177659520-30a6050b-3775-4772-ab42-bc445075322d.png"> <img width="563" alt="Capture d’écran 2022-07-07 à 01 26 58" src="https://user-images.githubusercontent.com/82478538/177659528-1a0533b2-c231-4d8a-a446-659adb8f05f9.png"> <img width="522" alt="Capture d’écran 2022-07-07 à 01 27 22" src="https://user-images.githubusercontent.com/82478538/177659532-b10aeb3d-d53f-4cc1-83c2-39199448feca.png">


## Installation

Here are the command lines of the production environment.

```sh

```


## Usage




## Results

Here are some results from the data analysis following the order of the questions.



## Issues
[(Back to top)](#table-of-contents)
