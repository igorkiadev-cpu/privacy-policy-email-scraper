# Privacy Policy Email Scraper

Python automation script that extracts publicly available contact email addresses from website Privacy Policy pages and exports the results to a clean CSV file.

This tool is designed to eliminate manual work when collecting contact information for lead generation, compliance research, or business outreach.

---

## Features

- Automatically finds Privacy Policy pages
- Extracts valid email addresses using regex
- Handles relative and absolute URLs
- Prevents duplicate emails
- Exports results to CSV format
- Configurable delay between requests (safe scraping)
- Simple and reusable Python code

---

## Tech Stack

- Python 3
- Requests
- BeautifulSoup4
- Regex
- CSV

---

## Project Structure

privacy-policy-email-scraper/
│
├── scraper.py
├── input_urls.txt
├── output.csv
├── requirements.txt
└── README.md


---

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/igorkiadev-cpu/privacy-policy-email-scraper.git
    cd privacy-policy-email-scraper
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## Usage

1. Add websites to `input_urls.txt` (one URL per line):
    ```
    https://example.com
    https://another-website.com
    ```
2. Run the script:
    ```bash
    python scraper.py
    ```
3. Extracted emails will be saved in `output.csv`:
    | Website             | Emails                                                                             |
    | ------------------- | ---------------------------------------------------------------------------------- |
    | example.com         | [contact@example.com](mailto:contact@example.com)                                  |
    | another-website.com | [support@site.com](mailto:support@site.com), [info@site.com](mailto:info@site.com) |

---

## Notes

Only publicly available emails are extracted.

 Use Cases for Freelancers:

- B2B lead generation
- Compliance and privacy research
- Contact discovery
- Marketing data collection
- Replacing manual data entry workflows

---

## Why This Project is Important

This project demonstrates:

- Real-world web data extraction
- Data extraction and cleaning
- Automation for business workflows
- Client-ready deliverables (CSV)

---

## Contact

If you need a customized automation or web scraping solution, please get in touch.

Always respect the website's terms of service.

The request delay can be adjusted to prevent blocking.
