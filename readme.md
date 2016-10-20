# Tweets From The Third 2016 Presidential Debate

This repo contains data on roughly 885,222 debate tweets. However, to make the data compliant with Twitter's terms of service, the public data only contains tweet IDs.

To convert the list of tweet IDs into a full dataset, run retrieve_tweets.ipynb using your own Twitter API keys.

## Run command lines

- python miner_#clinton.py 'full_data/hashtag_clinton' \#clinton
- python miner_#debate.py 'full_data/hashtag_debate' \#debate
- python miner_#hillary.py 'full_data/hashtag_hillary' \#hillary
- python miner_#trump.py 'full_data/hashtag_trump' \#trump
- python miner_clinton.py 'full_data/clinton' clinton
- python miner_hillary.py 'full_data/hillary' hillary
- python miner_trump.py 'full_data/trump' trump
