# Project 2
My database of Dungeons and Dragons Monsters.

# Reproducing the Report

You'll need to download the text files, because they contain the data that was previously scraped from the internet. The Rmd file will import these files from your working directory. 
The code from the original scrape is still in the report if you'd like to verify that it functions, but it is commented because it scrapes from over 900 unique urls, and takes about one lunchtime to run. That happens twice, once for the core data, and again for the images, so that they can be joined. If you'd like to do the scrape, you can uncomment the lines of code directly under the warnings:

#Scraping monster data from every page
#TAKES A LONG TIME TO RUN

and

#Grabbing both the real images and the theoretical links for a little trick later
#TAKES A LONG TIME TO RUN

Besides that, the report may take a bit to load, because it employs many graphs, including a graph gallery at the end, and uses many web images throughout the report, so give it a second to knit.
