# reference-management
Voila-based Dashboard to collect and organize Metadata of Academic Papers.

A simple snippet to create a Dashboard which uses Google Scholar and CrossRef to scrape Metadata of Academic Papers.
Input can be given as PDF or title, from which metadata such as DOI, author, link etc will be imported and stored in a Pandas Dataframe alongwith a CSV file stored remotely.


Requirements: <br/>
[Autobib](https://github.com/jdumas/autobib) - This Repository has already been cloned and stored in the Main folder  <br/>
'pip install voila' <br/>
pip install ipywidgets <br/>
jupyter nbextension enable --py widgetsnbextension <br/>



Instructions: <br/>
Clone and Extract entire Repository. <br/>
voila ref.ipynb <br/>

Attributes of Metadata Available: <br/>
Title, Author, Citation Count, DOI, Publisher, Venue, URL, Year
