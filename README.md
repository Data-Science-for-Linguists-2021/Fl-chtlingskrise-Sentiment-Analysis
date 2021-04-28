# Flüchtlingskrise-Sentiment-Analysis
## Emily Martin, Spring 2021, eem80@pitt.edu

## Description
Sentiment analysis of German newspapers across the political spectrum during the refugee crisis in 2015 using SpaCy and the pipeline extension Sentiws. The goal was to determine if there was a difference in sentiments towards refugees between right-leaning and left-leaning new sources. This was done using [Sentiws](https://spacy.io/universe/project/spacy-sentiws), a SpaCy extension for German sentiment analysis, which I also analyzed further to try and understand its functions and short-comings.

Here you can find my [guestbook](https://github.com/Data-Science-for-Linguists-2021/Class-Lounge/blob/main/guestbooks/guestbook_emily.md)

## The Data
I scraped my data using urllib and beautiful soup from [Der Zeit](https://www.zeit.de/index?utm_referrer=https%3A%2F%2Fwww.google.com), one of the largest weekly newspapers in Germany: centrist/liberal in its political leanings; [Die Tageszeitung](https://taz.de), a daily German newspaper with a modest circulation: leans left-wing/green; [Der Süddeutsche Zeitung](https://www.sueddeutsche.de), a daily newspaper with a very wide circulation (second largest after Der Zeit): leans left-liberal; and [Junge Freiheit](https://jungefreiheit.de), a small weekly newspaper: fairly strong right-wing leanings. Because of copyright issues I am not able to share the data itself, however, my scraping scripts along with the taz_urls.txt in MY SCRAPING FOLDER can be shared and will let anyone interested in the future acquire the data for themselves.

## Repo Directory

- [README.md](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/README.md): you are here ;)
- [LICENSE.md](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/LICENSE.md): information about the license for this project.
- [scraping](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/tree/main/scraping): a folder with  all my scraping scripts and the manually compiledTAZ links
    - [Junge_Freiheit.ipynb](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/scraping/Junge_Freiheit.ipynb): code for scraping Junge Junge_Freiheit. Here is the [nbviewer version](https://nbviewer.jupyter.org/github/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/scraping/Junge_Freiheit.ipynb)
    - [taz.ipynb](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/scraping/taz.ipynb): code for scraping Die Tageszeitung. Here is the [nbviewer version](https://nbviewer.jupyter.org/github/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/scraping/taz.ipynb)
    - [taz_urls.txt](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/scraping/taz_urls.txt): manually compiled links for scraping taz
    - [zeit.ipynb](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/scraping/zeit.ipynb): code for scraping Der Zeit. here is  the [nbviewer version](https://nbviewer.jupyter.org/github/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/scraping/zeit.ipynb)
    - [Süddeutsce_zeitung.ipynb](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/scraping/Süddeutsche_zeitung.ipynb): code for scraping Der Süddeutsche Zeitung. Here is the [nbviewer version](https://nbviewer.jupyter.org/github/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/scraping/Süddeutsche_zeitung.ipynb)

- [Presentation.ipynb](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/Presentation.ipynb): a notebook with the sentiment analysis and sentiws exploration
  - [Here](https://nbviewer.jupyter.org/github/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/Presentation.ipynb) it is in nbviewer with working links!
- [project_plan.md](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/project_plan.md): my original proposal and plan for the project.
- [progress_report.md](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/progress_report.md): a report of my progress throughout the semester.
- [DS_presentation.pdf](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/blob/main/DS_presentation.pdf): a pdf version of my class presentation.
- [html pics](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/tree/main/html%20pics): pictures of the html for each scraped site.
- [images](https://github.com/Data-Science-for-Linguists-2021/Fluechtlingskrise-Sentiment-Analysis/tree/main/images): a folder with all the images generated in my notebook.
