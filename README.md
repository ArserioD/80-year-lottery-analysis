# 80-year-lottery-analysis

This project uses Python and Matplotlib to calculate and visualize the long-term probability of winning the lottery and the corresponding cumulative ticket cost over an 80-year period. The analysis showcases skills in probability, mathematical modeling, and data visualization.

Overview
Win Probability Calculation: The project calculates the cumulative probability of winning the lottery at least once when playing 104 draws per year (for 80 years). It uses the formula:

Cumulative Probability
= 1 − (1 − Single Draw Win Probability)^Total Draws

Total Ticket Cost Calculation: Based on a fixed ticket cost (for example, $2 per ticket), the total cost accumulated over all lottery draws is computed.

Data Visualization: Using Matplotlib, the results are plotted to show:

How the win probability increases over time

How the total ticket cost accumulates


## Assumptions
Lottery Draws: 104 draws per year (e.g., twice a week)

Duration: 80 years

Ticket Price: $2 per ticket

Win Probability: For instance, a single draw win probability might be 1 in 13,983,816

 Calculations:

The cumulative win probability is computed using the complement of losing all draws.

Total cost is simply the number of draws multiplied by the ticket cost.

## Code Walkthrough
The primary components of the project include:

Data Setup: Using NumPy to generate an array representing each year over the 80-year period and calculating the total number of draws.

Probability Computation: Calculating the cumulative win probability using the formula based on the probability of losing a single draw.

Cost Calculation: Multiplying the number of draws by the ticket price.

Visualization: Plotting two curves with Matplotlib:

The win probability curve (left y-axis)

The cumulative ticket cost (right y-axis)

## How to Run
Prerequisites:

Python 3

Required libraries: matplotlib, numpy Install them using pip if needed:

pip install matplotlib numpy

Run the Script: Save the code in a file (e.g., lottery_analysis.py) and run:

python lottery_analysis.py




