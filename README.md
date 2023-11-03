Project Digitalization - WiSe 23/24

# First-Working-Package 
Data Acquisition, Preparation, Preprocessing and Evaluation. 

Objective :
This package aims to lay the groundwork for the project by acquiring, organizing, and evaluating data for subsequent stages of sustainability KPI extraction from annual reports.

# Project Proposal

Tasks :

1. Data Acquisition -
   
   ·Task 1.1 - Data Collection
      ·Identify reliable sources for annual reports of the 92 companies. https://docs.google.com/spreadsheets/d/1T2NnL4k2p51IMeotNYRFNGMmL_xP33zvhWRoWpPD8LY/edit#gid=2229353    
      ·Curate a list of URLs or sources for accessing the reports.
      ·Utilize web scraping tools or APIs for automated retrieval of report links.

   ·Task 1.2 - Data Storage
      ·Establish a structured database or file system to store report links    https://nextcloud.frankfurt-university.de/s/HZGB38ApYczPFd5

2. Data Preparation -
   
   ·Task 2.1 - Data Structuring
      ·Standardize the format of the acquired data.    
      ·Implement a consistent naming convention for the reports.
      ·Categorize data by company and publication date for easy retrieval.
      ·Find a way to convert pdf data into textual data.

   ·Task 2.2 - Cleaning -
      ·Scrutinize the acquired links for duplicates and rectify as necessary.  
      ·Address any inconsistencies in the report URLs.

4. Data Preprocessing -
   
   ·Task 3.1 - Initial Cleaning
      ·Conduct an initial cleanup to remove extraneous information from report links or metadata. 
      ·Address any broken links or inaccessible reports.

   ·Task 3.2 -  Data Enrichment
      ·Identify and extract pertinent metadata, such as report titles and locations.
      ·Establish a system for tracking the status of retrieved reports.

   ·Task 3.3 -  Data chunking
      ·Text Extraction with Regular Expressions (Develop regular expressions to identify and extract specific patterns within the reports, such as sustainability KPIs ,Utilize regular expressions to automate the extraction process.)
      ·Implement chunking techniques to break down large reports into smaller, more manageable sections. This makes the information more digestible and easier to process.

5. Evaluation -
   
    ·Task 4.1 - Data Quality Metrics
       ·Define a set of metrics to assess the quality of the acquired data, encompassing completeness, consistency, and relevance. 
       ·Generate a comprehensive report summarizing the data collection quality.

    ·Task 4.2 - Coordination with Other Groups
       ·Collaborate closely with the "Quantitative Metric" and "TCFD Task Force on Climate Financial Disclosure" groups to align data collection with their specific requirements. 
       ·Establish an efficient data-sharing protocol with these groups.

# Tools

·Data Collection:

 Web scraping tools (e.g., Beautiful Soup, Scrapy)
 APIs for accessing financial reports (e.g., SEC EDGAR)

·Data Storage:

 Database: https://nextcloud.frankfurt-university.de/s/HZGB38ApYczPFd5
 Version control systems like Git for tracking changes in data storage.

·Data Preprocessing:

Python libraries for data cleaning and enrichment (e.g., Pandas, NumPy)

·Data Quality Metrics:

Custom scripts for data validation and quality checks.
Coordination with Other Groups:

·Communication platforms (e.g., Discord https://discord.gg/usF2ZAnV)
  
