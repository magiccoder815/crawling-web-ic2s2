[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/comp-strat/web-crawling-ic2s2-2022.git/HEAD)

# Web-Crawling: Essential Tools for Wrangling Web Data in Python
## [A workshop at IC2S2 2022](https://iscss.org/ic2s2/conference/)

## Overview

When it comes to data collection, web-crawling (i.e., web-scraping, screen-scraping) is a common approach in our increasingly digital era--and a common stumbling block. With such a wide range of tools and languages available (Selenium, Requests, and HTML, to name just a few), developing and implementing a web-crawling pipeline is often a frustrating experience for researchers--especially those without a computer science background.

Whatever your background, this workshop will give you the foundation to use web-crawling in your research. We will tackle common problems including collecting web addresses/URLs (by automated Google search), downloading website copies (with wget), non-scalable website scraping (with requests), and scalable crawling of text (with scrapy). No web-crawling experience is required, but some Python know-how is expected. 


## Workshop goals

* Understanding the building blocks for digital data collection via web-crawling and -scraping
* Intuitions around the uses and limits of:
  - APIs (Application Programming Interfaces)
  - Exploiting website structure (HTML/CSS)
  - Web-crawling for research at scale
* Knowledge of common problems in web-crawling and their fixes, like:
  - Nested websites --> vertical crawling (link extraction)
  - Getting blocked --> polite pauses between server requests
* Hands-on skill with: 
  - Collecting domains to scrape
  - Non-scalable website scraping with _Requests_
  - Parsing website text with _BeautifulSoup_
  - Crawling at scale with _Scrapy_


## Prerequisites

We will get our hands dirty implementing an assortment of simple web-crawling tools. To follow along with the code—which is the point—will need some familiarity with Python and Jupyter Notebooks. If you haven't programmed in Python or haven’t used Jupyter Notebooks, please do some self-teaching before this workshop using resources like those listed below. 


## Getting started & software prerequisites

For simplicity, just click the "Launch Binder" button (at the top of this Readme) to create a virtual environment ready for this workshop. It may take a few minutes; if it takes longer than 10, try again.

If you want to run the code on your computer, you have two options. You could use [Anaconda](https://www.anaconda.com/what-is-anaconda/) to make installation easy: [download Anaconda](https://www.anaconda.com/download/). Or if you already have Python 3.x installed with the full list of libraries listed under `requirements.txt` or don't mind installing everything in a [virtual environment](https://python.land/virtual-environments/virtualenv) (best practice if working locally), you're welcome to clone this repository and follow along on your own machine. You can also install all the necessary packages like so: 

```
pip3 install -r requirements.txt
```


## Open-Access Resources 

* [Slides (previous version)](http://bit.ly/slides-crawl-2021) (also in folder above)

### Python and Jupyter Notebooks

* [Introduction to Jupyter Notebooks (Real Python)](https://realpython.com/jupyter-notebook-introduction/)
* [Quick Python intro (a Jupyter Notebook)](https://github.com/jhaber-zz/nlp-python-2020/blob/master/solutions/intro-to-python.ipynb)
* [Great book on Python (with exercises): _Python for Everybody_ (Charles Severance)](https://www.py4e.com/book.php)
* [Official Python Tutorial](https://docs.python.org/3/tutorial/index.html)
* [Python tutorials for social scientists (Neal Caren)](https://nealcaren.github.io/python-tutorials/)

### Web-crawling with Scrapy & friends

* [Official Scrapy tutorial](https://docs.scrapy.org/en/latest/intro/tutorial.html)
* [Blog on using item pipelines in Scrapy](https://medium.com/swlh/how-to-use-scrapy-items-05-python-scrapy-tutorial-for-beginners-f25ff2dceaa9)
* [Storing Scrapy output to MongoDB (humongous database!)](https://realpython.com/web-scraping-with-scrapy-and-mongodb/)
* [Examples of using wget to download from websites](https://phoenixnap.com/kb/wget-command-with-examples)
* [Scale Scrapy with a pre-cooked Docker assemblage: Scrapy Cluster](https://scrapy-cluster.readthedocs.io/en/latest)
* [Video tutorial on APIs, RSS, and Scraping from PyCon](https://youtu.be/A42voDYkFZw)

### Other useful libraries

* [Parse HTML, by author of Requests library: requests-HTML](http://html.python-requests.org/)
* [Extract different parts of URL: furl](https://github.com/gruns/furl)
* [Parse CSS files: cssutils](http://cthedot.de/cssutils/)
* [Parse common formats in newspaper data: newspaper](https://newspaper.readthedocs.io/en/latest/)
* [Scrape from the past: Internet Archive Python Library](https://archive.org/services/docs/api/internetarchive/index.html)
* [Browser automation for handling interactive, JavaScript-heavy pages: Selenium](https://www.selenium.dev/)

## O'Reilly books on scraping
These are available free for some universities, like Georgetown or UC Berkeley ([log in here then search for books](https://www.safaribooksonline.com/library/view/temporary-access/))

* [Popular intro book with Ch. 12 on web-scraping: _Automate the Boring Stuff with Python_](https://nostarch.com/automatestuff2)
* [Complete scraping intro: _Web-scraping with Python_](http://shop.oreilly.com/product/0636920078067.do)
* [Detailed look at mechanics and approaches in Scrapy](https://learning.oreilly.com/library/view/learning-scrapy/9781784399788/)

## Contributing

If you spot a problem with these materials, please make an issue describing the problem or contact Jaren at jhaber@berkeley.edu. If you want to suggest additional resources or materials, please branch and make a pull request!


## Acknowledgments

* [D-Lab at the University of California, Berkeley](https://dlab.berkeley.edu/)
* [Summer Institute in Computational Social Science](https://sicss.io/)
* [Massive Data Institute at Georgetown University](https://mdi.georgetown.edu/)
* [Geoff Bacon](https://geoffbacon.github.io/), especially his [Introduction to web scraping workshop](https://github.com/TextXD/introduction-to-web-scraping)
* [Rochelle Terman](http://rochelleterman.com/), especially her [Web Scraping and Data Management in R summer course](https://github.com/rochelleterman/ESS-webscraping)
