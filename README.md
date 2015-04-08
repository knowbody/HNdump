HNdump
===

### About

So this repo contains the historical data from [Hacker News](http://news.ycombinator.com). The data reaches as far as 6th September 2010.

All data has been taken from great HN clone - http://hckrnews.com, by [Wayne Larsen](https://github.com/wvl).


### The data

Each JSON file contains all stories which landed on the front page in the given day.

The single story is represented in this format:

```json
{
  "date": 1428277552,
  "homepage": false,
  "link_text": "The success of Project Ara depends on Toshiba",
  "comments": 18,
  "source": "www.araprototype.com",
  "points": 34,
  "link": "http://www.araprototype.com/uncategorized/toshiba-modules-project-ara/",
  "time": "1428274635",
  "submitter": "ElvisMa",
  "type": "story",
  "id": "9325611"
}
```

### Why?

You can read more about why I have/needed this data on my [blog post](https://medium.com/@knowbody/when-karma-8d1aeb1ef787).
In case you don't want to read the blog post:  

**tl;dr**  
Main reason why this repo exists, because I was thinking by publishing the way you could get the data from hckrnews page
could be harmful for the page, so instead of that you can just get the data from here. Although full credit for the data should go to Wayne.


Feel free to contribute / update this repo with a new data
