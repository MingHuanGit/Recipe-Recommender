# Recipe-Recommender

## Dataset
The recipe dataset was scraped from 2 websites: 
- https://www.jamieoliver.com/recipes/category/course/mains/
- https://www.madewithlau.com/recipes

Demonstrated in the notebooks:
- web_scrape_jamie.ipynb
- web_scrape_lau.ipynb

## Installation
This project requires Python and the following libraries installed:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- re
- nltk
- wordcloud
- datetime
- unidecode
- string
- ast
- bs4
- time

## Usage
This project demonstrates the application of web scraping, data cleaning, EDA, NLP, TF-IDF vectorization, and cosine similarity. I created a function that takes in the user's input ingredients and outputs a number of recipes based on the cosine similarity scores.  

The order of reading/running the notebooks should be executed in this order:
1. web_scrape_jamie.ipynb
2. web_scrape_lau.ipynb
3. NLP_and_data_cleaning.ipynb
4. EDA_recipes.ipynb
5. model_and_function.ipynb

## License 
[GNU General Public License version 3](https://opensource.org/license/gpl-3-0/)
