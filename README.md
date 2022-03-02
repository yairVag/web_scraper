# Metacritic Album Charts Scraper

Metacritic is a website that that aggregates reviews of music, movies, TV shows, and games.

This program will take any Metacritic music album chart and scrape it for relevant information, including:

* Album name (and link to Metacritic album page)
* Artist name (and link to Metacritic artist page)
* Album release date
* Metascore (based on critics' reviews)
* User score (based on users' reviews)
* Album summary
* Publisher (and link to Metacritic publisher page)
* Album Genres
* Album cover
* Link to Amazon purchase page

## Example

```javascript
# Returns information about the top-rated albums of all time, 
# based on the following link: 
# https://www.metacritic.com/browse/albums/score/metascore/all/filtered?sort=desc

```


## Run Locally

### Steps: 

Clone the project

```bash
  git clone https://github.com/doronreiffman/web_scraper
```

Go to the project directory

```bash
  cd web_scraper
```

Install dependencies

```bash
  pip install -r requirements.txt
```

## Screenshots

Version 1 of the program will output a csv file called top_albums.csv in your working directory.

The link in the example produces the csv file shown below (in Pycharm and in Google Sheets, for your convenience.)

![Output in Pycharm](https://github.com/doronreiffman/doronreiffman.github.io/raw/main/output_csv_pycharm.PNG)


![Output in Google Sheets](https://github.com/doronreiffman/doronreiffman.github.io/raw/main/output_csv_sheets.PNG)



## Contributing

Contributions are always welcome!


## Authors

- [@YairVag](https://www.github.com/YairVag)
- [@doronreiffman](https://www.github.com/doronreiffman)

