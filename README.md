# Netflix Titles Crawler
This is a program that will get a list of all movie and TV show titles in Netflix's library.

## Running the crawler
[Install Selenium](http://docs.seleniumhq.org/download/) I downloaded the Selenium GeckoDriver v0.22.0 (https://github.com/mozilla/geckodriver/releases) and the change the PATH env variable to include the director where the GeckoDriver executable is located

Install Firefox. This is the browser I use with Selenium.

Install [Node.js](https://nodejs.org).

Install dependencies

```
npm install
```

Add your Netflix email and password to the following variables in the `.env` file:

```
EMAIL=
PASSWORD=
```

Run the crawler

```
npm start
```

The crawler will go through all alphabet search pages put the results in the `output/` folder, in an aggregate `output/All-Movies` file.

# Credits
This project was created based on the code from Eric Lewis (https://github.com/ericandrewlewis): https://github.com/ericandrewlewis/netflix-library-indexer/

I just did some simple modifications to make it work on my side.