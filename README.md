# Web_Scanner


Web Application Vulnerability Scanner
A Python-based tool designed to detect common web application vulnerabilities such as Cross-Site Scripting (XSS), SQL Injection (SQLi), and Cross-Site Request Forgery (CSRF). This scanner features a Flask web interface for ease of use, automated crawling, payload injection, and detailed reporting.
Features

Vulnerability Detection: Identifies XSS, SQLi, and CSRF vulnerabilities.
Web Crawling: Uses requests and BeautifulSoup to explore target sites.
User Interface: Flask-based web app for initiating scans and viewing results.
Logging: Records vulnerabilities with severity and evidence in scan.log.
Modular Design: Easily extensible for additional vulnerability checks.

Requirements

Python 3.8 or higher
Dependencies listed in requirements.txt

Installation
Prerequisites
Ensure you have Python 3.8+ installed:
python3 --version

Steps

Clone the repository:git clone [https://github.com/your-username/web-vuln-scanner.git](https://github.com/kalyan14581/Web_Scanner.git)
cd web_scanner


Create a virtual environment:python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install dependencies:pip install -r requirements.txt


Verify the project structure:web-vuln-scanner/
├── vuln_scanner.py    # Core scanning logic
├── app.py            # Flask application
├── templates/        # HTML templates
│   ├── index.html
│   ├── report.html
├── requirements.txt  # Project dependencies
├── scan.log          # Log file
└── README.md         # This file



Usage

Run the Flask application:python3 app.py


Open your browser and navigate to http://localhost:5000.
Enter a target URL (e.g., http://testphp.vulnweb.com) and click "Start Scan".
View the scan results and click "View Detailed Report" for details.
Check scan.log for logged vulnerabilities:cat scan.log


Stop the server with Ctrl+C and deactivate the environment:deactivate



Project Structure

vuln_scanner.py: Contains the vulnerability scanning logic.
app.py: Main Flask application file.
templates/: Directory for HTML templates (index.html and report.html).
requirements.txt: Lists project dependencies.
scan.log: Log file for scan results.

Limitations

Designed for educational purposes; use only on authorized sites.
Limited to XSS, SQLi, and CSRF detection; expand payloads for broader coverage.
Crawling depth is capped at 2 to avoid excessive requests.
No authentication handling; extend for protected sites.




![Screenshot 2025-06-15 183157](https://github.com/user-attachments/assets/8b052c9d-0a14-4959-a3d3-86e156a15c82)
![Screenshot 2025-06-15 183212](https://github.com/user-attachments/assets/baccb00b-23b0-4601-b555-02b84fe5d4c6)

![Screenshot 2025-06-15 183657](https://github.com/user-attachments/assets/db454d82-0841-4062-9b8b-906e9e8a6e72)





