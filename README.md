![engineering_intelligence](https://github.com/mindyng/analytics-readings/blob/e6438578d3c915165141ffccc7eea0193b500803/engineering_intelligence.png)
Credit: [Lindsay Bongo](https://dribbble.com/Bongo)

# Welcome!

Given that Analytics Engineer is a fairly new role on the data team, I wanted to compile a list of resources to be a one-stop knowledge shop. 

First, let's be on the same page. What is an Analytics Engineer?
[Analytics Engineer Definition](https://www.locallyoptimistic.com/post/analytics-engineer/). 

[Video Definition with In-depth Explanation](https://www.youtube.com/watch?v=5s-KYV9zsWM&t=483s) (for the audio learners 😉 )

Following data as a product model for data teams, Analytics Engineers (AE) start with the business question. To be business strategic partners and not siloed engineers, Analytics Engineers have sharp business intelligence. Business needs are translated to data needs. AE's supply the data in order to answer business stakeholders' questions. 

Looker Community is where business intelligence folks post/comment, etc. If this is where they hang, then this is where they will talk about business [metrics of interest](https://community.looker.com/lookml-5/analytics-block-customer-retention-and-lifetime-value-survival-style-5780) i.e. what they want to measure in order to move the business forward. How data is queried and computed can be found in the [Looker Community](https://community.looker.com/). 

On top of the usual business stakeholder, you also have your friendly Data Scientist who needs that dataset to create their predictive models :) Kaggle is where the Data Scientist people hang out. And here are [Kaggle's business datasets](https://www.kaggle.com/tags/business) to get an idea of what sort of columns they would like to see in the data models they would receive from AE's.

Now that you know the general AE's role/responsibilities, here are the skills needed in order to hit OKR's and business goals along with some supplemental readings. Let's go!

## Table of Contents:

MINDSET

- [Thinking with data](#thinking-with-data)
- [Analytics Skills](#analytics-skills)
- [Business Acumen](#business-acumen)

DATA WAREHOUSE

- [Data Warehousing](#data-warehousing)
- [Data Pipelines](#data-pipelines)
- [Testing data](#testing-data)

SQL 

- [SQL](#sql)

PYTHON

- [Gitlab repo to learn from](#github-gitlab-repo-to-learn-from)
- [Python](#python)

DASHBOARDS / DATA VISUALIZATIONS

- [Data Visualisation](#data-visualisation)

### SUPPLEMENTAL

EMBEDDED DATA TEAMS IN CERTAIN FUNCTION:

- MARKETING
 1. [Marketing and data](#marketing-and-data)

BIG IDEAS:

- [Starting analytics in a company](#starting-analytics-in-a-company)
- [Organisation](#organisation)
- [Success Stories](#success-stories)
- [Infrastructure](#infrastructure)
- [Against ELT](#against-elt)

OTHER READINGS:

- [Other readings lists](#other-readings-lists)

AE TRIBE:

- [Community](#Community)
- [Top bloggers/blog](#top-bloggersblog)

## Readings

### Thinking with data
These books/articles helped me to think better when analysing data. 

  * [Common Data Mistakes to Avoid](https://www.geckoboard.com/learn/data-literacy/statistical-fallacies/). Excellent summary of the most common fallacies when analyzing data. Very clear and well-explained. 
  * [Thinking fast and slow](https://www.amazon.com/dp/0374533555/ref=cm_sw_em_r_mt_dp_U_wOryDb6WC3CVE). Learning about bias can be super useful. For instance, I didn't have the reflex to think of a base rate anytime I see a figure. 
  * [Fooled by randomness](https://www.amazon.com/Fooled-Randomness-Hidden-Markets-Incerto/dp/0812975219/ref=sr_1_1?crid=2QEXPWM35W0BR&keywords=fooled+by+randomness&qid=1566644880&s=books&sprefix=foole%2Cstripbooks-intl-ship%2C207&sr=1-1).
:book: Nassim Taleb taught so much both professionally and personnaly. In Fooled By Randomness, you will learn about major pitfalls when dealing with data in **real life**. 
  * [Why you should care about the Nate Silver vs. Nassim Taleb Twitter war](https://towardsdatascience.com/why-you-should-care-about-the-nate-silver-vs-nassim-taleb-twitter-war-a581dce1f5fc). Great chess players learn from high elo games. Great data people learn from debate between data experts. 
  * [Five books every data scientist should read that are not about data science](https://towardsdatascience.com/five-books-every-data-scientist-should-read-that-are-not-about-data-science-f7335fb1f84f). I have not read them all yet. But these suggestions seems judicious. 

### Analytics Skills
  * [One analyst's guide for going from good to great](https://blog.getdbt.com/one-analysts-guide-for-going-from-good-to-great/)
  * [Suceeding as the first data person in a small company/startup](https://towardsdatascience.com/succeeding-as-a-data-scientist-in-small-companies-startups-92f59e22bd8c). A must read for anyone working in data even in a big company. 
  * [Prioritizing data science work](https://towardsdatascience.com/prioritizing-data-science-work-936b3765fd45). Too many engineers like building ivory towers. Make sure you don't fall in the trap.

### Business Acumen
  * [Competitive Advantage by Michael Porter](http://www.mim.ac.mw/books/Michael%20E.%20Porter%20-%20Competitive%20Strategy.pdf) Seminal book for defining how businesses compete
  * [The Fifth Advantage by Peter Senge](http://kmcenter.rid.go.th/kmc08/km_59/manual_59/Book6/The-Fifth-Discipline.pdf) This book lays the groundwork of systems thinking upon which many modern management and leadership books have been written. 
  * [Harvard Business Review](https://hbr.org/)
  * [Strategy&](https://www.strategyand.pwc.com/) strategy consulting business unit of PricewaterhouseCoopers (PwC), one of the Big Four professional service firms

### Data Warehousing

  * [The beginner guide to data engineering series](https://medium.com/@rchang/a-beginners-guide-to-data-engineering-part-i-4227c5c457d7). Start here if you don't know what is a star schema, Airflow and some basic practices when writing data pipelines.    
  * [Best practices for data modeling](https://www.stitchdata.com/blog/best-practices-for-data-modeling/). A lot of practical tips on naming, grain, permissions and materialization. 
  * [The Data Warehouse Toolkit](https://www.amazon.com/Data-Warehouse-Toolkit-Definitive-Dimensional/dp/1118530802/ref=sr_1_1?crid=FV5A2S72XIZO&keywords=data+warehouse+toolkit&qid=1566644628&s=gateway&sprefix=data+ware%2Caps%2C213&sr=8-1) by Ralph Kimball. :book: A classic in Business Intelligence. Some chapters can be gold on modeling your data warehouse.   
  * [Functional Data Engineering — a modern paradigm for batch data processing](https://medium.com/@maximebeauchemin/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a). You will learn the spirit behind good data pipelines and a well-designed data warehouse.  
  * [The rise of the Data Engineer](https://medium.com/free-code-camp/the-rise-of-the-data-engineer-91be18f1e603). Explains recent evolutions of the job and data practices.   
  * [Five principles that will keep your data warehouse organized](https://blog.getdbt.com/five-principles-that-will-keep-your-data-warehouse-organized/)
  * [Using Postgres as a data warehouse](https://www.narrator.ai/blog/using-postgresql-as-a-data-warehouse/) I wish I read this post earlier. So much wisdom on Postgres.
  * [For Data Warehouse Performance, One Big Table or Star Schema?](https://fivetran.com/blog/obt-star-schema). Discussion on an alternative to star schema. 

### Data Pipelines

  * [Functional Data Engineering — a modern paradigm for batch data processing](https://medium.com/@maximebeauchemin/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a). You will learn the spirit behind good data pipelines and a well-designed data warehouse.
  * [Maintenable ETL: Tips for Making Your Pipelines Easier to Support and Extend](https://multithreaded.stitchfix.com/blog/2019/05/21/maintainable-etls/). Best practices to write good ETL. 
  * [The Data Warehouse ETL Toolkit](https://www.amazon.com/gp/product/0764567578?ie=UTF8&tag=decworks-20&lin%20kCode=xm2&camp=1789&creativeASIN=0764567578) :book: Once again, very dense book but you can find good ideas. 

### Testing data
  * [Automated Testing In The Modern Data Warehouse](https://medium.com/@josh.temple/automated-testing-in-the-modern-data-warehouse-d5a251a866af). Practical advice to test data. Useful for everyone building data pipelines. Rare to found such a post dealing with non-sexy thing in data.

### SQL
SQL has a lot of tips and tricks that take time to know. 
  * [Mode Analytics SQL Guide](https://mode.com/sql-tutorial/introduction-to-sql/). Very complete, even intermediate users can learn from this series of tutorials.
  * [Learning SQL 201: Optimizing Queries, Regardless of Platform](https://towardsdatascience.com/learning-sql-201-optimizing-queries-regardless-of-platform-918a3af9c8b1) By Randy Au. I finally found a complete post on advanced SQL.
  * [SQL Optimization from Chartio](https://cdn2.hubspot.net/hubfs/392937/SQL%20Optimization.pdf?__hstc=158613477.c6a4c543a84cf2375e40c7c5c52f788c.1620019958078.1620069124111.1620334698312.4&__hssc=158613477.1.1620334698312&__hsfp=1027006628&hsCtaTracking=9311e47c-0dbe-451b-9129-3cbce358df08%7C3d2c58de-3379-41ef-9c8d-f0492f3bf1bd) 
  #### Practice
  * [LeetCode Database Problems](https://www.youtube.com/playlist?list=PLdrw9_aIADIPAMJW8I_S-S747oyiRtzpS) All levels clearly explained and walked through
  * [Business Practice Problems]() Caveat here is that you need membership to get solutions, but there might be some good solutions in Comments. I advise using db-fiddle to create tables and to devlop solutions
  * [Top Interview Q's from well-known tech co's](https://platform.stratascratch.com/coding?questionType=2&company=&ids=&is_correct_solution=&is_bookmarked=&is_freemium=&in_depth_solution=&difficulty=&python=&filters=&page=1&page_size=25) Not as challenging as Business Practice Problems (good warm-up)
  * [Real-World Practice Problems](https://sqlpad.io/)

### Python 
Python is a very broad subject. Maybe you can follow this list for more [Python focused readings](https://github.com/charlax/python-education).
  * [Python for Data Analysis](https://www.amazon.com/Python-Data-Analysis-Wrangling-IPython/dp/1491957662). :book: Very comprehensive book about using python for data stuff. 
  * [Pandas Cheatsheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf) I use it everyday!
  * [Modern pandas](https://tomaugspurger.github.io/modern-1-intro.html). A series of blog posts on intermediate/advanced pandas written by one of the maintainers. 

### Github-Gitlab repo to learn from
I found that reading code helps to know the best practices whether it is Python or SQL.

In Python reading some taps from [Singer](https://github.com/singer-io) can teach you a lot. 

In dbt/SQL I like to browse [a repo open-sourced by Gitlab](https://gitlab.com/gitlab-data/analytics/-/tree/master/transform/snowflake-dbt)

### Data Visualisation 
   * [Fundamentals of Data Visualisation](https://serialmentor.com/dataviz/). Complete guide to visualisation. Free version online.

### Marketing and data
  * [Data Driven Marketing](https://www.amazon.com/Data-Driven-Marketing-Metrics-Everyone-Should/dp/0470504544/ref=sr_1_1?crid=38ZUOKHZZEY6D&keywords=data+driven+marketing&qid=1566644698&s=gateway&sprefix=data+driven%2Caps%2C209&sr=8-1). :book: Reading some chapters can help you think like a marketer with data driven approach. It's a gem. Didn't find this kind of insights elsewhere.
  * [Introduction to Algorithmic Marketing](https://algorithmic-marketing.online/). :book: I found good ideas to make more data driven initiatives for marketing. Very dense though, you can pass the equations.

### Starting analytics in a company
  * [Building a data practice from scratch](https://www.locallyoptimistic.com/post/building-a-data-practice/). Very useful for your first weeks as a data person. 
  * [The Startup Founder's Guide to Analytics](https://thinkgrowth.org/the-startup-founders-guide-to-analytics-1d2176f20ac1). An excellent introduction to the stack necessary for analytics and its evolution following the growth of the start-up. 

### Organisation
  * [Engineer shouldn't write ETL](https://multithreaded.stitchfix.com/blog/2016/03/16/engineers-shouldnt-write-etl/). It's more data science focused but it's a classic.
  * [Does my startup data team need a data engineer?](https://blog.getdbt.com/does-my-startup-data-team-need-a-data-engineer-/)

### Success Stories
  * [Scaling analytics at Wish](https://medium.com/wish-engineering/scaling-analytics-at-wish-619eacb97d16)
  * [Building Analytics at 500px](https://medium.com/@samson_hu/building-analytics-at-500px-92e9a7005c83)

### Infrastructure

  * [The Startup Founder's Guide to Analytics](https://thinkgrowth.org/the-startup-founders-guide-to-analytics-1d2176f20ac1). An excellent introduction to the stack necessary for analytics and its evolution following the growth of the start-up.  
  * [The missing layer of Analytics Stack](https://blog.getdbt.com/the-missing-layers-of-the-analytics-stack). 
  * [Choosing a Data Warehouse](https://discourse.getdbt.com/t/choosing-a-data-warehouse/62/4). A lot of excellent answers on what to choose for your data warehouse. 
  * [Data science for start-ups](https://bgweber.github.io/intro.html). You can find some useful information in this free book.
  * [Designing Data-Intensive Applications](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321) :book: Fascinating read to learn more about databases, protocols etc...
  * [The Modern Data Stack: Past, Present, and Future](http://blog.getdbt.com/future-of-the-modern-data-stack/) A must-read on the last innovations in the data stack.

  **Comparison of tools by Stephen Levin**
  * [Looker vs Tableau vs Mode. Data Visualisation tools compared](https://www.stephenlevin.co/advanced-analytics-part-3-data-visualization/). . 
  * [Segment vs Fivetran vs Stitch: Which Data Ingest Should You Use?](https://www.stephenlevin.co/segment-vs-fivetran-vs-stitch-which-data-ingest-should-you-use/)

### Against ELT
The concept of analytics engineering is tightly coupled with the ELT view of data warehousing. It is interesting to learn from the people that would prefer the ETL. 
[Reddit comments on Snowflake super-expensive cost](https://www.reddit.com/r/dataengineering/comments/is39id/snowflake_cost_analysis/)

### Other reading lists

   The GitLab data team also made an [excellent list](https://about.gitlab.com/handbook/business-ops/data-team/#data-learning-and-resources). (close to mine)

[Analytics Dispatch](https://mode.com/analytics-dispatch) by Mode Analytics. Very comprehensive.

I really love [Reading in Applied Data Science](https://github.com/hadley/stats337#readings) for a more data science focused view.  

Knowing more about programming is an huge asset. For instance [Professional Programming list](https://github.com/charlax/professional-programming) is quite complete.


# COMMUNITY

## Top bloggers/blog
  * [Randy Au](https://towardsdatascience.com/@Randy_Au). You can read almost all his posts there are all very relevant for analytics engineers.
  * [Locally Optimistic](https://www.locallyoptimistic.com/). A blog dedicated to data in organizations. 
  * [Tristan Handy](https://medium.com/@jthandy). I also love his newsletter: [Data Science Roundup](http://roundup.fishtownanalytics.com/).
  * [Dbt blog](https://blog.getdbt.com/). 90% of the articles are almost must-read.
  * [Ken Farmer](https://www.reddit.com/user/kenfar/?sort=top&t=year) It is healthy to read from those who still prefer the ETL stack.
  * [Holistics.io](https://www.holistics.io/blog/) About the contemporary practice of business intelligence.

## Conferences
 * [Census - 2021 Operational Analytics Conference](https://www.getcensus.com/operational-analytics-conference-2021)
 * [Coalesce - The Analytics Engineering Conference](https://coalesce.getdbt.com/)

## Social Media
  * [Twitter](https://twitter.com)
  * [Locally Optimistic](https://www.locallyoptimistic.com/) Highly recommend joining their Slack!
  * [Reddit's Data Engineering](https://www.reddit.com/r/dataengineering/) ETL, Business Intelligence, Data Science channels are also good.
  * Slack channels
    - [wimlds.slack.com](https://wimlds.slack.com/)
    - [futuredataconf.slack.com](https://futuredataconf.slack.com)
    - [thedataschool.slack.com](https://thedataschool.slack.com)
    - [data-engineering-sd.slack.com](https://data-engineering-sd.slack.com)
    - [wb-forum.slack.com](https://wb-forum.slack.com)
    - [earlywtm.slack.com](https://earlywtm.slack.com)
    - [apache-airflow.slack.com](https://apache-airflow.slack.com)
    - [Union All - Unofficial Looker Slack](https://community.looker.com/getting-started-1006/unofficial-slack-group-union-all-20594)
   * [MeetUp](https://www.meetup.com/)
   * [EventBrite](https://www.eventbrite.com/)
  
 ## Contribute ❤️
I really appreciate any contribution. If you do, please make sure to describe the theme and why you found the resource useful. 
