# Job Scraper Project
A personal project where I learn how to use Beautiful Soup and the python library Requests to scrape job information off job websites in order to better understand the professional environment

### Project Goal
To analyze all remote data science positions posted on indeed.com and determine the most frequently mentioned data science skill/tool/tech used to decide which I should begin learning next.

### Job Website Used
indeed.com

### Process
I researched the most popular data science tools that came up on the internet and created a simple list containing: python, R, SQL, D3.js, matlab, excel, SAS, BigML, Apache Spark, Jupyter, Tableau, Scikit, Tensorflow, Weka, Matplotlib, ggplot, nltk, Azure, power BI. This is by no means a comprehensive list, but I didn't want to spend too much time on it since my aim was to learn how to use BeatifulSoup and analyze indeed.com.

In order to get each job description from the job list, I had to get the html code, look through it, and then specify to beautiful soup what parts of the html I wanted. In this case, I wanted the job title, company name, and job description. In order to get the job description, I had to pull the job id from the list of jobs, and format a new URL to access the full page that contained the description.

Once I got the description, I noted down the tools that showed up in the description from my list, and stored it in a larger list for later.

Unfortunately, while my code does work as intended, I ran into captcha issues. It is likely because indeed or google noticed the unusually large number of web page accesses. Because of this, I only gathered 70+ rows of data, but I plan to continue to add to this.

### Which tools showed up the most?
Coming soon!

