
# Web Scraping Gold: Python-Selenium Techniques for Analyzing Historical and Current Gold Prices

## Introduction
Scraping gold prices from websites such as Yahoo Finance can provide valuable data for investors and researchers interested in tracking the price of this precious metal. Using Python and the Selenium library, it is possible to automate the process of accessing the website, navigating to the relevant pages, and extracting the gold price data. This data can then be analyzed and used for a range of applications, such as identifying trends, forecasting prices, or creating trading strategies. However, it is important to be aware of the legal and ethical considerations of web scraping, such as copyright laws and user privacy, and to ensure that the scraped data is used responsibly.

## Steps Followed 

1. Importing the required libraries such as webdriver from selenium, Keys from selenium.webdriver.common.keys, and so on.
2. Defining the chrome options by adding arguments to disable GPU, start the browser in maximized mode, and disable notifications.
3. Setting the path for the chromedriver.
4. Creating an instance of the webdriver with the defined chrome options and the path.
5. Navigating to the URL of the website using the get() method.
6. Maximizing the window and clicking on the date range dropdown to expand it.
7. Entering the start and end date using the clear() and send_keys() methods respectively.
8. Clicking on the 'Done' and 'Apply' buttons to apply the date range filters and then scrolling down to load all the data in the table using the execute_script() method and finding the required data using the find_elements() method.
9. Define a helper function to extract the data for each column (date, open, high, low, price, volume) using Selenium's find_elements() method and store them in dictonary.
10. Define a helper function which converts dictonary into pandas tabular and return a csv file.

## Conclusion

- In conclusion, this project demonstrates the value of web scraping for data analysis, particularly from `01-09-2000 to 30-03-2023` for this period gold prices was tracked . By automating the process of accessing and extracting data from websites using Python and Selenium, we can gather data of about `5751 rows and 7 columns` quickly and efficiently.

- For further analysis the project highlights the importance of understanding the legal and ethical considerations of web scraping, as well as the technical challenges that can arise, such as navigating complex website layouts. However, with the right tools and techniques, web scraping can provide valuable insights into market trends and patterns that can inform investment strategies or research projects. 

- The use of Selenium and Python for web scraping offers several benefits, including ease of use, flexibility, and compatibility with a range of data analysis tools and libraries. Overall, web scraping using Python and Selenium is a powerful tool for data analysis that can provide valuable insights into a range of domains, from finance to social media.

## Reference
    
   This project drew on a variety of sources to support the development and implementation of the web scraping process. These included documentation for the Selenium library and the Python programming language, as well as tutorials and forums related to web scraping and data analysis. In addition, research articles and publications related to gold prices and market trends were consulted to inform the analysis and interpretation of the scraped data. The following list provides a selection of the sources used in the project:

- Selenium documentation: https://www.selenium.dev/documentation/en/
- Python documentation: https://docs.python.org/
- Stack Overflow: https://stackoverflow.com/

These sources were instrumental in providing guidance and insights throughout the project, and can serve as valuable resources for others looking to develop their skills in web scraping and data analysis.


