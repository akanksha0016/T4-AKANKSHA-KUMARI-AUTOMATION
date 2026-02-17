Overview

This document explains how the Octopus SaaS application is automated using Selenium and Python.

The automation script performs the full process from Login to Logout automatically.

Tools Used
1.Selenium WebDriver

Selenium is used to control the browser automatically.
It helps to:

Click buttons

Type text

Select dropdown options

Select checkboxes

Move between pages

2.PyCharm

PyCharm is used to write and run the Python automation script.
It also helps to fix errors and manage project files.

3.Google Chrome

The automation runs on the Chrome browser.

4.ChromeDriver

ChromeDriver connects Selenium with the Chrome browser.
Without it, automation cannot run on Chrome.

Programming Language
Python

Python is used because it is:

Easy to learn
Easy to read
Easy to maintain
Project Structure

The automation is written in one Python file.

The code is divided into sections using comments, like:

Login
Add Generator
Billing Information
Service Hours
Route Assignment
Price Book
Logout



The script performs these steps:

Login to the application
Create new Generator
Fill Generator and Billing details
Check Latitude and Longitude
Set Service Hours
Assign Route
Add Service
Update Price Book
Logout

Two types of waits are used:

Implicit Wait → Waits for elements to load
time.sleep() → Adds manual wait time when needed

Locators Used

The script finds elements using:

ID
XPath
Text-based XPath
Contains XPath (for dynamic elements)

Conclusion

This automation is created using Selenium and Python.
It covers the complete workflow of the application step by step.
