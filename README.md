# Text-Preprocessing-Techniques-Gen-AI-

# IMDB Movie Review Preprocessing

This project demonstrates various data preprocessing techniques applied to the IMDB Dataset of 50k movie reviews. The goal is to clean and prepare the text data for further analysis, such as sentiment analysis or topic modeling.

## Dataset

The project uses the IMDB Dataset of 50k movie reviews, available on Kaggle:

>[Dataset can be found here](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)


## Preprocessing Steps

The following preprocessing steps are performed on the movie review data:

1. **Lower Case Operation:** Converts all text to lowercase.
2. **Removing HTML Tags:** Eliminates HTML tags from the reviews.
3. **Removing URLs:** Removes any URLs present in the text.
4. **Punctuation Handling:** Removes or replaces punctuation marks.
5. **Chat Conversion:** Converts chat abbreviations to their full forms (e.g., ASAP to As Soon As Possible).
6. **Incorrect Text Handling:** Attempts to correct spelling errors using TextBlob.
7. **Stop Words Removal:** Removes common words that do not carry significant meaning (e.g., "the", "a", "is").
8. **Emoji Handling:** Removes or converts emojis to text representations.
9. **Tokenization:** Splits the text into individual words or sentences.
10. **Stemming:** Reduces words to their root form using Porter Stemmer.
11. **Lemmatization:** Reduces words to their base form using WordNet Lemmatizer.

## Code

The code for each preprocessing step is provided in the Jupyter Notebook `IMDB_Movie_Review_Preprocessing.ipynb`. You can find detailed explanations and examples in the notebook.

## Libraries Used

The project utilizes the following libraries:

- pandas
- re
- string
- textblob
- nltk
- emoji

Make sure to install these libraries before running the code.

## Usage

1. Download the IMDB Dataset from Kaggle and place it in the project directory.
2. Open the Jupyter Notebook `IMDB_Movie_Review_Preprocessing.ipynb` in Google Colab or your local environment.
3. Execute the code cells to perform the preprocessing steps.
4. The preprocessed data can then be used for further analysis.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
