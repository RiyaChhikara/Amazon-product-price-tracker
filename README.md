# Amazon-product-price-tracker
This Python script monitors the price of a product on Amazon and sends an email alert when the price drops below a specified threshold. It uses web scraping to fetch the product's price and title from Amazon, and it sends the alert via an SMTP email using the Gmail server.

## Prerequisites
Before using this script, you need to have the following:

- Gmail Account: You should have a Gmail account from which you want to send the email alerts.

- Python and BeautifulSoup: Ensure you have Python installed and the BeautifulSoup library. You can install BeautifulSoup using pip:
  - pip install beautifulsoup4
  
- SMTP Library: Python's built-in SMTP library is used for sending emails. You don't need to install it separately; it's part of the Python standard library.

## Configuration
You need to set the following variables in the script:

- EMAIL: Replace this with your Gmail email address.
- SMTP_ADDRESS: Use the Gmail SMTP server address, which is "smtp.gmail.com."
- PASSWORD: Replace this with your Gmail account password.
- URL: This is the URL of the Amazon product you want to monitor. Ensure it is up-to-date and points to the correct product.
  
## Usage
Open a terminal and navigate to the directory containing the Python script.

Run the script using the following command:

- python amazon_price_alert.py
 
The script will scrape the Amazon product page to retrieve the price and title of the product.
It will compare the price to the specified BUY_PRICE. If the price is lower than the threshold, it will send an email alert.

## Customization
You can change the URL variable to monitor a different Amazon product.

Adjust the BUY_PRICE threshold to the price at which you want to receive an alert.

## Acknowledgments
This script was created by Riya as a learning project.
If you encounter any issues or have suggestions for improvement, please feel free to file an issue or create a pull request on the GitHub repository.







