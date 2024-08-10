Currency Converter In Java

Project Overview :-

Welcome to the Currency Converter, a handy tool that lets you seamlessly convert amounts between some of the world's most prominent currencies. Whether you're tracking your expenses while traveling or simply curious about exchange rates, this application has you covered. The converter currently supports a curated selection of currencies: INR-Indian Rupee", "CAD-Canadian", "USD-United States Dollar", "EUR-Euro", "AUD-Australian", "GBP-Britain Pound". If you're working with other currencies, don't worry—this project can be expanded or integrated with additional APIs for broader use.

How It Works :-

1. User Input: Start by entering the amount you wish to convert. Next, select your source currency and the target currency. It's that     simple! 
2. .Conversion Logic: The application uses predefined conversion rates to calculate the converted amount. For example:
   - USD to GBP : Multiply the amount by 0.78.
   - GBP to USD: Multiply the amount by 1.28.
   - And so on for other currency pairs.
3.Validation: The application checks for valid input (numeric values) and displays an error message if the user enters invalid data.
4.Reset and Exit: Users can reset the form or exit the application as needed.

How I Built This Project :-

1. Java Swing: I used Java Swing to create the graphical user interface (GUI) for this application. Swing provides components like buttons, 
text fields, and combo boxes, allowing users to interact with the program.

2. Conversion Logic: I implemented the conversion logic based on predefined exchange rates. Each currency pair has a specific conversion 
factor, which I applied to the user's input.

3. Error Handling: To ensure a smooth user experience, I added error handling for invalid input (e.g., non-numeric characters).

4. User Experience: The application provides a clear interface for users to input data, view the converted amount, 
and reset or exit the program.

Limitations :-

1. Supported Currencies: While the converter currently supports a select list of currencies, there's potential to expand its capabilities. If you need more currency pairs, additional tools or APIs can be integrated.

2. Exchange Rates: Keep in mind that the exchange rates used are static and may not reflect the latest market conditions. For critical conversions, double-check the rates to ensure they meet your needs.

Feel free to check out the code, add your own touches, or ask any questions you have. Thanks for using this Currency Converter—happy converting!


