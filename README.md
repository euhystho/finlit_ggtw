# Financial Literacy for Grizzly Guide to Wealth 🐻💰

## ℹ️ Overview

The Grizzly Guide to Wealth is a Canvas Course offered by Ursinus College. In my internship, I created web-based financial calculators that provide tools for understanding various financial concepts like emergency savings, loan repayment, investment growth, and risk tolerance. These tools feature simple and intuitive interfaces and visual representations to make financial planning more accessible.

## 🧮 Calculators

### 💰 Annuity Calculator
- Calculate regular payout amounts from an initial investment
- Options for fixed period payouts or distribution amount calculations 
- Visual representation of balance and interest over time
- [Monte Carlo simulation mode for market forecasting using Normal Distribution](## "Adapted from Bill Mongan's Retirement Planner, which uses a Uniform Distribution")

### 💸 Expense Calculator
- Track income, savings goals, and various expense categories
- Flexible timeframe selection (monthly, semester, yearly)
- Organized expense categories with accordion-style interface
- Visual breakdown of financial snapshot through interactive charts
- Existing code available to switch to a pie chart if needed!

### 📈 Future Value Calculator
- Project growth of investments over time
- Account for initial investments and regular contributions
- Adjust for different interest rates and time periods
- Market forecasting mode with [simulated market fluctuations](## "Based on the Annuity Calculator's Monte Carlo Simulation")

### 🏦 Loan Repayment Calculator
- Calculate monthly payments for loans
- Visualize how much is going towards principal or interest over the loan term
- Adjust loan amount, interest rate, and repayment period
- See total cost of the loan including all interest payments

### ⚠️ Risk Tolerance Questionnaire
- Interactive quiz to determine individual investment risk profile
- Covers investment timelines, financial situation, investment knowledge, risk handling, and goals
- Provides personalized results categorizing users as conservative, moderate, or aggressive investors
- Includes key traits and examples for each investment style
- Offers a playful and fun way to calculate risk
- Developed with George Psaradakis

### 💵 Emergency Savings Calculator
- Calculate recommended emergency fund size based on monthly expenses
- Set saving goals with specific [start](## "Uses Date function to get current month and year") and end dates
- Visualize savings progress over time for both 3-month and 6-month emergency funds
- Calculate required monthly contribution to reach savings goals

## 💻 Technologies Used
- HTML5/CSS3 for structure and styling
- JavaScript for interactive functionality
- [Plotly.js](https://plotly.com/javascript/) for data visualization
- D3.js for [Monte Carlo Simulations](https://d3js.org/d3-random#randomNormal)

## 🚀 Getting Started
1. Clone this repository to your local machine
2. Open any of the HTML files in a modern web browser
3. Input your financial information to see calculations and visualizations

## 🎨 Customization
The calculators use [Ursinus College's branding colors and fonts](https://live.standards.site/ursinusbrandhub/visualsystem) by default. To customize:
- Modify the CSS variables in the `:root` selector in each file
- Update fonts by changing the font imports and font-family properties
- Adjust visualization colors in the Plotly plotting functions
- Modify Plotly code to add additional features!

## ⚠️ Disclaimer
These calculators provide estimates only and should not be considered as financial advice. For personalized financial guidance, consult with a qualified financial advisor.

