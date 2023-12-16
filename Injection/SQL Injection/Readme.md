# SQL Injection Vulnerability Scanner

This Python script is designed to identify potential SQL injection vulnerabilities within web applications. It uses a variety of techniques, including URL testing and form submission, to detect common SQL error responses that might indicate susceptibility to SQL injection attacks.

## Features

- **URL Testing**: Checks the provided URL for potential SQL injection vulnerabilities directly by appending quotes to the URL parameters.
- **HTML Form Analysis**: Scans HTML forms on the page and submits test payloads to identify possible SQL injection vulnerabilities.

## Prerequisites

- Python 3.x
- Required Python libraries (`requests`, `BeautifulSoup`) installed. Install them via:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/sql-injection-scanner.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the script:

    ```bash
    python scan_sql_injection.py
    ```

4. Provide the URL to be scanned as prompted.

## Vulnerability Detection

The script is designed to detect common SQL error responses in web pages that might indicate the presence of SQL injection vulnerabilities. It currently supports identifying vulnerabilities in MySQL, SQL Server, and Oracle databases based on specific error messages.

## Limitations

- The script may produce false positives.
- It detects only specific error messages and might miss some vulnerabilities.

## Disclaimer

This script is intended for educational and testing purposes only. Ensure proper authorization before scanning any website or web application.


