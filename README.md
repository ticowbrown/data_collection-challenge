# Module 11 Challenge
## Deliverable 1: Scrape Mars News
1. Visit the Mars News Site: Utilize automated browsing to access the Mars news website and identify the elements to be scraped, potentially using Chrome DevTools for inspection.
2. Scrape the Website: Implement Beautiful Soup to create a structured representation of the HTML and extract text elements from the website.
3. Store the Results: Extract titles and preview text of news articles, storing the scraping results in Python dictionaries with 'title' and 'preview' keys, and then aggregating them into a list for further processing.
## Deliverable 2: Scrape Martian Temperature Data
* Visit the Website: Access a webpage containing Martian temperature data for scraping.
* Create a Beautiful Soup Object: Utilize Beautiful Soup to parse the HTML content and create an organized representation for data extraction.
* Extract Data Rows: Locate and extract relevant data rows from the webpage, preparing them for further processing.
* Create a Pandas DataFrame: Construct a structured DataFrame using the extracted data rows and assign appropriate column names for analysis.
* Data Analysis: Perform data type conversions and calculations to answer questions about Martian months, days, temperatures, and atmospheric pressure.
	* Num_months was sorted to show the count of each month.
	* There are 1867 Martian days worth of data.
	* Avg_low_temp  was created to find the average low temperature by month. 
	* Avg_pressure was created to group average atmospheric pressure by month.
* Visualization: Generate plots to visualize temperature and pressure data trends, aiding in the interpretation of the findings.
	* A bar chart was generated to show the average low temperature by month.
	* A bar chart was generated to show the average low temperature by month sorted by coldest month to warmest.
		* On average, the third month has the coldest minimum temperature on Mars, and the eighth month is the warmest. But it is always very cold there in human terms!
	* A bar chart was generated to show the average atmospheric pressure by month sorted by lowest to highest.
		* Atmospheric pressure is, on average, lowest in the sixth month and highest in the ninth.
	* A line chart was generated to calculate how many terrestrial days are in a Martian year using minimum temperature.
		* The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.	
*Write Data to CSV: Export the processed data to a CSV file for potential future use or sharing with others.
