# Trading Card Price Optimizer

## About

This Java program uses a list of trading card names and interacts with the eBay API to find the optimal selling price for each card. It then uploads the cards to eBay with pictures at the optimal price, either individually or grouped with other optimal cards.

## Prerequisites
- Java Development Kit (JDK)
- eBay API Key
- Required libraries:
  - JSON parsing library (e.g., org.json)
  - HTTP client library (e.g., Apache HttpClient)

## Setup
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ConorJones05/Trading_Card_Seller.git]
   ```
2. **Install dependencies:**
   Add the required libraries to your project's build path.

3. **Obtain an eBay API Key:**
   Follow the instructions on the [eBay Developer Program](https://developer.ebay.com/signin) to get your API key.

4. **Configure the API Key:**
   Set your eBay API key in the configuration file or directly in the code where the API client is initialized.

## Usage
1. **Prepare the list of trading card names:**
   Create a text file containing the names of the trading cards you want to price and upload.

2. **Run the program:**
   Execute the main class to start the process:
   ```bash
   java -jar trading-card-price-optimizer.jar
   ```

3. **Review the output:**
   The program will print the optimal prices and upload the cards to eBay with pictures.

## Code Explanation
- **Libraries Used:** JSON parsing library, HTTP client library
- **API Interaction:** The program uses the eBay API to fetch current market prices for each trading card.
- **Optimal Pricing:** It calculates the optimal selling price based on current listings and historical data.
- **eBay Upload:** The cards are uploaded to eBay with pictures at the calculated optimal price, either individually or in groups.

## Future Work
- Enhance the pricing algorithm with additional factors such as card condition and rarity.
- Add support for other trading card marketplaces.
- Implement a graphical user interface (GUI) for easier usage.

## Contributing
Feel free to fork this repository, make improvements, and submit pull requests. All contributions are welcome!
