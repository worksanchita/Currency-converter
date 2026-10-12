# 💱 Currency Converter

A simple and responsive Currency Converter web application built using **HTML, CSS, and JavaScript**. It allows users to convert an amount from one currency to another using exchange-rate data fetched from an API.

## ✨ Features

- **Real-Time Currency Conversion:** Fetches the latest available exchange rates from an API.
- **Multiple Currencies:** Supports a wide range of currencies.
- **Country Flags:** Displays the corresponding country flag for the selected currency.
- **Default Currency Selection:** USD is selected as the default source currency and INR as the default target currency.
- **Currency Swap:** Easily switch the source and target currencies.
- **Dynamic Exchange Rates:** Updates the conversion result based on the selected currencies and entered amount.
- **Interactive UI:** Simple and user-friendly interface.

## 🛠️ Technologies Used

- **HTML5** — Structure of the application.
- **CSS3** — Styling and layout.
- **JavaScript** — DOM manipulation, event handling, and conversion logic.
- **Currency API** — [@fawazahmed0/currency-api](https://github.com/fawazahmed0/currency-api) for exchange-rate data.
- **Flags API** — [FlagsAPI](https://flagsapi.com/) for displaying country flags.

## 📁 Project Structure

```text
currency-converter/
├── index.html    # Application structure
├── style.css     # Styling and layout
├── code.js       # Currency-to-country code mapping
├── app.js        # Application logic and API requests
└── README.md     # Project documentation
```

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/currency-converter.git
```

### 2. Navigate to the project folder

```bash
cd currency-converter
```

### 3. Run the application

Open `index.html` in your browser, or use the **Live Server** extension in Visual Studio Code for a smoother development experience.

An active internet connection is required to fetch exchange rates and country flags.

## 💡 How It Works

1. Enter the amount you want to convert.
2. Select the source currency in the **From** dropdown.
3. Select the target currency in the **To** dropdown.
4. Click **Get Exchange Rate** to calculate the converted amount.
5. Use the swap button to reverse the selected currencies.

The application fetches exchange-rate data from the API and calculates the converted amount using the selected currencies.

## 📡 APIs Used

**Exchange Rates:**  
[Currency API by fawazahmed0](https://github.com/fawazahmed0/currency-api)

**Country Flags:**  
[FlagsAPI](https://flagsapi.com/)

Exchange rates may be delayed or unavailable depending on the API. The application requires an internet connection for API requests.


## 🔮 Future Improvements

- Display the exchange rate separately from the converted amount.
- Add input validation and improved error handling.
- Improve mobile responsiveness.
- Show the last updated time for exchange rates.
- Add conversion history.

## 👩‍💻 Author

**Your Name**

GitHub: [@worksanchita]

---

If you find this project useful, consider giving the repository a ⭐ on GitHub!