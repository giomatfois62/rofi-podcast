# rofi-podcast
A rofi menu to browse and play podcasts from [rss.com](https://rss.com/community/).  

History of played podcasts is kept in ~/.cache and can be browsed selecting the "Recently Played" entry in the categories menu.  

A python script using requests and lxml modules is provided to scrape the website when new series are added.
Series episodes are instead fetched every time a serie is selected, so they will be always up to date.  

Podacasts are streamed by default to mpv, set the *PODCAST_PLAYER* env variable to change default player (putting xdg-open will use the default browser).

Podcast categories
![podcast categories](https://github.com/giomatfois62/rofi-podcast/blob/main/screenshots/pocast_categories.png)
Podcast series 
![podcast series](https://github.com/giomatfois62/rofi-podcast/blob/main/screenshots/podcast_series.png)
Podcast episodes 
![podcast episodes](https://github.com/giomatfois62/rofi-podcast/blob/main/screenshots/podcast_episodes.png)
