README
It automates the full workflow inside the Octopus SaaS application — starting from login and going all the way to generator creation, service setup, price book update, and logout.

The script automatically performs these steps:

Logs into the application
Creates a new Generator
Fills billing and address details
Updates latitude and longitude from map section
Sets service working hours
Assigns route to generator
Adds service details (date, frequency, weekdays, etc.)
Updates Price Book prices
Logs out and closes the browser

Tools & Technology Used:-

Python
Selenium WebDriver
Chrome Browser

Before You Run This Script make sure you have these installed:

1. Python
Check if Python is installed:
python --version

2. Install Selenium
Run this command:
pip install selenium

3. Chrome Browser
Install or update Google Chrome.

5. ChromeDriver
Download ChromeDriver based on your Chrome version and keep it:


How To Run

Go to your project folder and run:
python automation_script.py
Chrome browser will open and automation will start.

If script fails, check:
ChromeDriver version matches Chrome
Internet connection is stable
Application UI is not changed
Increase sleep time if page is slow

Author
Akanksha kumari
