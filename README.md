Email Extractor and Sender Script
This Python script automates the process of extracting email addresses from a given website and sending emails to those addresses. It uses BeautifulSoup for parsing the HTML content of the website and regular expressions (regex) to locate email addresses. Once the emails are extracted, the script sends a custom email to each address using an SMTP server.

Features
Email Extraction: The script can scrape any website to extract email addresses embedded in the webpage’s content.
Email Sending: After extracting the email addresses, the script sends an email to all found recipients with a customizable subject and body.
SMTP Integration: It uses Gmail's SMTP server by default to send emails, but can be configured to use other email providers.
How It Works
The user provides a URL of a website, and the script sends an HTTP request to retrieve the webpage’s content.
The script parses the webpage using BeautifulSoup and applies a regex pattern to find email addresses embedded in the text.
It removes any duplicate email addresses and displays them for the user.
The user then inputs the sender’s email credentials, the subject, and body of the email.
The script sends the email to all the extracted email addresses.
Use Cases
Marketing Campaigns: This tool can be used to extract email addresses from publicly available directories or websites and send promotional emails.
Web Scraping: Useful for scraping email addresses from websites with public contact information.
Automation: Automates the repetitive task of manually collecting emails and sending messages.
Important Considerations
Privacy and Legal Issues: Make sure to comply with the privacy policies and terms of service of any website you scrape. Unauthorized scraping can violate website rules or data protection regulations.
Email Sending Limits: Email services like Gmail impose sending limits to prevent spam. Be aware of these limits if you are sending to a large number of recipients.
Security: When using this script, be cautious when providing email credentials. Consider using application-specific passwords and avoid using personal email accounts for such operations.
