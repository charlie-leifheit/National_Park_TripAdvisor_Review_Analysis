DESCRIPTION - Describe the package in a few paragraphs
Four Github repos are required to execute the project from end to end.  This project was completed for the Data and Visual Analytics course at Georgia Institute of Technology.  
Team Members include:  Charlie Leifheit, Tal Mullenbach, Anil Gunda, Hein Dang, Daniel Escobar and Nathan Wu


1. TripAdvisor National Park Reviews Web Scraper
	- This scraper is built entirely in Python using Requests, BeautifulSoup, Pandas, and
	Tabula libraries. The objective is to visit each of the 61 National Parks, locate all reviews for
	each park, obtain the review text, title, user, location, rating, and review date - then store the
	results for each park into a CSV.
2. National Park Feature Engineering
	- The text processing is built using Python with Pandas, Numpy, Matplotlib, Seaborn,
	Spacy. The objective is to take raw data from web scraper and decompose each review by park
	and year into its individual words. The individual words are to be cleaned up and filter using
	Spacy package. The final output is a csv aggregate table of all the words with their associated
	counts and respective parts of speech grouped by park and year.
3. TripAdvisor Review Text Modeling
	- The TripAdvisor Text Modeling code is written in Python 3.7. User also needs to install
	Scikit Learn via pip. The files generate various modeling based on the csv tables obtained from
	feature engineering and the national park service spending data. The final output includes two
	models: a regression spending forecast model and a review word TF-IDF analysis model. There
	is also a supervised learning model created using Azure ML Studio. The flow of the model is
	included in the final report.
4. Tableau Visualization
	- This is a TWBX file showing the historical and forecasted National Park Spending per
	year, as well as the most distinct nouns and verbs per park. The visualization can also be found	
	at:
	-https://public.tableau.com/profile/charlie.leifheit#!/vizhome/Team97_Visualization_CSE6242/NPSVisitorSpending

INSTALLATION - How to install and setup your code
1. TripAdvisor Scraper:
	- The code was created using Google Colaboratory Jupyter Notebook and can be
	downloaded as an IPYNB or Python file from the GitHub listed below. Instructions are include
	for scraping each National Park, however, the files have already been obtained and can be
	loaded it for quick manipulation. The IPYNB file includes instructions for downloading the ZIP
	file of CSVs and loading into Google Colaboratory. Users may need to install the following
	non-standard python libraries in Google Colaboratory or local machine: Tabula, Pandas,
	BeautifulSoup.
	- https://github.com/charlie-leifheit/TripAdvisor-Web-Scraper
2. National Park Feature Engineering
	- The code was created using Google Colaboratory Jupyter Notebook and can be
	downloaded as an IPYNB or Python file from the GitHub listed below. Instructions are included
	within notebook to run and obtain full output as csv files. The raw data for processing is the data
	output from the Scraper. The loading process of the data is formatted to use google drive by
	importing from google.colab import drive. All other non standard packages might need
	to be installed if not using google colab notebooks.
	- https://github.com/charlie-leifheit/Data-Transformation
3. TripAdvisor Review Text Modeling
	- Make sure you have Python 3.7 installed.
	https://www.python.org/downloads/release/python-373/
	- Install pip https://pip.pypa.io/en/stable/installing/
	- Install Scikit Learn using pip https://scikit-learn.org/stable/install.html
	- To use Azure ML Studio, follow instructions to set up a workspace.
	https://docs.microsoft.com/en-us/azure/machine-learning/studio/create-workspace
	
	- https://github.com/charlie-leifheit/TripAdvisor-Review-Text-Modeling
4. Tableau Visualization
	- To manipulate the Tableau visualization - users will need to download Tableau:
	- https://public.tableau.com/en-us/s/
	
	
EXECUTION - How to run a demo on your code
1. TripAdvisor Scraper:
	-TripAdvisor Scraper can run end-to-end using the IPYNB or Python code files at the
	Github listed in the INSTALLATION and only visits public websites. To begin a demo of scraping
	TripAdvisor Reviews, choose a single URL from the ‘start_urls’ variable in Code Cell 1 - and
	delete all others. The scraper will now visit the chosen National Park and pull all reviews.
2. National Park Feature Engineering
	- To begin a demo of text processing, it can be run by starting from cell 1 and following
	until the cell labeled Generating words for review titles since it should run for about 2 minutes to
	clean up all review titles and process the words. The Generating Review Text data cells, will
	take about twenty minutes to process.
3. TripAdvisor Review Text Modeling
	- For each python file, the use case is included as comments in the file itself.
	- To run the python files, make sure the csv files are referenced with proper directory
	paths in the python code, and the output directory exists. Simply run python3 <filename>.py
	- To run the Azure ML Studio, create the experiment flow according to the one in the final
	report.
4. Tableau Visualization
	- For a demo of the visualization visit:
	-
	https://public.tableau.com/profile/charlie.leifheit#!/vizhome/Team97_Visualization_CSE6242/NPSVisitorSpending
