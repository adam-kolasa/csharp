# MIRExampleScraper
Example Selenium script for MakeItRight Engineers

This is the demo I used to showcase web scraping websites to our client. This was not the final version of the project. Refer to https://roseberrypi.com/our-work/projects/lead-manager

This script will run Selenium ChromeDriver (C#) in headless mode as specified by the user through the console. The web scraper then scrapes realtors based on location, cleans the data, and outputs it to a .csv file.

This script was tested as of 2020-07-17 using Chrome -v 84.0.4147.89 and ChromeDriver 84.0.4147.30 (which is included in the project).

Project uses the .Net Core 3.1 Framework.

# To Use
Build the console application using your preferred tools and run the RealtorScraper.exe. Follow the prompts given in the console.

The output data (.csv) is located in the "Data" folder which is created at runtime if it does not already exist.


# Contact
For additional questions, email: hello@roseberrypi.com
