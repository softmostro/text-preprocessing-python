# Text Preprocessing with Python

This Python program performs various text preprocessing techniques on a CSV file sourced from Kaggle. The program includes tokenization, stop word removal, stemming, lemmatization, TF-IDF calculation, word cloud generation, n-gram analysis, and vector space modeling (VSM).

## Requirements

* Python 3
* pandas
* numpy
* nltk
* sklearn
* wordcloud

## Installation

To install the required packages, run the following command:

**pip install pandas numpy nltk sklearn wordcloud**

## Usage
To use this program, follow these steps:

* Download a CSV file from Kaggle that contains text data.
* Load the CSV file into the program using the pandas library.
* Select the column containing the text data.
* Run the program.

The program will perform the following text preprocessing steps:

* **Tokenization**: Breaks down the text into individual words or tokens.
* **Stop word removal**: Eliminates commonly used words that do not add meaning to the text, such as "the", "and", and "it".
* **Stemming and lemmatization**: Reduce words to their root form, which can help to group together words with similar meanings.
* **TF-IDF calculation**: Determines the importance of each word in the text.
* **Word cloud generation**: Displays the most important words in the text in a visually appealing way.
* **N-gram analysis**: Identifies common phrases or patterns in the text.
* **Vector space modeling**: Represents text data in a high-dimensional space.

## Screenshots
![wordcloud](https://user-images.githubusercontent.com/97142240/221418411-3b87c1ce-540f-4234-b137-07d85de90852.png) 
## Dataset Source

**Author**: Larxel

**URL**: www.kaggle.com/datasets/andrewmvd/udemy-courses

### Dataset Description:
This dataset contains records of courses from 4 subjects (Business Finance, Graphic Design, Musical Instruments and Web Development) taken from Udemy.  Udemy is a massive online open course (MOOC) platform that offers both free and paid courses. Anybody can create a course, a business model by which allowed Udemy to have hundreds of thousands of courses. This version modifies column names, removes empty columns, and aggregates everything into a single csv file for ease of use.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
