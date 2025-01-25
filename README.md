# PRICELENS-E-Commerce-Tracker

**PriceLens🔍** is a web application that allows users to monitor and analyze product prices on e-commerce platforms, starting with Amazon. The platform offers real-time data scraping, price trend visualization, and product tracking to help users make informed purchasing decisions.

## Features
- **Dynamic Price Updates**: Use the "Refresh Prices" button to fetch and display the latest price data.
- **Top Deals Showcase**: Highlights curated deals for popular products.
- **Search Functionality**: Enables users to search for specific products on Amazon either by URL or by product name.
- **Interactive Price History Graphs**: Visualizes historical price trends to assist with strategic purchasing.
- **Personalized Tracking**: Add products to your cart and monitor their prices conveniently.

## Tech Stack
- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite3
- **Web Scraping**: Selenium, BeautifulSoup
- **Utilities**: asyncio, WebDriver for Selenium


## How to Run
1. Clone this repository:  
   ```bash
   git clone <https://github.com/binduu04/Pricelens-E-commerce-tracker.git>
   ```
2. Navigate to the project directory
3. Install the required dependencies
4. Run the Flask application:
 ```bash
 python app.py
 ```
5. Open the application in your browser
## Usage  
1. **Sign Up or Log In**: Create an account or log in to search products and add them to track.  
2. **Search for Products**: Enter the product URL or name in the search bar to fetch its details and price.  
3. **Track Products**: Add products to your cart to monitor their price changes over time.  
4. **Price History Visualization**: View detailed price history graphs for tracked products, showcasing price fluctuations since the product was added.  
5. **Real-Time Price Updates**: Use the "Refresh Prices" button to update the prices of all tracked products.

With these features, Price Lens ensures you never miss out on the best deals and helps you make informed purchasing decisions.  

## Note
Some dependencies in requirements.txt is additional, and were used while trying on different scraping logics.







