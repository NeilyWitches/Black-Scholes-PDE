# Black-Scholes-PDE

Before creating this function, I created a function which takes in a csv file from NASDAQ containing the stock prices of a stock at market close for each day for a 6 month period. The function spits out the price of a vanilla call option for each stock price and date by applying the Black Scholes formula, i.e. the solution to the Black Scholes patial differential equation. This function does the same exact thing, but instead of using the formula, it solves the Black Scholes PDE directly using the method of finite differences.
