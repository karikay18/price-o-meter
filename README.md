# Price Alert Web Scraper

This project is a simple Python script that checks the price of a product on an e-commerce site (like Amazon) and notifies you if the price drops below your set budget. The script fetches product details such as the title and price from the website and alerts you with a sound if the product is within your desired price range.

## Features

- Scrapes product information from a specified URL.
- Alerts you with a sound when the product price is within your budget.
- Customizable settings through a `settings.json` file.
- Configurable price reminder frequency.
- Cross-platform, works on any machine with Python installed.

## Requirements

Create a `settings.json` file in the root directory with the following structure:

Create a virtual environment and install the dependencies:

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

🚀 Congratulations! You've set up the project and are ready to use the price alert system.
