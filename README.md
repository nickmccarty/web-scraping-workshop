# Web Scraping Workshop

![](https://raw.githubusercontent.com/nickmccarty/web-scraping-workshop/main/images/beige-book-scraping-screenshot.jpg)

## Motivation

Knee-deep in the middle of a research project, we want to obtain the summary of economic conditions for each Federal Reserve bank district. We know that this information is containined in the archived Federal Reserve Beige Book publications.

## Approach

Web scraping is our most direct option. We will perform it using Python's `Beautiful Soup` library.

## Methodology

We have already obtained the summary of economic conditions for the years 2017 up through the most recent Beige Book publication and we know that archived reports can be viewed by year:

![](https://raw.githubusercontent.com/nickmccarty/web-scraping-workshop/main/images/beige-book-scraping-screenshot-2.jpg) 

We will specify a range of years (2011 thru 2016, specifically -- more on why in a moment) and iterate through each one in order to parse all of the Beige Book publication dates to faciliate next steps.

![](https://raw.githubusercontent.com/nickmccarty/web-scraping-workshop/main/images/beige-book-scraping-screenshot-3.jpg) 

Having collected the publication dates, we use the `year` and `month` substrings to ingest the HTML for each given Beige Book publication and parse the national summary in addition to the summary of economic conditions for each district.

![](https://raw.githubusercontent.com/nickmccarty/web-scraping-workshop/main/images/beige-book-scraping-screenshot-4.jpg) 

## Conclusion

As you can see from the results, we now have some data cleaning to do -- but we'll save that for another lesson 😆

![](https://raw.githubusercontent.com/nickmccarty/web-scraping-workshop/main/images/beige-book-scraping-screenshot-5.jpg) 

See you next time!
