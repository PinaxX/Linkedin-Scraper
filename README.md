# Linkedin-Scraper
This notebook can scrape posts from Linkedin using user-defined tags.
Since there are no official APIs introduced yet, this is the best we can do.

Works fine in 02/28/2021. If Linkedin changes URLs or login strategies it'll need modifications.

There are 4 parameters that you need to modify: username, password, hashtags and SCROLL_PAUSE_TIME. You can find the first 2 in the second code cell and the other 2 can be found in the third cell.

The scraped data consists of post's text, post's relative date and its author. The last cell will save the data into a CSV file.
