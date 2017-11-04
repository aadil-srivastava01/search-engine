# search-engine

A search engine that worls on Google's Page rank alorithm for ranking/displaying webpages.

Project is comprised of three files

1)crawler.py- This python file activates a webcrawler(using beautiful soup library) which crawls web addresses.
2)make_index.py- This file prepares the list if webpages crawled by the web crawler and ranks the according to the page arank algorithm.
3)new_lookup.py- This file takes the user input and fethes the result from the index created by make_index.py.