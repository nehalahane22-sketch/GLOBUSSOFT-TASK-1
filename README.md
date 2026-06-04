Hi,

I've completed Task 1 and here's a quick summary of what I built.

I wrote a Python script that scrapes laptop listings from amazon.in. To avoid getting blocked, I used rotating browser headers and created a session that first visits the Amazon homepage to collect cookies, just like a real browser would. The script goes through multiple pages and for each product it picks up the title, price, rating, product image URL, product link, and whether the listing is a sponsored ad or an organic result.

Once the scraping is done, everything gets saved into a CSV file automatically. The filename includes a timestamp so every run creates a unique file, for example: amazon_laptops_20260604_081111.csv

In my test run I was able to collect 48 laptop listings across 3 pages without any issues.

The code is saved as a .ipynb notebook file as mentioned in the requirements.

Let me know if you have any questions!

Regards,
Neha Lahane
9146394305
