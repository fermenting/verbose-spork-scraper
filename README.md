# NPR News Scraper

Scrape NPR for news you want. Make notes on the fly.

[Scrape Fresh Articles](https://verbose-spork-scraper.herokuapp.com/scrape)

[See Articles & Make Notes](https://verbose-spork-scraper.herokuapp.com/scrape)

## Why Scrape?

While I'm passionate about news, I'm not interested in advertisements and bulky web design. This scraper grabs the essential info from a news site and displays it in a simple list. 

The scraper allows you to make notes on each article, and the notes are persistent. You can navigate away from the page and come back to your notes any time.

## Use it

Head over to the deployed app on Heroku and check it out. If there aren't any news articles listed, click on the "Scrape Fresh Articles" link to populate the list.

If you click on any of the news results besides the link, a note entry text area pops up on the right, which will allow you to take notes on articles.

If you click on the link, it will take you to the full news story.

## Technologies

This web application was built using:

* express - for routing the different functions of the app
* morgan logger - for logging when running locally
* mongoose - for database
* axios - for grabbing all the data from news sites
* cheerio - for scraping specific data

### Technologies to be used
* handlebars - to make the web design modular
* body parser - for middleware parsing

## Future Goals

As implied from the "Technologies to be used", I have a few more packages I would like to utilize. I'd love to get the whole app working flawlessly.

I would like to make it a 'save for later' function. Upon performing a scrape, I would like to check for whether a note has been entered on that article, and if so, to keep that article in the db.

I would also add more news sites, so that it can truly be my one-stop-shop for online news.

## Thanks

Thanks to Zoe for helping me deploy this monster!

