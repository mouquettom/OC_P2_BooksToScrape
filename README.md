# OpenClassrooms_P2_BooksToScrape

## Documentation

This script retrieves details of all books in the entire library from the home page url :
http://books.toscrape.com

Details :

The script goes through all the categories, then all the pages in those categories, to retrieve 
all the URLs for all books. For each URL, the script extracts book information : ['Category', 'Title',
'Price', 'Stock', 'Star', 'Description', 'Image', 'URL', 'UPC', 'Product Type', 'Price (excl. tax)', 
'Price (incl. tax)', 'Tax', 'Nb of reviews']

There is one .csv file per category, and the book images are downloaded and stored in a folder called 'Images'.

## Installation

Start by installing Python. Then launch the console, move to the folder of your choice and clone the repository:

- git clone https://github.com/mouquettom/OC_P2_BooksToScrape/tree/master

Go to the OC_P2_BooksToScrape folder, then create a new virtual environment:

- python -m venv env.

Then activate it. 

### Windows:

- env\scripts\activate.bat

### Linux:

- source env/bin/activate

All that remains is to install the required packages:

- pip install -r requirements.txt

You can now run the script:

- python3 books_toscrape.py