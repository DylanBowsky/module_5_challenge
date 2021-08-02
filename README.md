# 5_module_challenge
# Portfolio Analysist 
The goal for this financial notebook is to create a sophisticated simulation with our financial investments. This will help to make sure we have enough for emergencies as well to see the height of our potential portfolio after a number of years with a certain stock and bond allocation. In this notebook we used a ten year aggressive plan along with a steady 30 year plan to see the difference.
-------------------------------------------------------------------------------------------------------------------------

# Technologies Used
We used Jupyter notebook, .env, api's, plot simulation, and Monte Carlo simulation for forcasting.  
-------------------------------------------------------------------------------------------------------------------------

# Installation
We will need Pandas, load_dotenv, request, json, alpaca api, numpy, and matplotlib, and Path from pathlib. An optional install could be seaborn for heat maps and different variety of graphs.
-------------------------------------------------------------------------------------------------------------------------

# Example
We use our api key to get our digital wallet and see the allocation of crpto and our investment account(stock and bonds), we then have the amount of risk we want to tollerate by selecting our allocation of stocks and bonds, and we can select the amount of years we want to be in the market. After we have the allocation and timeframe we create our forecasting simulation with monte carlo we then can see the summary which will give us our upper and lower confidence levels. We can give this to our client as a basis for them to show the difference of what each variable(time, amount, allocation) will do and see the most optimal.
-------------------------------------------------------------------------------------------------------------------------