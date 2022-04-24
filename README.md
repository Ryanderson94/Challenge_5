# Financial Planning w APIs and Simulations

This application serves as an analysis for financial planning and potential retirement savings outcomes. It is flexible enough to accommodate Crypto holdings, as well as equities by accessing different, free API endpoints to pull up-to-date information.

With this application, you can obtain the current market value of any crypto investments, run a Monte Carlo simulation on any two-holding portfolio and ultimately obtain a more data-driven perspective on investment decisions.

As mentioned, this application can be used to analyze any crypto or stocks of a person's choice but in this particular example the two crypto holdings reviewed are Bitcoin and Ethereum and the two equities positions are SPY and AGG. These can be used as examples in constructing your own analysis.

At the end of this program, you will obtain 95% confidence interval high and low values for the portfolio outcomes that can help determine if you will be set up for retirement. 

---

## Technologies

This program leverages python 3.7+

To ensure all dependencies are installed and up-to-date, please run the following commands in your terminal once you have cloned the repository to your local machine.
run pip install -r requirements.txt

---

## Installation Guide

1. Copy this repository via the URL (SSH or HTTP)

<img width="907" alt="Screen Shot 2022-04-03 at 3 35 27 PM" src="https://user-images.githubusercontent.com/98444459/161445246-d4eecac4-44ae-452f-8e0c-ebaa9e523908.png">

2. Run a git clone command in your terminal or git bash under the desired local directory
<img width="753" alt="Screen Shot 2022-04-10 at 7 16 52 PM" src="https://user-images.githubusercontent.com/98444459/162644165-ab8f92db-10d9-47bb-b862-f8f14b9d1aa3.png">

3. If you receive errors, please review the dependencies above, install them and try again. 

---

## Usage

1. Navigate to the directory in either the Terminal or GitBash. 

2. From the top folder (Challenge_5), launch jupyter lab by typing 'jupyter lab' into Terminal or Gitbash and pressing 'Enter'
<img width="498" alt="Screen Shot 2022-04-10 at 7 21 15 PM" src="https://user-images.githubusercontent.com/98444459/162644238-051cd580-bf09-4bc9-9b77-1b495632f4c1.png">

3. Open the 'crypto_arbitrage.ipynb' notebook and follow the instructions therein.  
<img width="529" alt="Screen Shot 2022-04-10 at 7 22 55 PM" src="https://user-images.githubusercontent.com/98444459/162644301-f7527670-3415-4469-b8ab-ba6d6efa1899.png">

---

## Contributors

Made by:
Ryan Anderson
  Email: m.anderson.ryan@gmail.com
  LinkedIn: https://www.linkedin.com/in/ryan-anderson-57b2b173

---

## License

While a license is not required, a free account from Alpacas is requried and the sign up can be found here https://app.alpaca.markets/signup. This will provide you with an API Key and API Secret Key that can be used to fetch data to be used in the analysis.