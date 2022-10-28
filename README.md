<div> <body> <h1> <b> PORTFOLIO OPTIMIZATION USING PYTHON </b></h1>
   <img src = "https://miro.medium.com/max/720/1*8QpMpCoG48LOav6-o4MsTA.jpeg", width = "1000" </img>
  <h2> <b> DESCRIPTION </b></h2>
    <body> 
      <p>  Portfolio optimization is the process of selecting the best portfolio (asset distribution), out of the set of all portfolios being considered, according to some objective. The objective typically maximizes factors such as expected return, and minimizes costs like financial risk. Factors being considered may range from tangible (such as assets, liabilities, earnings or other fundamentals) to intangible (such as selective divestment). </p>
      <p> In investing, portfolio optimization is the task of selecting assets such that the return on investment is maximized while the risk is minimized. For example, an investor may be interested in selecting five stocks from a list of 20 to ensure they make the most money possible. Portfolio optimization methods, applied to private equity, can also help manage and diversify investments in private companies.</p>
      <h2> <b> OBJECTIVES </b></h2>
      <body>
        Our goal is build a portfolio containing multiple stocks with optimal weights. In this project, we assume that we want to invest $100,000 in the stocks in our portfolio. We want to be able to prescribe the number of stocks the investor should buy. 
      </body>
      <h2> <b> OUR APPROACH </b></h2>
      <body>
        <font size = "5">
 <li> First we import our one year of data for our stocks using pandas-datareader </li>
 <li> Generate 10,000 scenarios with random weighting to find our optimal portfolio using sharpe ratio and visualise it.</li>
 <li> We then build portfolio with our optimal weights and check its performance using performance metrics.</li>
 <li> We prescribe the number of stocks to purchase for each of stock in our portfolio
      </body>
        <h2> <b> BRIEF DESCRIPTION OF THE DATA </b></h2>
       <body>
         We get our data from Yahoo using the pandas-datareader library. We make use of the adjusted closing prices of each stock present in our portfolio in this project. You can check out the list of names of companies and their associated tickers in the notebook.
       </body>
