# Custom-Search-Engine

# Features
- Ad and trackers blocker
- DB Integraton for caching the results
- Upto 20 most relevent google search result for the query.
- Google Search Engine API used.

# Setup
- Clone this repository
- Run `pip install -r requirements.txt`
- Add File `blacklist.txt` and list the ad and tracker urls from [here](https://raw.githubusercontent.com/notracking/hosts-blocklists/master/dnscrypt-proxy/dnscrypt-proxy.blacklist.txt).
- Add API Key for programmable search engine [Custom Search API](https://developers.google.com/custom-search/v1/introduction), You can create one [here](https://programmablesearchengine.google.com/controlpanel/all), Create an [API key](https://console.cloud.google.com/apis/credentials) for the engine.
- Add these API key(SEARCH_KEY) and cx(SEARCH_ID) in `settings.py`
- python -m flask run
- Go to `http://localhost:5000/` on your browser	
