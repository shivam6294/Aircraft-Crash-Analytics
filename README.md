# Aircraft-Crash-Analytics
Flying is considered as the safest way to travel as of today. But has that always been the case? Was flying as safe in the 20th century? Most of us have boarded an airplane manufactured by Boeing and Airbus, which are two of the biggest and most popular commercial flight manufacturers in the world. How many planes that have been manufactured by them have crashed in the past? What were some of the most common reasons for the crashes? It is questions like these that fueled our curiosity and interest towards this project- Aircraft crash analytics- a visual exploration of aircraft crashes since 1908.

The aviation industry is a mature industry, and is more than a hundred years old. So, there exists a lot of data in this field, especially aircraft crash data. This makes it very interesting, as we were able to grab data that helped us analyse the state of the aircraft safety over a period of an entire century!

Through this project, we have explained in detail, the methodology and tools used for implementing the data pipeline, right from getting the data in HTML format, analyzing it, and to converting it into attractive visualizations can be viewed thorough our website www.sykdesigns.com/GE2324

##  Structure: 
* The project is divided logically into three parts:
  * <u> Part 1- Data Collection - Crawling Flight Crash Data.ipynb </u>: Scripts to crawl the website www.planecrash.info/database.htm. This can be used as a skeleton to crawl urls that have a pattern.
  * <u> Part 2- Data Wrangling- Adding Latitudes and Longitudes using Google Maps Geocoding API.ipynb </u>: Adding Geolocation data to the crawled dataset from Part 1, using [Google Maps Geocoding API] (https://developers.google.com/maps/documentation/geocoding/intro)
  * <u> Part 3- Aircrash Analytics- Data Mining.ipynb </u>: The aim of this IPython Notebook is to perform some exploratory data analysis on the wrangled dataset that we have obtained. We're gonna use Pandas for the most of it, and some SciPy and Scikit Learn towards the end. 

ENJOY!!

## REQUIREMENTS:
* Ipython Notebook Server (WinPython for Windows/Anaconda for Linux recommended)
* MongoDB server up and running on the same machine (by default. Can link it to the code if it's running elsewhere)
* All the python dependencies must be installed. All the library classes used in this project are available on [PyPI](https://pypi.python.org/pypi) (Python Package Index)
* Google Maps Geocoding API key is required for Part 2
