## Admin FinderX Pro - Advanced Security Scanning Tool
Admin FinderX Pro is a comprehensive security scanning tool designed for penetration testers and security professionals. It provides a user-friendly GUI for discovering potential vulnerabilities and sensitive information on target websites.

## Key Features
Admin Panel Discovery: Scan for common admin login pages

Email Harvesting: Extract email addresses from target websites

Subdomain Enumeration: Discover subdomains through brute-force

Vulnerability Scanning: Identify potential security flaws

Multi-threaded Scanning: Fast scanning with configurable threads

Proxy Support: Route traffic through proxies

Custom Wordlists: Load custom admin paths and subdomain lists

Multiple Report Formats: Export results as HTML, JSON, CSV, or TXT

## Installation
Prerequisites
Python 3.7+

Tkinter (usually included with Python)

## Installation Steps
Clone the repository:
```
git clone https://github.com/tawfique02/admin_finder.git
cd admin_finder
```
## Install required dependencies:
```
pip install -r requirements.txt
python encoded_main.py
```
Basic Scanning
Enter the target URL in the "Target URL" field

Configure scanning options:

Set number of threads (default: 15)

Enter proxy if needed (ip:port format)

Select scan types (Admin Panels, Emails, Subdomains, Vulnerabilities)

Click "Start Scan"

## Advanced Features
Load Custom Wordlists:

Use the File menu to load custom admin paths or subdomain lists

Save Results:

Export scan results in HTML, JSON, CSV, or text format

## Proxy Rotation:

Load a proxy list from file (File > Load Proxy List)

Features in Detail
Admin Panel Discovery
## Scans for common admin paths using:

Built-in list of common paths (admin, wp-admin, etc.)

Custom wordlist support

Checks HTTP 200 responses

Email Harvesting
Extracts emails from page content

Finds mailto: links

Removes duplicates automatically

Subdomain Enumeration
Brute-force subdomain discovery

Built-in common subdomains list

Custom wordlist support

Checks for valid HTTP responses

Vulnerability Scanning
CMS detection (WordPress, Joomla, Drupal)

Basic pattern matching for:

SQL Injection vulnerabilities

XSS vulnerabilities

Form analysis:

CSRF protection checks

Password field analysis

Input field validation

## Contributing
Contributions are welcome!
## License
This project is licensed under the MIT License - see the [LICENSE]() file for details.

## Disclaimer
This tool is intended for security testing and educational purposes only. The developers are not responsible for any misuse of this software. Always obtain proper authorization before scanning any systems.

Use Responsibly!
