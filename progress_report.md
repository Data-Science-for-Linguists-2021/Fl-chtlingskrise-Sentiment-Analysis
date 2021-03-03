### First progress report
Created GitHub repository and added files.
Began looking into programs and library to help me with my work - Scrapy, SpaCy, BERT, Gensim.

### 2/27/21
Several snags have been hit:
1- Frankfurter Allgemeine Zeitung (FAZ) explicitly forbids data mining of any kind. https://www.faz.net/allgemeine-nutzungsbedingungen-von-faz-net-und-seinen-teilbereichen-11228149.html
2- Others the documentation was hard to find so I am waiting to hear back from several emails I sent them (it is the weekend and they are in Europe so I definitely don't expect an answer in the next 2 days)
3- Der Zeit, which has an API, does not easily allow you to see/scrape the actual article text, so I emailed them as well hopefully there will be an easy solution, if not I will use the API to get the URL's and go from there.
4- Still waiting to hear from Junge Freiheit because I could not find anything in the terms of use.

### 2/28/21
Managed to retrieve 100 relevant articles from Der Zeit, lots of work to be done on them and I need a lot more but I should wait to find out about copywrite, hoping to hear tomorrow.

### 3/2/21
Zeit article text (100 articles) have been added to my dataframe. More cleanup is needed but for now they are at least cohesive texts and at first overview don't appear too messy (weird links/formatting that made it through). TAZ does not let you search specifically by date without having a particular subscription, so I manually collected a few links and had Beautiful Soup get the text from them. Pitt does have access but that page does not have the links (and I am quite sure it would be very hard to scrape) so manual collection it is. Annoyingly there are articles in 2 formats and I can only use one (the other does not have consistent 'div's. I managed to do a test run and compiled a dictionary of 11 articles and URL's and another with URL's and dates. I will try to add more soon, but at least I know the code works.
