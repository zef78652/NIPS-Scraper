# NIPS Scraper

A quick script to scrap and save all the published papers in [Neural Information Processing Systems](https://nips.cc/) (abbreviated as **NeurIPS** and formerly **NIPS**) from 1987 to 2019.

## Content
The script scrap and save the data in two files.
#### 1. papers.csv

![](https://i.imgur.com/G8atzkU.png)

#### 2. paper_authors.csv

![](https://i.imgur.com/IbIqlSR.png)


## Usage
**```nips_scraper.py [-h] [-start START_YEAR] [-end END_YEAR]```**

```
Script to scrap NeurIPS Papers
optional arguments:
  -h, --help         show this help message and exit
  -start START_YEAR  The start year to scrap the papers
  -end END_YEAR      The end year to scrap the papers
  ```
### Example
  - Simply run script to scrap and save all the papers.
  
  ```python3 nips_scraper.py```
  - You can specify the range of years in which you want to scrap the papers. Example:
  
  ```python3 nips_scraper.py -start=2002 -end=2010```
  - Get the help
  
  ```python3 nips_scraper.py --help```


## Credit
Data collection would not have been possible without [https://nips.cc](https://nips.cc). A huge thanks to **NeurIPS** for making the data public.
