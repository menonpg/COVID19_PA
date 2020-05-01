# Modeling-ready COVID19 time-series for PA, by county 
Datasets on time-series evolution of COVID19 cases and deaths in Pennsylvania (PA), by county.  

# Download data into Python, as follows:
- `import pandas as pd`
- `PA_County_Deaths = pd.read_csv('https://raw.githubusercontent.com/menonpg/COVID19_PA/master/timeSeries_COVID19_Cases_PACounties.csv')`
- `PA_County_Cases = pd.read_csv('https://raw.githubusercontent.com/menonpg/COVID19_PA/master/timeSeries_COVID19_Deaths_PACounties.csv')`
- `PA_County_NegativeTests = pd.read_csv('https://raw.githubusercontent.com/menonpg/COVID19_PA/master/timeSeries_COVID19_NegativeTests_PACounties.csv')`
- Consider adding the `, engine='python')` or `, encoding="cp1252")` arguments to the pd.read.csv function in the event of utf-8 related errors 

Also see: https://quantmd.shinyapps.io/visualizeCorona/ ; A COVID19 tracker app mashes datasets from a few different sources, allows interactive pairwise comparison of trends from different countries, etc..  

Email me at prahlad.menon@quant.md to be subscribed to my automated daily email bot summarizing stats and WHO situation reports for your country and state (if in the US).  


#covid19news #covid19us #coronavirus
