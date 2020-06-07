# Anonymous Web Scraping with Node.js, Tor, Puppeteer and cheerio

 Web Scraping is the technique of extracting data from websites. The term is used typically for automated data extraction. Today, I am going to show you how to crawl websites anonymously. The reason why you want to hide your identity is due to the fact that many web servers apply rules to websites which ban IPs after a certain amount of continuous requests. We are going to use Puppeteer for accessing web pages, cheerio for HTML parsing, and Tor to run each request from a different IP address.

> While the legal aspects of Web Scraping vary, with many grey zones, remember to always respect the Terms of Service of each web page you scrape. Ben Bernard has wrote a nice article about those legal issues.