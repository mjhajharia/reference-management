# reference-management
Voila-based Dashboard to collect and organize Metadata of Academic Papers.

A simple snippet to create a Dashboard which uses Google Scholar and CrossRef to scrape Metadata of Academic Papers.
Input can be given as PDF or title, from which metadata such as DOI, author, link etc will be imported and stored in a Pandas Dataframe alongwith a CSV file stored remotely.


Requirements:
Autobib - https://github.com/jdumas/autobib
pip install crossrefapi
pip install voila
pip install ipywidgets
jupyter nbextension enable --py widgetsnbextension



Instructions:

Download Notebook and CSV file to the same directory.
Open the Notebook in Voila.

Attributes of Metadata Available:
Title
Author
Citation Count
DOI
PUblisher
Venue
URL
Year
