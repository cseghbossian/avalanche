**Datasets:**

1. JUST Capital Rankings

2. Scope 1 and 2 Emissions

3. EPA Violations

4. Forest Company Assessments

**Scrapable Websites:**

1. Yahoo Finance Stock History or similar website that has market cap!!

2. EPA Violation Tracker 

**Visualization 1: Industry Best/Worst**

- A box/whisker chart or visualization similar to NYT 

- Linear regression plotting market cap (scraped) vs. environmental score 

  - Is there a relation between worse scores and market cap?

- Which companies are best/worst in each industry?

- Which environmental scores vary the most in each industry?

- By what metric are we determining best/worst?

**Work Required:**

- Define a metric for best/worst (combine datasets if possible; else, use one)

  - Scale scope emissions by company value or scrap scope emissions since JUST uses them as part of their scores

  - Join EPA violations with JUST scores using ticker symbols. Find total penalty amount from EPA violations 

  - Possibly incorporate Forest Company scores somehow. This is difficult because no ticker symbols. Find ticker symbols? 

- Scrape 2018 average market caps for each company (we use 2018 since JUST scores are from that year)

- Research plotly tools

- Create visualization(s) that answer above questions

**Visualization 2: USA vs. the Rest of the World**

- A map with different sized points for different companies (size determines how bad)

- A bar graph for each continent x environmental factor

- In each environmental score, how do US companies rank (on average) compared to all other countries?

  - Possibly separate by continent

  - Possibly separate by industry

- Of all EPA violations, what number of them are non-US companies?  What percentage of the total penalties are from non-US companies?

**Work Required:**

- Fill in continent data for all relevant data sets

- Fill in coordinate data for all relevant data sets

- Research how to plot map

- Create many different visualizations that answer above questions

**Visualization 3: EPA Violations and Their Effects on the Stock Market**

- Line graphs of top EPA violations’ before and after market caps

- How does a company’s market cap change after a huge EPA violation?

- Are EPA penalty amounts significant enough to negatively impact big companies?

- Compare larger companies with smaller companies to see how badly EPA penalties affect them

**Work Required**

- Find top n(?) most expensive penalty amounts 

- Find market cap for the companies with top n penalty amounts

- Scrape change in market cap before and after penalty dates

