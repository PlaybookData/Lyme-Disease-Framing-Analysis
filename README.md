# Lyme-Disease-Framing-Analysis
 Acquisition, processing and analysis of 1000s of journal articles about Lyme disease and tick-borne diseases

The main notebooks for this project are Data Acquisition Process and FullDataSet-Analysis although other temporary working files are also currently still in this repo.

Publish or Perish was used to search for articles about Lyme disease or tick-borne diseases via PubMed, Google Scholar, Scopus and CrossRef.

Abstracts are scraped from the respective websites if not returned as part of the Publish or Perish search.

Over 40,000 search results are filtered for uniqueness and eligibility. Around 4615 existing abstracts are supplemented with over 1000 scraped abstracts for a total of 5897 abstracts which are then further refined based on language and relevancy down to a final data set of 5699 abstracts.

Notebooks:

Data_Acquisition Process.ipynb = data acquistion, web scraping etc.

FullDataSet-Analysis.ipynb = tokenisation, normalisation, EDA, topic modelling.
