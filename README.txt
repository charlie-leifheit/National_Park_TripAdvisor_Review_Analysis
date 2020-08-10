DESCRIPTION - Describe the package in a few paragraphs

Four Github repos are required to execute the project from end to end:

1. TripAdvisor National Park Reviews Web Scraper
	- This scraper is built entirely in Python using Requests, BeautifulSoup, Pandas, and Tabula libraries.  The objective is to visit each of the 61 National Parks, locate all reviews for each park, obtain the review text, title, user, location, rating, and review date - then store the results for each park into a CSV.  

2.  National Park Feature Engineering
	- Daniel/Anil

3. TripAdvisor Review Text Modeling
	- Nathan

4. Tableau Visualization
	- This is a TWBX file showing the historical and forecasted National Park Spending per year, as well as the most distinct nouns and verbs per park.  The visualization can also be found at:

		-https://public.tableau.com/profile/charlie.leifheit#!/vizhome/Team97_Visualization_CSE6242/NPSVisitorSpending


INSTALLATION - How to install and setup your code

1. TripAdvisor Scraper:
	- The code was created using Google Colaboratory Jupyter Notebook and can be downloaded as an IPYNB or Python file from the GitHub listed below.  Instructions are include for scraping each National Park, however, the files have already been obtained and can be loaded it for quick manipulation.  The IPYNB file includes instructions for downloading the ZIP file of CSVs and loading into Google Colaboratory.  Users may need to install the following non-standard python libraries in Google Colaboratory or local machine: Tabula, Pandas, BeautifulSoup.  

	- https://github.com/charlie-leifheit/National_Park_TripAdvisor_Review_Analysis


2.  National Park Feature Engineering
	- Daniel/Anil

3. TripAdvisor Review Text Modeling
	- Nathan

4. Tableau Visualization
	- To manipulate the Tableau visualization - users will need to download Tableau:
		- https://public.tableau.com/en-us/s/

EXECUTION - How to run a demo on your code

1. TripAdvisor Scraper:	
	-TripAdvisor Scraper can run end-to-end using the IPYNB or Python code files at the Github listed in the INSTALLATION and only visits public websites. To begin a demo of scraping TripAdvisor Reviews, choose a single URL from the ‘start_urls’ variable in Code Cell 1 - and delete all others.  The scraper will now visit the chosen National Park and pull all reviews. 

2.  National Park Feature Engineering
	- Daniel/Anil

3. TripAdvisor Review Text Modeling
	- Nathan

4.  Tableau Visualization
	- For a demo of the visualization visit:
		- https://public.tableau.com/profile/charlie.leifheit#!/vizhome/Team97_Visualization_CSE6242/NPSVisitorSpending
 
