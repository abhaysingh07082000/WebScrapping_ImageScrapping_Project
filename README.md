Image Scraper Web App

This Flask web application scrapes images from Google based on user queries and stores them in MongoDB.

Overview
This web application allows users to search for images using keywords. It fetches images from Google search results, downloads them locally, and saves their binary data into a MongoDB database.

Features-

-Search for images using keywords.
-Download and store images locally.
-Save image data to MongoDB for future reference.

Setup
To run this application locally, follow these steps:

Clone the repository:
git clone https://github.com/yourusername/image-scraper.git
cd image-scraper

Install dependencies
pip install -r requirements.txt

Set up MongoDB:
Install MongoDB and ensure it's running on your local machine.
Create a MongoDB database named image_scrap.

Run the application:
python app.py
The application will run on http://localhost:8000 by default.

Usage
-Access the web application through a web browser.
-Enter a search query to fetch related images from Google.
-Images will be downloaded locally in the images/ directory.
-Image data will be stored in the image_scrap.image_scrap_data collection in MongoDB.

Dependencies-
Flask
Flask-Cors
Requests
BeautifulSoup4
pymongo


Contributing-
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
