## Overview of the Analysis

The purpose of this analysis was to take the provided dataset of over 34,000 organizations that have received funding from Alphabet Soup and create a tool that would help select applicants for success in their future ventures.

Results:
    - Data Processing
        - Target Variables - In this analysis we target the column of previous successful campaigns and focused our tool on if a previous campaign was successful or not.
        - Feature Variables - We used the rest of the columns of the data set after filtering out the successful or not successful columns.
        - Removed Variables - We removed the EIN and Name columns from the dataset before we did any processing of the data.
    - Compiling, Training and Evaluating
        - My first attempt I used 2 hidden layers of 80 and 35. These were provided by our instructor as a good starting point.
        - Achieve Target Performance - No, I was not able to successfully achieve the 75% benchmark that was asked for on this project.
        - Steps to increase Performance - I tried to optimize the results by running it through a loop testing various different neurons and layer variables almost 500 times. During this loop, it failed to achieve above 75%.

Summary:

Overall, not achieveing the 75% goal of this tool, I would consider that we would need to perhaps do more data cleanup before we start to train our data and run our analysis. I would suggest filting more of the columns of data so we did not have 40+ columns of data and perhaps had around 30+ with less variables. I believe if we started with this, we would get a much better result and that would have achieved our goal of 75% or above.

