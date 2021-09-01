## Real Estate ETL Pipeline

**Project description:** 
For a proptech startup, I acquired >4M data points a month, and cleaned them

I set up multiple scrapers on digitalocean droplets, and automated them with cronjobs to scrape bimonthly. They reported to telegram with telemon, and deposited the data into an S3 bucket. This triggered Cloudwatch (for reporting), and lambda functions which would clean the data and deposit into an AWS RDS. It would then be fetched client side via CQL, and a Geoserver set up on an EC2 instance.

### 1. Scrapers

[Apartments.com Scraper](https://github.com/andrewshrout/apartment-scraper)
<br>
[Craigslist Scraper](https://github.com/andrewshrout/craig-scraper)
<br>
[Airbnb Scraper](https://github.com/andrewshrout/AirBnB-Scraper)
<br>
[Redfin Scraper](https://github.com/andrewshrout/redfinspidertest/tree/main)

### 2. Cleaning Scripts
[Readme](https://github.com/andrewshrout/cleaners)
<br>
[Craigslist Cleaner](https://github.com/andrewshrout/cleaners/blob/main/craig_cleaner.py)
<br>
[Apartments Cleaner](https://github.com/andrewshrout/cleaners/blob/main/apartment_cleaner.py)
<br>
[AirBnB Cleaner](https://github.com/andrewshrout/cleaners/blob/main/air_cleaner.py)

### 3. Jupiter Notebook Data Exploration / Modeling

<img src="images/la-rent-resize.png?raw=true"/>

[Analysis + Readme](https://github.com/andrewshrout/sample-explorations)
<br>
[Craigslist LA Data Analysis](https://github.com/andrewshrout/sample-explorations/blob/main/basic_la_analysis.ipynb)
<br>
[Crime Data Exploration + Modeling](https://github.com/andrewshrout/sample-explorations/blob/main/Crime%20Exploration.ipynb)

### 4. SQL

[SQL Examples](https://github.com/andrewshrout/SQL-Portoflio-Examples)

### 4. Map App / Visualizations

See [Mapstack](https://github.com/andrewshrout/mapstack-ai) page.
