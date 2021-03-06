# enfsolar.com Scraper
Given a list of URLs, as a .csv file, the program extracts company contact information from each individual URL.

## Installation
```pip install -r requirements.txt```

or 

```peotry install```

## Using with selenium
requires having hombrew installed, how to install: https://brew.sh

```homebrew``` is a macOS package manager

then 

```brew install cask```

### Installation
1. ```brew cask install firefox```, or just download it https://www.mozilla.org/en-US/firefox/new/
2. ```brew install geckodriver```, install the geckodriver for selenium

## Running the program
1. Scrape & download:

    ```python main.py --scrape --csv-file /path/to/csv/file```
    
2. Parse & write report:

    ```python main.py --extract```

### Params

```--scrape```, download HTML content of each URL 

```--headless```, do no show the selenium browser window, when scraping 

```--extract```, extracts contact information from each file

```--csv-file```, path to the input CSV file

