# Mike's fantasy baseball and football Jupyter notebooks

## Draft Prep

The whole process is split into 3 notebooks:

1. [Scraping all expert draft rankings](http://nbviewer.jupyter.org/github/MikeTrizna/fantasy_sport_data/blob/master/Scraping%20all%20expert%20draft%20rankings.ipynb)

	Start out by first scraping the FP expert list, and then using that list to scrape each expert's rankings.

2. [Filtering and summarizing expert rankings](http://nbviewer.jupyter.org/github/MikeTrizna/fantasy_sport_data/blob/master/Filtering%20and%20summarizing%20expert%20rankings.ipynb)

	Now that all of the expert ranking data is downloaded and saved, I use pandas to calculate mean/median rankings and then rank by position. Finally, it's all saved to a spreadsheet.

3. [Making graphs]()

	Finally, take all of the summary rankings and combine with the raw expert ranks to produce nice Seaborn plots in PDF format for easy crossing-out on draft day.

	Here's a quick preview of what the plots look like:

