# EuroGames16

A collection for benchmarking change detection.

## Reference

This data is used in our paper:

Goutte, C., Wang, Y., Liao, F., Zanussi, Z., Larkin, S. and Grinberg, Y. (2018) EuroGames16: Evaluating Change Detection in Online Conversation, Proc. 11th Language Resources and Evaluation Conference (LREC-2018).

This would also be the proper bibliographical reference for that resource.

## Availability

The dataset is available here:

https://sites.google.com/site/cyrilgoutte/research-1/Euro16.zip

The collection is available as a zip file containing

* README
* gameTimes16: A list of UTC start times for the games
* 16 directories identified by the date and trigram combination for each game

Each directory contains 6 files (where - stands for the trigram combination for each game):
* -15sec.csv: preprocessed sentiment time series with 15s bins
* -30sec.csv: preprocessed sentiment time series with 30s bins
* -60sec.csv: preprocessed sentiment time series with 60s bins
* -Timeline.tx: text file containing the reference timeline
* events_comments.html: HTML file containing events and comments
* events_comments.json: events and comments in JSON format

Other files available here allow to run simple analysis on the data. (tbd)

## Licence

This data is made available for benchmarking and evaluation purposes.

Please contact us if you'd like to apply the preprocessing to your own data.
