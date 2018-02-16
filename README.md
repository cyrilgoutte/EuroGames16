# EuroGames16

A collection for benchmarking change detection

The dataset is available here:
https://sites.google.com/site/cyrilgoutte/research-1/Euro16.zip

The collection is available as a zip file containing

* README
* gameTimes16: A list of UTC start times for the games
* 16 directories identified by the date and trigram combination for each game

Each directory contains 6 files:
* -15sec.csv: preprocessed sentiment time series with 15s bins
* -30sec.csv: preprocessed sentiment time series with 30s bins
* -60sec.csv: preprocessed sentiment time series with 60s bins
* -Timeline.tx: text file containing the reference timeline
* events_comments.html: HTML file containing events and comments
* events_comments.json: events and comments in JSON format

Other files available here allow to run simple analysis on the data. (tbd)
