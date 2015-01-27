# Data Science CS109 HW2:Desperately Seeking Silver

In HW1, we explored how to make predictions (with uncertainties) about upcoming elections based on the Real Clear Politics poll. This assignment also focuses on election prediction, but we are going to implement and evaluate a number of more sophisticated forecasting techniques. 

We are going to focus on the 2012 Presidential election. Analysts like Nate Silver, Drew Linzer, and Sam Wang developed highly accurate models that correctly forecasted most or all of the election outcomes in each of the 50 states. We will explore how hard it is to recreate similarly successful models. The goals of this assignment are:

1. To practice data manipulation with Pandas
1. To develop intuition about the interplay of **precision**, **accuracy**, and **bias** when making predictions
1. To better understand how election forecasts are constructed

The data for our analysis will come from demographic and polling data. We will simulate building our model on October 2, 2012 -- approximately one month before the election. 

### Instructions

The questions in this assignment are numbered. The questions are also usually italicised, to help you find them in the flow of this notebook. At some points you will be asked to write functions to carry out certain tasks. Its worth reading a little ahead to see how the function whose body you will fill in will be used.

**This is a long homework. Please do not wait until the last minute to start it!**

The data for this homework can be found at [this link](https://www.dropbox.com/s/vng5x10b837ahnc/hw2_data.zip). Download it to the same folder where you are running this notebook, and uncompress it. You should find the following files there:

1. us-states.json
2. electoral_votes.csv
3. predictwise.csv
4. g12.csv
5. g08.csv
6. 2008results.csv
7. nat.csv
8. p04.csv
9. 2012results.csv
10. cleaned-state_data2012.csv
