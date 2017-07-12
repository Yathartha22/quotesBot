# quotesBot

quotesBot is bot that scrapes data from the famous quotes site [http://quotes.toscrape.com/](http://quotes.toscrape.com/).
It contains a spider `quotesbot` that does the work.

It will give thee result as in the form:
 
```
{
    'author': 'Douglas Adams',
    'text': '“I may not have gone where I intended to go, but I think I ...”',
    'tags': ['life', 'navigation']
}
```
## Running the spider

- Clone the repo.

- Run the spider as `scrapy crawl quotesbot` or run `scrapy crawl quotesbot -o quotes.json` to get a json file containing the output.



