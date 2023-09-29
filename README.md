# <B>Cash Pulse</B>

### Cryptocurrency Tracker with Real-time Data Visualization

## Description

This repository contains a React-based Cryptocurrency Tracker application that allows users to monitor various cryptocurrencies in real-time. The app provides data visualization and updates for different currencies, as well as a carousel displaying the top-performing currencies. It utilizes ContextAPI to prevent recursive drilling of data and employs the useEffect hook for handling side effects. The application fetches data from the GekoCoins website's API endpoints, such as Trending and coin list, using Axios.

## Technologies and Tools Used

- React: A JavaScript library for building user interfaces.
- ContextAPI: State management solution to avoid prop drilling and manage global state.
- useEffect Hook: Used to handle side effects, such as fetching data from APIs.
- Axios: A library for making HTTP requests to fetch cryptocurrency data from GekoCoins API.
- Chart.js: A popular charting library for creating interactive data visualizations.
- Bootstrap: CSS framework for styling the application.
- React-Slick: A carousel component for displaying the top currencies.

## Home Page

![image](https://github.com/shrey9393/cash-pulse/assets/80638949/dc2b0ac2-c1ec-4dff-b4b4-168ead1726d5)

The home page of the Cryptocurrency Tracker application displays real-time data for various cryptocurrencies. The page is designed to be user-friendly and intuitive. It consists of the following components:

1. Real-time Updates: The application leverages WebSocket technology to provide real-time updates on cryptocurrency prices, trends, and other data. As the data changes, the charts and graphs on the home page are automatically updated to reflect the latest information.

2. Data Visualization: The home page includes interactive charts and graphs created using Chart.js. These visualizations represent cryptocurrency trends and performance over time. Users can hover over data points to view specific information about each data point.

3. Top Currency Carousel: At the top of the home page, there is a carousel that showcases the top-performing currencies. Each slide in the carousel displays essential information about a specific cryptocurrency, such as its name, symbol, current price, and percentage change.

4. Search Functionality: Users can use the search bar to find specific cryptocurrencies by their name or symbol. When a user enters a query, the application filters the displayed data to match the search term.
5. Currency Selection: The home page provides functionality for users to change the currency displayed on the application. Users can select their preferred currency from a drop-down menu, and all prices and data will be converted accordingly.

## Coin Detail Page

![image](https://github.com/shrey9393/cash-pulse/assets/80638949/ae53311a-3d13-483b-b27a-ff79510d5f14)

The Coin Detail Page provides more detailed information about a specific cryptocurrency. When a user clicks on an individual currency from the home page or uses the search functionality, they are directed to this page. The page contains the following components:

1. Coin Information: The top section of the page displays comprehensive information about the selected cryptocurrency. This includes its name, symbol, current price, market cap, volume, circulating supply, and other relevant data.

2. Time Frame Selection: Similar to the home page, the Coin Detail Page allows users to choose the time frame for the historical data visualization. This enables users to analyze the cryptocurrency's price trends over different periods.

3. Historical Data Chart: Below the coin information, there is a historical data chart representing the price history of the selected cryptocurrency over a specified period. Users can interact with the chart to explore price trends and fluctuations.

4. Additional Details: This section provides additional details about the cryptocurrency, such as its rank in the market, the total supply, and the maximum supply.

5. Back Button: A back button is available at the top of the page, allowing users to return to the home page or their previous navigation.

## Installation

1. Clone the repository to your local machine.

```bash
git clone https://github.com/yourusername/cryptocurrency-tracker.git
```

2. Navigate to the project directory.

```bash
cd cryptocurrency-tracker
```

3. Install dependencies using npm or yarn.

```bash
npm install
# or
yarn install
```

4. Start the development server.

```bash
npm start
# or
yarn start
```

5. Open your browser and go to `http://localhost:3000` to view the application.

## Usage

- Upon launching the application, you will be presented with real-time data for various cryptocurrencies on the home page.
- Use the search functionality to find specific cryptocurrencies by their name or symbol.
- Click on individual currencies to view more detailed information on the Coin Detail Page.
- The data is displayed in interactive charts and graphs, allowing you to analyze cryptocurrency trends over time.
- The application will automatically update data as new information becomes available through the WebSocket connection.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## Acknowledgments

- We would like to thank the developers of the various open-source libraries used in this project, as they have greatly contributed to the application's functionality and ease of development.
