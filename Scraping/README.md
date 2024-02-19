# Scraping for factsheet automation
The factsheet automation is based on Excel due to its broad range of application and the vast user pool - meaning it is accessible to more people than a Python script. But we try to automate the data gathering separately with Python. We utilize a headless ```Selenium``` browser to tackle the lazy loading of vivino and then scrape it with ```beautifulSoup```. 

## Other features
We also included an automated plot script to export small graphs of the google Trends history for a certain wine variety. If it fits the style of the factsheets, this will be included.