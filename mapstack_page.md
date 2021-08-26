## Real Estate ETL Pipeline

**Project description:** 
For a proptech startup, I acquired >4M data points a month, and cleaned them

I set up multiple scrapers on digitalocean droplets, and automated them with cronjobs to scrape bimonthly. They reported to telegram with telemon, and deposited the data into an S3 bucket. This triggered Cloudwatch (for reporting), and lambda functions which would clean the data and deposit into an AWS RDS. It would then be fetched client side via CQL, and a Geoserver set up on an EC2 instance.

### 1. Scrapers

[Apartments.com Scraper](https://github.com/andrewshrout/apartment-scraper)
<br>
[Craigslist Scraper](https://github.com/andrewshrout/craig-scraper)
<br>
[Redfin Scraper]
<br>
[Airbnb Scraper]

### 2. Cleaning Scripts

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

### 3. Jupiter Notebook Data Exploration

<img src="images/dummy_thumbnail.jpg?raw=true"/>

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

### 4. SQL / CQL

[SQL Examples](https://github.com/andrewshrout/SQL-Portoflio-Examples)

CQL

### 4. Map App / Visualizations

See [Mapstack](url) page.

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
