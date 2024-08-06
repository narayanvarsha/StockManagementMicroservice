Stock Research Microservice:

Overview:
This microservice updates a text file with a new ticker symbol, uses the 'yfinance` library to fetch stock information, and writes the summary statistics to a JSON file and also displays the summary on the terminal.

Communication Contract:

Before we run any of the files we should install the 'yfinances library' by just running this line in the terminal.

<img width="124" alt="image" src="https://github.com/user-attachments/assets/88e905f7-7969-4c57-9470-5be5bf0e3860">


How to request data:
To request stock data, write the desired ticker symbol in the terminal. This will be updated in the 'ticker.txt' file. This file should be located in the same directory as the microservice script.

Example request: In the terminal, use the command line to update the ticker file. 
                 For example, to retrieve the stats about microsoft, you would put 'python test_microservice.py MSFT' in the terminal.

<img width="185" alt="image" src="https://github.com/user-attachments/assets/0193a901-e8b2-4b47-aefe-c05033384af0">

Another way to request stock data is by updating the 'ticker.txt' file with the desired symbol and save the file. Then, the summary of the stock will be displayed in the json file.

How to receive data:
After the microservice processes the ticker symbol, it writes the stock data to the 'stock_summary.json' file. You can read this file to get the stock information.

Example output: The 'stock_summary.json' file will contain a JSON object with the following structure:


<img width="296" alt="image" src="https://github.com/user-attachments/assets/c75c18e4-7d0f-4256-a80d-25153746d781">




UML Diagram:


<img width="788" alt="image" src="https://github.com/user-attachments/assets/e0a49470-5703-4217-9cee-ad99d2d47b41">


