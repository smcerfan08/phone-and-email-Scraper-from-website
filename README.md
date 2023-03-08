<h1 align="center">Website Data Scraper (Email & Phone From Websites.)</h1>
<q>A Python script that visits a list of websites, extracts email addresses and phone numbers, and saves the results to an Excel file.</q>
<h3>Dependencies:</h3>
 <p>This script requires the following Python libraries:</p>
<ul>
  <li>openpyxl</li>
  <li>re</li>
  <li>selenium</li>
 </ul>
 <p>You can install these libraries using pip:</p>
 <code>pip install <b>openpyxl</b></code><br>
 <code>pip install <b>selenium</b></code>
 <h3>Usage:</h3>
 1. Create a text file named <code>websites.txt</code> containing a list of websites to scrape, with each website on a separate line. <br>
 2. Run the script using the following command: <code>python website_scraper.py</code><br>
 3. The script will visit each website, extract the email address and phone number (if available), and save the results to an Excel file named <code>results.xlsx</code>.<br>
 <h3>Additional Features</h3>
The script also checks if the URL starts with "https://" before visiting the website. If not, it will automatically add "https://" to the URL. This ensures that the script is able to visit the website without any errors.

<h3>Note</h3>
Please note that web scraping may violate the terms of service of some websites. Use this script responsibly and only on websites that allow web scraping.
