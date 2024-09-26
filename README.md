Lidyak HodlNodle

HodlNodle is a cryptocurrency portfolio tracker built on internet protocol to help users monitor and manage their investments in real-time. It provides a comprehensive view of portfolio performance, price tracking, and market trends, making it easier for cryptocurrency enthusiasts to stay informed about their holdings.

## Features

- **Real-Time Price Tracking**: Get updated prices from multiple exchanges.
- **Portfolio Management**: Track your cryptocurrency holdings, including profit and loss.
- **Market Overview**: See key metrics for all supported coins.
- **Custom Alerts**: Set notifications for price movements or specific portfolio events.
- **Secure Storage**: Keep your data private and secure, with no unnecessary third-party integrations.
  
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Supported Coins](#supported-coins)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites

Before setting up the project, ensure that you have the following installed:

- [Node.js](https://nodejs.org/en/) (v14 or later)
- [npm](https://www.npmjs.com/get-npm) or [yarn](https://yarnpkg.com/getting-started)

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/lidyakano/hodlnodle.git
   cd hodlnodle
   ```

2. **Install dependencies:**

   Using npm:
   ```bash
   npm install
   ```

   Or, using yarn:
   ```bash
   yarn install
   ```

3. **Configure Environment Variables:**

   Create a `.env` file in the root directory and add necessary environment variables like API keys for fetching cryptocurrency data from your chosen providers.

   Example:
   ```bash
   API_KEY=your_api_key_here
   ```

4. **Start the application:**

   For development mode:
   ```bash
   npm run dev
   ```

   For production mode:
   ```bash
   npm run build
   npm start
   ```

5. **Access the application:**

   After starting the application, open your browser and navigate to `http://localhost:3000` (or the appropriate port).

## Usage

Once the application is running, you can begin by:

1. **Adding your portfolio:** Enter the amount and type of cryptocurrency you own, and the app will begin tracking its performance.
2. **Viewing market trends:** Get a real-time overview of the entire cryptocurrency market.
3. **Setting alerts:** Stay on top of your investments by configuring custom alerts for price movements or portfolio changes.

## Supported Coins

HodlNodle supports the following cryptocurrencies (and many more):

- Bitcoin (BTC)
- Ethereum (ETH)
- INTERNET COMPUTER (ICP)

The list of supported coins can be extended by configuring the application with new API endpoints or market data sources.

## Contributing

We welcome contributions to improve HodlNodle! To get started:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a pull request

Please ensure your code follows the existing code style and includes relevant tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

If you have any questions or feedback, feel free to open an issue or reach out!

