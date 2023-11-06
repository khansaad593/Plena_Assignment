# Plena_Assignment
# CoinGecko Token Widget

This repository contains a JavaScript widget script that fetches and displays CoinGecko token details for a specified token. The script can be embedded into a web page using a script tag. The displayed information is presented in a table format in the middle of the page, organized into three rows as follows:

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Example](#example)
- [Credits](#credits)
- [License](#license)

## Features

1. **Token Logo and Name**
   - Displays the token's logo and name.

2. **Token Metrics**
   - Market Cap
   - Current Price
   - 24-hour Trading Volume

3. **Powered by CoinGecko**
   - Provides a hyperlink to CoinGecko's website.

## Usage

1. Clone or download this repository to your local machine.

2. Open the `index.html` file in a web browser.

3. Customize the widget by changing the token name in the `createCoinGeckoWidget` function.

    ```javascript
    createCoinGeckoWidget('bitcoin'); // Replace 'bitcoin' with your desired token name
    ```

4. View the token information displayed in the table format on the web page.

## Dependencies

- This widget script utilizes the CoinGecko API to fetch token details.

## Example

You can view an example of the widget by opening the `index.html` file in a web browser.

## Credits

This widget is powered by [CoinGecko](https://coingecko.com).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
