Parental Leave in the US

Website: https://mardejour.github.io/parental-leave/

## Intro
Currently, the United States is the only developed nation that has no federal policy for paid maternity leave. As a result, many new mothers in the US must rely heavily on their employers to grant them paid maternity leave and benefits. I was curious to know which US employers granted their employees paid leave, and to what extent compared to other countries that have federal policies mandating paid leave.

## How it works
Data is from [Fairygodboss's Maternity Resource Center](https://fairygodboss.com/maternity-leave-resource-center). I wrote an HTML web scraper in Python that loads a page from Fairygodboss, gets the data from the table, and stores it in a JSON object. The web scraper is available in the `/assets` folder and can be run using Jupyter Notebook.

The data is visualized using [d3.js](https://d3js.org/).

## Run it
To run, `git clone` the repo, `cd` into the project, and run `http-server -c-1 -p 8000` (or any local server of your choice) to view the project at `localhost:8000`.

## Sources
- [Fairygodboss](https://fairygodboss.com/maternity-leave-resource-center)
- [Among 41 nations, U.S. is the outlier when it comes to paid parental leave](http://www.pewresearch.org/fact-tank/2016/09/26/u-s-lacks-mandated-paid-parental-leave/)
- [Glassdoor: 15 Companies With The Best Parental Leave Policies](https://www.glassdoor.com/blog/best-parental-leave-policies/)
- [Paid Parental Leave in the United States: What the data tell us about access, usage, and economic and health benefits](https://iwpr.org/wp-content/uploads/wpallimport/files/iwpr-export/publications/B334-Paid%20Parental%20Leave%20in%20the%20United%20States.pdf)
- [Working Mothers 100 Best Companies 2020](https://www.workingmother.com/working-mother-100-best-companies-winners-2020)
- [These 10 countries have the best parental leave policies in the world](https://www.businessinsider.com/countries-with-best-parental-leave-2016-8)

## Resources
Making a bubble chart
- https://observablehq.com/@d3/bubble-chart
- https://github.com/d3/d3-force

Annotating the bubble chart
- http://d3-annotation.susielu.com/

Creating the scrolly story
- http://vallandingham.me/scroller.html

Building a web scraper with Python and Jupyter Notebook
- https://docs.python-guide.org/scenarios/scrape/
