# AI Projects Portfolio

## About Me

I’m currently building skills in Python, AI automation, and workflow engineering. I enjoy solving operational problems using automation tools, scripting, and AI-assisted development.

## Projects

### [🤖 Discord AI Chatbot](https://github.com/vasquez98gaspar-ctrl/-discord-ai-chatbot)
A Discord bot built using Python and Discord APIs. The project focused on automated interactions, command handling, and AI-assisted workflow logic.

**Skills Used:**

* Python
* Discord API
* Automation Logic
* Debugging

---

# Invoice Web Scraper

A Python-based scraper designed to extract invoice and tracking 
information from a web portal for workflow automation and operational processing.

## How It Works
The scraper logs into a web portal, navigates to the orders page, 
and extracts order numbers, tracking numbers, dates, and statuses.

## Features
- Automated login and order extraction
- Extracts order numbers, tracking numbers, dates and statuses
- Filters orders by today's date (configurable)
- Saves a debug HTML snapshot for troubleshooting
- Handles duplicate orders and edge cases automatically

## Dual Scraper Architecture
- **SeleniumScraper** — handles JavaScript-heavy pages, 
  automates browser login, clicks "Expand All" to reveal tracking numbers
- **StaticScraper** — parses plain HTML using BeautifulSoup, 
  used after Selenium fetches the page

## Debugging & Bug-Fixing Process
- Logging throughout every major step to track exactly where issues occur
- Saves raw HTML snapshot to `debug_orders_page.html` for inspection
- Switch between Selenium and Static mode via `config.USE_SELENIUM`
- Try/except blocks catch login failures, missing elements, and timeouts
- Duplicate orders handled via a `seen` set
- Edge cases filtered out (N/A, empty strings, label text stripped from cells)

## Skills Used
- Python
- Web Scraping (BeautifulSoup, Selenium)
- Data Processing
- Workflow Automation
- Debugging & Troubleshooting

## Dependencies
pip install requests beautifulsoup4 selenium webdriver-manager pyperclip
---

## [⚙️ n8n Automation Workflow](https://github.com/vasquez98gaspar-ctrl/n8n-automation-workflow)
Built automation workflows using n8n to reduce repetitive manual tasks and improve operational efficiency.

**Skills Used:**

* n8n
* Workflow Design
* Process Automation
* AI-Assisted Development

---

## Currently Learning

* Advanced Python
* API Integrations
* AI Workflow Systems
* Backend Development

## Goal

To continue building real-world AI and automation systems that improve operational efficiency and solve practical business problems.
