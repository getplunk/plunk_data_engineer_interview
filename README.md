# Plunk Data Engineer Technical Interview


## Prerequisites to the Coding Interview 

- Have an IDE of your choice set up with either Java or Python 3 - be prepared to share your screen on Zoom while you implement a solution to a prompt given at the start of the interview
- Have a local database instance of your choice running on your computer - ex PostgreSQL, MySQL, SQLite
- At the start of the interview we will provide a git repo with more detailed instructions and data files

## Prompt

Using whatever coding language you prefer, design and implement a solution to the case study below.

## Case Study

We just acquired a new datasource for home assessor data. Assessor data is collected by individual counties across the US which contains various details about homes (various square footages, bedroom count, bathroom count, etc). We received a single initial data drop file from our provider which includes one record for roughly every home in the United States.  Since the initial data drop, we now receive a delta file every Monday. These delta files only include homes which have changed or are new builds.