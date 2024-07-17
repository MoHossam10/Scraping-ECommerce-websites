# Scraping-ECommerce-websites




Website Overview:  
The targeted website chosen for web scraping is an e-commerce platform specializing in men's 
shoes from the Adidas Originals brand. The website offers a wide selection of products and 
enables users to browse and make purchases. 



Introduction:  
Web scraping is a technique used to extract data from websites. In this project, we employed 
web scraping to retrieve specific details about men's shoes from the Adidas Originals brand found 
on the Noon website. Our objective was to collect information such as product links, names, 
prices, ratings, company names, and image URLs. 



Libraries Used:  
To accomplish the web scraping task, we utilized various Python libraries: 
1. Requests: This library facilitated sending HTTP requests to the website and retrieving the 
HTML content of the pages. 
2. BeautifulSoup: We leveraged BeautifulSoup to parse the HTML content and extract 
relevant elements from it. 
3. CSV: The CSV library enabled us to write the extracted data into a CSV file for convenient 
storage and analysis.



Code Description: 
1. Importing Required Libraries: We imported the necessary libraries, including requests, 
BeautifulSoup, and CSV, to enable the required functionality. 
2. Sending HTTP Request: Using the requests library, we sent an HTTP GET request to the 
website's URL, allowing us to fetch the HTML content of the webpages. 
3. Parsing HTML Content: We utilized BeautifulSoup to parse and navigate through the 
HTML content, creating a BeautifulSoup object for further processing. 
4. Extracting Product Information: By analyzing the HTML structure of the website, we 
identified the relevant elements and utilized BeautifulSoup to extract the desired product 
information. This involved retrieving product links, names, prices, ratings, company 
names, and image URLs. Each category of information was stored in separate lists for 
organization. 
5. Saving Data to CSV File: To preserve the extracted information, we saved it to a CSV file 
named "product_information.csv". We opened the file in write mode and used the 
csv.writer to write the data as rows. Each category (header) and its corresponding list 
were written as separate rows in the CSV file.



Conclusion: Web scraping is a valuable technique for gathering data from websites. In this 
project, we successfully performed web scraping on the Noon website to collect detailed 
information about Adidas Originals men's shoes. By utilizing Python and the BeautifulSoup 
library, we extracted product links, names, prices, ratings, company names, and image URLs. The 
extracted data was then saved in a CSV file for further analysis and utilization. This project 
showcases the effectiveness of web scraping as a means of acquiring valuable data from online 
sources.
