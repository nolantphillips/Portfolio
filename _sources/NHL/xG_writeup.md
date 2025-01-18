# NHL xG Model

This project was my first attempt at creating an expected goals model from data scraped from the NHL. I have built a scraper that scraped NHL play by play data from the 2022-2023 to 2024-2025 seasons excluding preseason games. From there I found every Fenwick shot which is any shot attempt that was not blocked. I then cleaned and formatted the data in a manner that would be useful for the model. My final model currently has a test AUC of about 0.78, which is okay. I will continue to tune the model and find other features that may help increase the AUC metric to make the model more accurate. In the future I would like to deploy this model onto a website I create which serves as a NHL statistics website. The website would have player stats as well as team stats and would hopefully have the capability to create player cards showing advanced statistics for any NHL player of the user's choice. I need to continue to do research into advanced hockey statistics in order to make this a reality.

## Relevant Links
- [Github Repository](https://github.com/nolantphillips/xG_model)

```{tableofcontents}

```