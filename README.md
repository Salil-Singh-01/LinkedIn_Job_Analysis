# Linkedin Job Scrapping and Anlaysis
<hr>

## Project Overview

This project aims to analyze the job market by scraping job data from LinkedIn and visualizing key insights through a Power BI dashboard. The main objective is to help job seekers and industry professionals understand trends in the job market, such as demand by company, job level, and more. We used Python for data collection, cleaning, and preparation, and Power BI for creating an interactive dashboard to display the findings.

![Project Logo](https://drive.google.com/uc?export=view&id=1c5_lh7amJHCu7X0BItFOsDtylv89lYMH)
[LinkedIn Jobs-Page](https://www.linkedin.com/jobs/collections/)

<hr>

## Project Steps

### 1. Data Collection

We used **web scraping** to collect job data directly from LinkedIn. The tools and libraries used for this process included:
- **Selenium**: For automating the browsing and scraping process.
- **Beautiful Soup**: For parsing HTML and extracting relevant information from the LinkedIn job postings.

### 2. Data Processing

After collecting the raw data, we processed it in **Python** using **Pandas**:
- **Data Cleaning**: Removed any duplicate or irrelevant entries and handled missing data to ensure accuracy.
- **Data Transformation**: Organized the data into a structured format, making it easier to analyze.

The final dataset was saved as a **CSV file** for further analysis and dashboard creation.

### 3. Data Analysis and Dashboarding

For the visualization part, we used **Power BI** along with **DAX (Data Analysis Expressions)** to create a comprehensive dashboard. The dashboard includes several key visuals to represent the job market trends, such as:
- **Jobs by Company**: Showing the distribution of jobs posted by different companies.
- **Jobs by Level**: Displaying the number of job openings at various experience levels.
- **Main Overview**: Highlighting additional insights like top job titles, industries, and locations.

### 4. Key Insights from the Dashboard

Here are some insights we gathered from our analysis:

- **Top Hiring Companies**: Certain companies were consistently hiring the most across various job roles.
  
- **Jobs by Experience Level**: Entry-level positions made up the majority of job postings, suggesting a strong demand for fresh talent.
  
- **Job Titles in Demand**: Popular job titles included roles like "Data Analyst," "Software Engineer," and "Project Manager."
  
- **Top Locations for Jobs**: Major cities like Bangalore, Mumbai, and Delhi had the most job postings.
  
- **Industry Breakdown**: The IT and Software industries dominated the job postings, followed by Finance, Healthcare, and E-commerce sectors.

  <hr>

### Team Contribution

This project was a team effort by a group of 5 members. Each member contributed to different parts of the project, from data scraping and cleaning to data analysis and visualization. The collaboration helped us complete the project efficiently and gain a better understanding of the LinkedIn job market.
> Team members are -
## Contributors

- ![GitHub](https://img.shields.io/badge/Anjani%20Nandan-333?logo=github&logoColor=white&labelColor=333)(https://github.com/anjanicoder)
- ![GitHub](https://img.shields.io/badge/Salil%20Singh-333?logo=github&logoColor=white&labelColor=333)(https://github.com/Salil-Singh-01)
- ![GitHub](https://img.shields.io/badge/Aamir%20Khan-333?logo=github&logoColor=white&labelColor=333)(https://github.com/aam1rkhan)
- ![GitHub](https://img.shields.io/badge/Tauheed%20Ahmad-333?logo=github&logoColor=white&labelColor=333)(https://github.com/tauheed7080)
- ![GitHub](https://img.shields.io/badge/Jaishree%20Yadav-333?logo=github&logoColor=white&labelColor=333)(https://github.com/Jayadavv)

  <hr>

## Tools and Technologies Used

- **Python**: For data scraping, cleaning, and transformation
  - **Selenium**: Web scraping
  - **Beautiful Soup**: HTML parsing
  - **Pandas**: Data manipulation
- **Power BI**: For creating an interactive dashboard
- **DAX**: For calculations and expressions in Power BI visuals

  <hr>

## Project Objective

The main goal of this project was to **analyze the job market on LinkedIn** to uncover insights into:
- Which companies are actively hiring
- The demand for various experience levels
- Other trends in job postings

These insights can assist job seekers in targeting companies and roles that match their skills and experience level, as well as give companies a view of the competitive hiring landscape.

<hr>

## Installation and Configuration

### Prerequisites

- **Python 3.x**: Make sure Python is installed on your system.
- **Chrome Browser**: Required for Selenium to automate LinkedIn navigation.
- **ChromeDriver**: Ensure you download the ChromeDriver that matches your Chrome version. Place it in your PATH or specify its path in your code.

### Libraries

Install the required Python libraries using the following command:
```bash
pip install selenium beautifulsoup4 pandas
```

### LinkedIn Credentials

Since LinkedIn requires a login to view job postings, you’ll need to provide your LinkedIn credentials in the script. **It’s recommended to store credentials securely** and not hard-code them directly in your code.

### Steps for Setup

1. **Clone the Repository**: Clone or download the project files from the repository.

2. **Set Up ChromeDriver**: Ensure `chromedriver.exe` is in your PATH or specify its path in the Selenium script.

3. **Edit Configurations**:
   - Update the LinkedIn login credentials in a secure way. You may use environment variables or a configuration file (e.g., `config.json`).

4. **Run the Scraper**:
   - Open the terminal, navigate to the project folder, and run the scraper:
   ```bash
   python linkedin_scraper.py
   ```

5. **Data Processing**:
   - After scraping, run the data processing script to clean and transform the data. This will generate the final CSV file ready for visualization.

### Power BI Setup

1. **Open Power BI**: Import the final CSV file created from the data processing step.
2. **Use the Dashboard Template**: Apply DAX expressions as needed to create visuals. Customize the dashboard to display insights such as jobs by company, job level, and location.

<hr>

## How to Use This Project

1. **Data Collection**: Use the provided Python scripts with Selenium and Beautiful Soup to scrape LinkedIn job data.
2. **Data Cleaning and Transformation**: Process the data using the provided cleaning and transformation functions in Python.
3. **Visualization**: Use Power BI to create or interact with the dashboard, applying filters and viewing insights as needed.

<hr>

## Conclusion

This LinkedIn Job Market Analysis Dashboard provides an overview of current job market trends, focusing on company hiring patterns, job levels, and more. By leveraging data scraping, data processing, and visualization tools, we created a user-friendly and informative dashboard to support job seekers and HR professionals in making data-driven decisions.

<hr>






<!-- 
![Project Logo](https://drive.google.com/uc?export=view&id=1c5_lh7amJHCu7X0BItFOsDtylv89lYMH)


The project Scope discusses how we have scrapped and analyzed the data on the LinkedIn platform. we have tried to cover different insights including how jobs are distributed in the country India so including various aspects such as how jobs are available based on Different cities and how many different applicants are applying for that particular job apart from that we have also covered how many numbers of followers or what is the count of followers of that particular company so that based upon that data a person can decide whether he/she wants to work with a startup or  Big MNCs



## Team Members
- [Anjani Nandan](https://github.com/anjanicoder)
- [Salil Singh](https://github.com/Salil-Singh-01)
- [Aamir Khan](https://github.com/aam1rkhan)
- [Tauheed Ahmad](https://github.com/tauheed7080)
- [Jaishree Yadav](https://github.com/Jayadavv)

# LinkedIn Job Analysis Project
![Dashboard Image](https://github.com/anjanicoder/JobDashboard/blob/e8c307e9a2e7c9fc392b01772ad8ae7c0fca3fd3/Project%20Image/main.jpg?raw=true)


<img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn" width="100"/>

Welcome to the LinkedIn Job Analysis Project!

## Overview

In this project, we scrape job data from LinkedIn using Beautiful Soup and Selenium. The data is then analyzed using Power BI, incorporating DAX queries for deeper insights.

## Tools and Technologies Used

### Web Scraping

<img src="https://www.crummy.com/software/BeautifulSoup/bs4/doc/_static/Logo2.png" alt="Beautiful Soup" width="100"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/Selenium_Logo.png" alt="Selenium" width="100"/>

- **Beautiful Soup**: A library for parsing HTML and XML documents. It creates parse trees that are helpful for extracting data from HTML.
- **Selenium**: A portable framework for testing web applications. It is also used for web scraping to interact with dynamic content.

### Data Analysis

<img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" alt="Power BI" width="100"/>

- **Power BI**: A business analytics tool by Microsoft. It provides interactive visualizations and business intelligence capabilities with an interface simple enough for end users to create their own reports and dashboards.
  - **DAX Queries**: Data Analysis Expressions (DAX) is a formula language used in Power BI to create custom calculations in calculated columns and measures.

## Project Structure

The project is structured as follows:

- **Scraping**: Scripts for scraping LinkedIn job data using Beautiful Soup and Selenium.
- **Data Processing**: Scripts for cleaning and preparing the scraped data for analysis.
- **Analysis**: Power BI reports and dashboards for visualizing the job data.

## How to Run the Project

1. **Setup the Environment**:
   - Install the required Python libraries:
     ```bash
     pip install beautifulsoup4 selenium
     ```

2. **Scrape the Data**:
   - Run the scraping scripts to gather job data from LinkedIn.

3. **Analyze the Data**:
   - Open the Power BI report and load the cleaned data.
   - Use DAX queries to create custom calculations and visualizations.

## Conclusion

This project comprehensively analyses job data from LinkedIn, using advanced web scraping techniques and powerful data analysis tools. It demonstrates the effective use of Beautiful Soup and Selenium for data collection and Power BI for data visualization and analysis.

You can explore the repository and use the scripts and reports for your own analysis. -->
