Stock Research Microservice:

Overview:
This microservice updates a text file with a new ticker symbol, uses the 'yfinance` library to fetch stock information, and writes the summary statistics to a JSON file and also displays the summary on the terminal.

Communication Contract:

How to request data:
To request stock data, write the desired ticker symbol in the termianl. This will be updated in the 'ticker.txt' file. This file should be located in the same directory as the microservice script.

Example request: In the terminal, use the command line to update the ticker file. 
                 For example, to retrieve the stats about nvidia, you would put 'python test_microservice.py NVDA' in the terminal.

<img width="185" alt="image" src="https://github.com/user-attachments/assets/0193a901-e8b2-4b47-aefe-c05033384af0">


How to receive data:
After the microservice processes the ticker symbol, it writes the stock data to the 'stock_summary.json' file. You can read this file to get the stock information.

Example output: The 'stock_summary.json' file will contain a JSON object with the following structure:


<img width="296" alt="image" src="https://github.com/user-attachments/assets/c75c18e4-7d0f-4256-a80d-25153746d781">




UML Diagram:


<img width="788" alt="image" src="https://github.com/user-attachments/assets/e0a49470-5703-4217-9cee-ad99d2d47b41">


