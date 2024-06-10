# Used Car Data Analysis Project

## Overview

In this project, our team developed a comprehensive approach to gather and analyze data on used cars from autolist.com, focusing on the San Francisco Bay Area. By employing web scraping techniques and leveraging MongoDB for data storage, we aimed to derive insights that could benefit both buyers and sellers in the used car market.

## Team Members

- Avantika Goyal
- Charles Wang
- Shalagha Mundepi

## Project Goals

- To collect detailed used car listings from autolist.com using web scraping.
- To analyze the gathered data to uncover trends related to vehicle pricing, preferences, and market dynamics in the San Francisco Bay Area.
- To provide actionable insights for consumers and dealerships, aiding in informed decision-making.

## Methodology

### Data Collection

We utilized Python Selenium’s ChromeDriver for web scraping and MongoDB for storing the extracted data. Our focus was on cars within a $20,000 price range and within 25 miles of zip code 94102 (San Francisco Bay Area).

### Data Extraction

For each car listed under our search criteria, we collected extensive details, including:
- Listing Title, Year, Make, Model
- Mileage, Location, Days on Market, Price
- Est. Monthly Payment, Listing URL
- Additional attributes like Trim, Transmission, Engine Type, etc., were extracted by visiting each car's listing page.

### Data Storage

All collected data were stored in MongoDB, chosen for its flexibility and compatibility with our data structure, allowing for future project scalability.

## Key Insights

- Our analysis revealed significant trends in vehicle pricing, types, and features preferred within the San Francisco Bay Area.
- We identified that compact and environmentally friendly vehicles, particularly EVs, are more favored in the area, aligning with broader environmental consciousness trends.

## Technologies Used

- **Python** for web scraping and data manipulation, with libraries such as Selenium, BeautifulSoup, and pymongo.
- **MongoDB** for data storage, allowing for flexible and scalable data management.

## Application in Business Domain

Our findings can empower dealerships with better inventory management strategies, customized customer engagement, and competitive pricing models. Additionally, consumers can benefit from a more informed vehicle purchasing process.

## How to Use

1. **Clone the repository** to access the project files and datasets.
2. Ensure you have **Python**, **Selenium**, and **MongoDB** set up in your environment.
3. Follow the scripts to **replicate the data collection** process or analyze the dataset for insights.

## Contributions

We welcome contributions to expand the dataset, enhance the analysis, or refine the scraping methodology. Feel free to fork the repository and submit your improvements or findings.

## Acknowledgements

We thank autolist.com for providing a rich source of used car listings that made this project possible. Our gratitude extends to our mentors and peers who supported us throughout this project. This is a final project completed as an assignment for UC Davis MSBA Course BAX-422 Data Design & Representation.
