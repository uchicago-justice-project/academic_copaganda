# Academic Copaganda

## Decription

This github repo is for data and code related to the research paper "Academic Copaganda."

## Project Step by Step

Below are the steps we took to gather the papers in our sample as well as the media mentions and contracts associated with that data.

### Gather Grants from major funders

We utilized web scraping scripts to gather publicly available grant data from four major funders: [Arnold Ventures](https://www.arnoldventures.org/summaries-of-research-grants) (note this link is different from the one we originally used for scraping, that link is now dead), the [National Institute of Justice](https://nij.ojp.gov/funding/awards/list), and the [MacArthur Foundation](https://www.macfound.org/grants/). When categories were available via the grant search we utilized relevant categories, otherwise we used keywords like "police" and "crime" to find relevant grants. We scraped all grants from 2010 to 2021.

All grants found can be seen in the tabs for the individual funders in policing_papers.xlsx.


### Gather Papers Funded by Grants

We utilzied the NIJ website and Web of Science to gather papers funded by the grants we scraped. When available we used the grant number to find funded papers, but when that was not possible we matched papers to grants using the funder, the timing of the grant and paper, and the topic of the grant and paper. 

All papers found can be seen on the tab Papers_raw in policing_papers.xlsx.


### Filter out irrelevant papers and code

From this original collection of papers we dropped any papers that were not relevant typically because they were not actually studies of police. From this we created our final sample of papers. 

We then coded papers by their modeling techniques, findings, and whether or not they were academic copaganda. All papers without a DOI were considered non-peer reviewed.

This list of papers can be seen on the tab Papers_cleaned in policing_papers.xlsx


### Gather media mentions via Altmetric

We utilized the service [Altmetric](https://www.altmetric.com/) to gather media mentions of the papers in our sample. Papers could be found in altmetric's database if they had a DOI. 

The full list of media mentions found can be seen on the tab AltmetricCitations in policing_papers.xlsx.

### FOIA for Contracts between Police Departments and Universities

We then FOIA the Universities and Police Departments involved in each study to find any contracts and data user agreements between the researchers and the departments they studied.

Those can be found here: [https://airtable.com/appo7grLN7rXMf2H9/shrGfVJA2SnaAgBqt/tbljzyLNFsHZZ03ky](https://airtable.com/appo7grLN7rXMf2H9/shrGfVJA2SnaAgBqt/tbljzyLNFsHZZ03ky).



