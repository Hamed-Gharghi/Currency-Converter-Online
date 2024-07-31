# Currency Converter Online

![Python Version](https://img.shields.io/badge/python-3.6%2B-blue)
![PyQt5 Version](https://img.shields.io/badge/pyqt5-5.15.11-blue)
![Alpha Vantage API](https://img.shields.io/badge/Alpha_Vantage-API-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

## Description

Currency Converter Online is a user-friendly desktop application built with PyQt5 that allows users to convert amounts between different currencies using real-time exchange rates provided by the Alpha Vantage API. It offers a simple interface with currency selection and conversion features.

## Features

- Real-time currency conversion using the Alpha Vantage API.
- Display of currency symbols alongside currency names in drop-down lists.
- User-friendly interface built with PyQt5.
- Support for a wide range of currencies.

## Screenshots

![Screenshot](./screenshot.png)

## Requirements

- Python 3.6 or higher
- PyQt5
- Requests library

You can install the required Python libraries using pip:

```sh
pip install PyQt5 requests
```

## API Key

This project uses the Alpha Vantage API for currency conversion. You will need an API key to use the service. Obtain your free API key from [Alpha Vantage](https://www.alphavantage.co/support/#api-key) and replace the placeholder in the code.

## Setup

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/Currency-Converter-Online.git
   ```

2. **Navigate to the project directory:**

   ```sh
   cd Currency-Converter-Online
   ```

3. **Install the required libraries:**

   ```sh
   pip install PyQt5 requests
   ```

4. **Replace the API key in the code:**

   Open `main.py` and replace `YOUR_API_KEY_HERE` with your actual Alpha Vantage API key.

5. **Run the application:**

   ```sh
   python main.py
   ```

## Usage

- Select the base currency from the first drop-down list.
- Select the target currency from the second drop-down list.
- Enter the amount you want to convert in the first input field.
- Click the "Convert" button to see the converted amount in the second input field.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Hamed Gharghi

## Acknowledgments

- [Alpha Vantage](https://www.alphavantage.co) for providing the currency exchange rates API.
- [PyQt5](https://riverbankcomputing.com/software/pyqt/intro) for the GUI framework.

## Contact

For any questions or feedback, please contact me at [Hamedgharghi1@gmail.com](mailto:Hamedgharghi1@gmail.com).

## Tags

- `Python`
- `PyQt5`
- `Currency Converter`
- `GUI Application`
- `Alpha Vantage API`
- `Exchange Rates`
- `Real-time Conversion`
- `Financial Software`
- `Open Source`
- `MIT License`
