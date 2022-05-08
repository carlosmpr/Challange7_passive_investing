# Passive investing Application
In recent years, finance has had an explosion in passive investing. Passive investing means that you invest in a basket of assets that’s called an exchange-traded fund (ETF). This way, you don’t spend time researching individual stocks or companies or take the risk of investing in a single stock. ETFs offer more diversification.

## Technologies

- Jupyter notebook
- Sqlalchemy
- voila
---

## 1.Analyze a Single Asset in the ETF

-  SQL SELECT statement by using an f-string that reads all the PYPL data from the database. Using the SQL SELECT statement, execute a query that reads the PYPL data from the database into a Pandas DataFrame.
![image info](./Capture1.PNG)

- Using hvPlot, created an interactive visualization for the PYPL daily returns. Reflect the “time” column of the DataFrame on the x-axis
- Using hvPlot, created an interactive visualization for the PYPL cumulative returns.
![image info](./Capture2.PNG)

---

## 2. Optimize Data Access with Advanced SQL Queries

- Write a SQL SELECT statement to select the dates where the PYPL closing price was higher than 200.0
- Using the SQL statement, read the data from the database into a Pandas DataFrame, and then review the resulting DataFrame.
- Select the “time” and “close” columns for those dates where the closing price was higher than 200.0.
![image info](./Capture3.PNG)


---

## 3. Find the top 10 daily returns for PYPL by completing the following steps:

![image info](./Capture4.PNG)

---

## 4. Analyze the ETF Portfolio

- Writed a SQL query to join each table in the portfolio into a single DataFrame. To do so, complete the following steps:
- Created a DataFrame that averages the “daily_returns” columns for all four assets. Review the resulting DataFrame.
- Used the average daily returns in the etf_portfolio_returns DataFrame to calculate the annualized returns for the portfolio. Display the annualized return value of the ETF portfolio.
- Used the average daily returns in the etf_portfolio_returns DataFrame to calculate the cumulative returns of the ETF portfolio.
- Using hvPlot, create an interactive line plot that visualizes the cumulative return values of the ETF portfolio
![image info](./capture5.PNG)

![image info](./capture6.PNG)
---

##  Contributors
Brought to you by Carlos Polanco.

- Email: carlos.polanco0508@gmail.com
- GithubProfile: https://github.com/carlosmpr
- Linkedin: https://www.linkedin.com/in/carlosmpr/

---

## License

MIT

Copyright (c) 2012-2022

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.