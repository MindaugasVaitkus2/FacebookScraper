# FacebookScraper
This script scrapes posts and comments from facebook pages,groups and store its with their details in mysql databases .

# Requirements
This script test under this Requirements
  * Ubuntu OS.
  * Python [ installed already with ubuntu ] .
  * MySQL Server .
      install it by this command
            `$ apt-get install mysql-server`

# Setup Script
  * Download Script .
			`$ git clone https://github.com/ihalloum/FacebookScraper.git`
  * Create Database fb_data
			`$ mysql -u root -p`
			`mysql> CREATE DATABASE fb_data;`
  * Import Database structure .[ Use /database/fb_dta.sql ].
			`$mysql -u root -p fb_data < ./Database/fb_data.sql`
  * Edit Script vars to fit your data.
  * Run Script :)
			`$python -W ignore script.py ScrapePage=Y ScrapeGroup=Y ScrapeComment=Y ScrapeReply=Y ScrapeLike=Y`
			
