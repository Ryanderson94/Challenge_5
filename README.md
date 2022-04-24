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
<img width="685" alt="Screen Shot 2022-04-24 at 7 34 00 PM" src="https://user-images.githubusercontent.com/98444459/165001308-15664dd8-218d-4c41-aa2b-860fe44dc411.png">

3. If you receive errors, please review the dependencies above, install them and try again. 

4. Set up an Alpacas account by navigating to https://app.alpaca.markets/signup. 
<img width="526" alt="Screen Shot 2022-04-24 at 7 41 59 PM" src="https://user-images.githubusercontent.com/98444459/165001577-2543dfa3-2d40-4030-9f69-ad4b81db11c1.png">

---

## Usage

1. Navigate to the directory in either the Terminal or GitBash. 

2. From the top folder (Challenge_5), launch jupyter lab by typing 'jupyter lab' into Terminal or Gitbash and pressing 'Enter'
<img width="498" alt="Screen Shot 2022-04-10 at 7 21 15 PM" src="https://user-images.githubusercontent.com/98444459/162644238-051cd580-bf09-4bc9-9b77-1b495632f4c1.png">

3. Open the 'financial_planning_tools.ipynb' notebook and follow the instructions therein.  
<img width="299" alt="Screen Shot 2022-04-24 at 7 49 14 PM" src="https://user-images.githubusercontent.com/98444459/165001822-7557d950-a365-4ebf-896d-933e17a4fcf4.png">

4. Obtain your API Key and API Secret Key from Alpacas
<img width="305" alt="Screen Shot 2022-04-24 at 7 45 24 PM" src="https://user-images.githubusercontent.com/98444459/165001976-d26f6993-a6e0-4dd1-a992-13596913acb9.png">

5. Create a .env file in which to store your API Key and API Secret Keys from Alpacas.
<img width="965" alt="Screen Shot 2022-04-24 at 7 52 12 PM" src="https://user-images.githubusercontent.com/98444459/165001945-9cc12442-8b66-4157-bd87-c1f60682380c.png">

---

## Contributors

Made by:
Ryan Anderson
  Email: m.anderson.ryan@gmail.com
  LinkedIn: https://www.linkedin.com/in/ryan-anderson-57b2b173

---

## License

While a license is not required, a free account from Alpacas is requried and the sign up can be found here https://app.alpaca.markets/signup. This will provide you with an API Key and API Secret Key that can be used to fetch data to be used in the analysis.
