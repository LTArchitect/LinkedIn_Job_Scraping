### Overview
This notebook is designed to scrape tech-related job postings from LinkedIn. The goal is to extract key information such as job titles, company names, locations, job links, posting dates, and Easy Apply availability. The data is then saved into a CSV file for further analysis.

### How it Works
- **Data Source**: The HTML content of LinkedIn job search result pages is fetched using the `requests` library.
- **Web Scraping**: `BeautifulSoup` is used to parse the HTML and extract job details like titles, companies, and locations.
- **Data Output**: The extracted data is stored in a CSV file, making it easy to analyze or manipulate for further use.
- **Customization**: Filters can be applied manually on LinkedIn before fetching the data to focus on specific job criteria like location, job type, or posting date.