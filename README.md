# Top-IT-Companies-WorldWide

Data Description
This dataset contains information about top IT companies worldwide, including:

Company Name: The name of the IT company.
Company Link: The URL of the company's profile page on the TechBehemoths website.
Locations: The geographical locations where the company has operations, such as cities, countries, or regions.
Service Speciality List: The primary services or areas of expertise offered by the company, such as web development, mobile app development, digital marketing, etc.
Team Size: The approximate number of employees or team members working at the company.
Founding Year: The year the company was established or founded.
Hourly Rate: The estimated hourly rate or pricing range for the company's services.
The data was obtained using a machine scraping technique from a publicly available source.

Machine Scraping Technique
To gather this data, I used a Python-based web scraping library called selenium. The scraping process involved the following steps:

Identified the target website and the relevant pages containing the company data.
Sent HTTP requests to the target URLs , handling any rate limiting or captcha challenges.
Parsed the HTML content of the pages using selenium to extract the required information.
Stored the extracted data in a Pandas DataFrame for further processing and analysis.
Some of the challenges I faced during the scraping process included:

Handling dynamic content loaded through JavaScript.
Dealing with inconsistent HTML structures across different pages.
Ensuring the scraping process did not overload the target website and cause any disruptions.
The code used for the scraping process is available in the company_scrabing.py file in this repository.

summary description of the data in the EDA_FOR_top-it-companies-worldwide.ipynb notebook:

The data provides an overview of top IT companies, their specialties, locations, team sizes, founding years, and hourly rates. This information can be used to analyze the IT industry, identify top players, understand service offerings, and potentially explore business opportunities.
