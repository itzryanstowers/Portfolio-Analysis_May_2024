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
 3. After exploring the data and making a few changes, it is now time to choose a few stocks and perform some technical analysis to compare with the S&P 500.
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

Utilizes various technical analysis techniques to evaluate potential investments.
Optimizes portfolio construction to target performance that matches or outperforms the S&P 500.
Target Audience:

This project is intended for individuals seeking investment guidance and portfolio management assistance from wealth planners or financial institutions like BlackRock and Fidelity.

Technical Stack:

Python
Libraries: pandas, numpy, datetime, pathlib, matplotlib.pyplot, seaborn
Running the Project (Current Stage):

Currently, the project operates in a fully automated fashion within a Python environment.  There's no manual interaction required at this stage.

Future Development:

The next step involves developing a user-friendly application (planned to use Streamlit) for interacting with the project's functionalities.

Output (To Be Defined):

The final application's output will be determined during the development phase. It's likely to include visualizations, performance metrics, and actionable recommendations.

Development Notes:

Feel free to include a brief description of your development process or the challenges you encountered.

Additional Resources:

Consider adding any relevant links to libraries or technical analysis concepts used in the project.

License:

(Optional) If you have a specific license associated with your project, mention it here.

Contribution:

(Optional)  If you plan to allow others to contribute, outline your contribution guidelines.
