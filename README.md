# quotesBot

quotesBot is bot that scrapes data from the famous quotes site [http://quotes.toscrape.com/](http://quotes.toscrape.com/).

It will give thee result as in the form:
 
```
{
    'author': 'Douglas Adams',
    'text': '“I may not have gone where I intended to go, but I think I ...”',
    'tags': ['life', 'navigation']
}
```
## How to use:

- Clone the repo.

- Run the following command `scrapy crawl quotesbot` or run `scrapy crawl quotesbot -o quotes.jsons` to get a json file containing the outpu.



