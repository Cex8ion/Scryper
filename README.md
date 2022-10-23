# Scryper
Proxy Scraper

Used with a text file containing one URL on each line

Scrapes the site with beautiful soup and parses the data
Uses regex to find IPs in the page content and print them in a new text file
Results can be filtered by port number

Scryper.py URL.txt -o results.txt -p 8080
--Runs the script and saves all proxies with port 8080 to results.txt

Scryper.py URL.txt
--Runs the script and saves all proxies to the default outfile proxies.txt

The only required argument is the file that contains the URLs the other arugments are optional
