# Real A.L.F.R.E.D.
A.L.F.R.E.D. was a project I created to keep track of my weekly tv shows and where to watch them.  
It has provider scrapping for the content in cloud functions on-demand.  
At some point it had cronjobs to scrape the provider, a server-side rendered frontend platform hosted on heroku, noSQL database and integration with google assitant for new episodes prompting.

## alfred-assitant
Integration with Google Assistant
- alfred-assistant: https://github.com/felipereyel/real-alfred-assistant

## alfred-platform
Currently just cloud functions that scrape the provider. But in the history there is a full server-side rendered platform
- alfred-platform: https://github.com/felipereyel/real-alfred-platform

## torrent-query
Backend engine for searching in torrent indexers returning the first result
- torrent-query: https://github.com/felipereyel/torrent-search

## chromium-alfred
An implementation of alfred for as an extension, editing the source page to add download links
- chromium-alfred: https://github.com/felipereyel/chromium-alfred

## thor
Torrent server
- thor: https://github.com/felipereyel/thor
