# Portfolio-Analysis

This project aims to identify stocks and funds for building an investment portfolio using technical analysis such as Sharpe Ratio, Cumulative properties and other fundamentals.
The goal is to aim to build a portfolio that will compete with the returns of the S&P 500.

### Chapter Features:
 Here are a list of sections within the project
  *  Gather Data from various sources (Yahoo Finance, Excel)
  *  Exploratory Data Analysis using pandas library
  *  Technical Analysis techniques and visuals applied
  *  Choosing the preferred stocks and index funds to build a custom Portfolio
  *  Compare the custom portfolio with the S&P 500.
### Data Gathering & Exploration
 Before getting started, we need to acquire the data and explore it in order to move forward to perform some technical analysis. The following steps in gathering and exploring are as follows:
 1. Performing pandas function "read_csv" to read the data sets together.
 2. Using more pandas functions to explore the data such as pd.head, pd.info, pd.isnull, etc.
 3. Using box plots and line charts to get a picture of how each stock is doing within the duration of the dataeset captured.
 4. After exploring the data and making a few changes, it is now time to choose a few stocks and perform some technical analysis to compare with the S&P 500.
### Technical Analysis
 This is part of the project that will cover a wealth amount of analysis to decide which stocks will belong in the custom portfolio to compete with the S&P 500.
 Some of the techniques we use are as follows:
 - Standard Deviation: Measures how spread out the data is from its average. A high standard deviation means data points are further from the average, while a low standard deviation indicates data points are closer to the average.
 - Correlation: Indicates the relationship between two data sets. A positive correlation means they tend to move in the same direction (up and down together). A negative correlation means they move in opposite directions (one goes up, the other goes down). When the datasets show no relationship, that indicates a zero correlation.
 - Rolling Standard Deviation: Rolling Standard deviation is the same as standard deviation but it is calculated over a specific window of data points instead of the entire dataset. For instance, a window of 14 days is the amount of time the std would calculate over that specific period. This helps identify how volatility changes over time.
 - Covariance: Covariance or (cov) Measures how two variables change together, but it doesn't consider direction (positive or negative) like correlation. A positive covariance move in the same direction, while a negative covariance move opposite from each other.
 - Variance: Similar to standard deviation, but squared. It represents the average of the squared deviations from the mean.
 - Beta: Measures how much a specific investment moves relative to a benchmark (like the S&P 500). A beta of 1 means the investment moves exactly like the benchmark. A beta greater than 1 means it tends to be more volatile than the benchmark. A beta less than 1 means it's less volatile.
 - Rolling Statistics: Any statistical calculation (like standard deviation, mean) performed on a window or period of data points that's moved forward over time. This helps analyze how the statistics changes throughout the data.
 - Sharpe Ratio:  Measures the risk-adjusted return of an investment. It considers both the average return and the volatility (standard deviation) of the returns. A higher Sharpe Ratio indicates better risk-adjusted performance.
We will be using visuals to view the pictures of most of the technical analysis to get a better picture of which stock is performing better than others that can be included in the portfolio. 
### Custom Portfolio
Now that we have performed some technical analysis on the various stock options, we can now put together a portfolio that we believe will match or even outperform the S&P 500.
Remeber the goal is to build a customized portfolio that aims to match or outperform the S&P 500's performance. By incorporating these technical analysis signals, the project seeks to exploit potential price movements and select assets with strong growth prospects. The specific technical indicators used and the selection criteria are detailed within the code itself.
### Construct and Evaluate 
Now that we've constructed the customr portfolio, its now time to evaluate the portfolio with the S & P 500. Using the indicators that was aimed to capture potential price movements and growth prospects of the custom portfolio, the portfolio's performance is continuously monitored and compared against the S&P 500 to assess its effectiveness in achieving the goal of matching or exceeding the benchmark's return.
### Potential Developments:
Now that we have selected our custom portfolio, we can move over to another step that involves developing a user-friendly application (planned to use Streamlit) for interacting with the project's functionalities.
This application will allow customers to see how each custom portfolio performs against the S&P 500 based on a couple questions they would answer to determine their risk tolerance (growth-oriented, income-focused, risk-averse) and receive tailored portfolio suggestions based on their preferences. This app will be determined during the development phase. It's likely to include visualizations, performance metrics, and actionable recommendations.

