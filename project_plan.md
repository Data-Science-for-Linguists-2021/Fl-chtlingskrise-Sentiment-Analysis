## Emily Martin Project Plan, eem80@pitt.edu
Sentiment Analysis of the 2015 Refugee Crisis
#### The Data
###### Where will it come from?
The data would be scraped from several well known German newspapers across the political spectrum. The following are what I plan on using, although some additions/changes are possible as I begin scraping and working with the data:

- Die Tageszeitung, https://taz.de (left-wing, green), daily
- Der Zeit, https://www.zeit.de/index  (centrist/liberal), weekly
- Der Süddeustche Zeitung, https://www.sueddeutsche.de (center-left, left-liberal), daily
- Frankfurter Allgemeine Zeitung, https://www.faz.net/aktuell/ (center-right, moderately conservative-liberal), daily NOPE https://www.faz.net/allgemeine-nutzungsbedingungen-von-faz-net-und-seinen-teilbereichen-11228149.html
- Junge Freiheit, https://jungefreiheit.de (alt-right, very conservative bordering on nationalistic), weekly

_I got the political leanings from this page: https://en.wikipedia.org/wiki/List_of_newspapers_in_Germany_



#### Goals
The end goal would be to figure out if and how sentiments towards refugees and migrants changed during the refugee crisis in 2015. The governments decision to let so many refugees in was very controversial and Germany ended up very polarized, resulting in a lot of government backlash and the rise of the AfD ("Germany for the Germans" kind of party) and alt-right there. Categorizing the articles into negative and positive is one part, but it would also be interesting to potentially analyze more specifics such as what words do they use for refugees and the mood/modality used (there are some fun "tenses" in German specifically for relaying things you don't agree with).

#### Potential tools
**Scrapy** -To scrape the articles

**BERT** -Can summarize texts! See below

**SpaCy**, **Gensim** -Both of these libraries support German

#### Analysis
After being scraped, cleaned, organized, lemmatized, etc, one option to explore would be text summarization as a new and improved middle step in my analysis. BERT has a summarization feature that would be fun to try out (I believe it works with SpaCy). This could mean I would not have to work only with many very long articles, which would be a time saver (also this is new stuff and therefore very exciting)
There are several methods for sentiment analysis, and I have yet to decide the best one for this project. A simple positive/negative classifier is probably not nuanced enough for what I want to look at, so a more fine-grained approach is probably needed. Again, as I begin really working with the data I think I will have a better sense of what I need.
My hypothesis is that more conservation newspapers will have more negative articles about refugees while their more liberal counterparts will have more positive ones. The same distribution will probably be true of the sentiments towards Merkel and other politicians who were so pro-refugee.
#### Presentation
Presumably powerpoint, including screen shots of my JNB and plots/graphs of my results
