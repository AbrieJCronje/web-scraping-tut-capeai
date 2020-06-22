# Basic scraping

We explore how scraping works, covering making some soup from a website URL, finding a unique identifier for the content you're after using the inspector, and finally extracting it.

# Selenium

Some websites have some javascript functionality that blocks you from immediately getting the information you want, for example, by having to click a button to show a table.
Here we use a normal app testing tool, selenium, to act as a webdriver, giving us the functionality necessary to obtain our information.
Think of it as a browser bot instance, it opens a browser and you use code to tell it what to click etc.

# Sample project

We are curious about the nutritional information of the products we buy at a regular basis.
First we scrape a list of the products we are interested in, then we loop through them with geckodriver, click the required javascript with selenium, and scrape the information with beautiful soup and some logic.
Our end goal is simply to have a database with the selected products and their nutritional information.

