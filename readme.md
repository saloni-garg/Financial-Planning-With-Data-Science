## Case Study:
You just got a new job as an entry-level Data Scientist at a technology company in New York City with a decent starting salary of $85,000 per year.

Unfortunately, after state and local taxes, you can expect to be sending roughly 30% back to the government each year.

You will need to calculate your monthly take home pay after taxes in order to begin budgeting.

## Monthly Expenses and Savings

In order to make it in New York City, you have decided to split a two-bedroom apartment with a friend. You will have to budget for rent, food and entertainment, but it's also a good idea to allocate an amount for unforeseen expenses each month. This unforeseen expenses budget could be used for anything ranging from new clothes or electronics to doctor appointments.

### Set up the monthly budget as follows:

- Rent: $1200 / month (Includes utilities)
- Food: $30 / day (On average. Includes groceries and eating out.)
- Entertainment: $200 / month (Movies, drinks, museums, parties...)
- Unforeseen Expenses: 250 / month (Stay safe, and don't drop your phone!)
For this application, assume an average of 30 days per month. Whatever is left after your paying your monthly expenses will go into your savings account each month.

## Forecast Salary Growth and Cost of Living
Due to both inflation and increased productivity from experience, you can expect your salary to grow at different rates depending on your job. Now, since you are working in a growing and in-demand career field as a Data Scientist, you can assume a steady growth in your annual salary every year based on performance.

You can assume an annual salary growth rate of 5%, which means if you start at $85,000 per year, you can expect to earn over $176,000 per year after 15 years. After taxes, assuming your tax rate hasn't changed, that works out to roughly $125,000 per year, which is not unreasonable for a Data Scientist. In fact, you might even make it to that level in a few years! But just to be safe, you should be conservative with your projections.

For this application, assume all inflation and salary growth happens in smaller increments on a monthly basis instead of just one large increase at the end of each year.

# Calculating One's Net Worth
For this example, all you need to do is subtract your forecasted monthly expenses from your forecasted monthly salary. The remaining cash flow will go straight into your savings account for each month.

You want to project your cumulative savings over time to see how effective your budgeting process will be given your projections.

## How much more to Be a Millionaire?
Your projections show that you can accumulate over $700,000 in just 15 years by following a strict budget and growing your salary steadily over time.

But you want to be a millionaire in 15 years, retire young, sip margaritas and travel for the rest of your life. In order to do that, you're going to need to invest.

Remember the .pmt() function from numpy? You can use this function to calculate how much you need to save each month in order to accumulate your desired wealth over time.
ś
You still have a lot to learn about the stock market, but your financial advisor told you that you can earn anywhere from 5-10% per year on your capital on average by investing in a low cost index fund.

You know that the stock market doesn't always go up, but you will assume a modest 7% return per year, which has been the average annual return in the US stock market from 1950-2009.

The forecast_months variable from the previous exercise is available.

## Investing a Percentage of Income
Unfortunately, you really can't afford to save $3,000 per month in order to amass $1,000,000 after only 15 years.

But what you can do is start slowly, investing a small percentage of your take-home income each month, which should grow over time as your income grows as well.

In this exercise, you will lay the foundations to simulate this investing process over time.

The salary_forecast and expenses_forecast variables are available from the previous exercise.

The cash_flow_forecast is also available, and is an array of your forecasted salary minus your forecasted expenses. The monthly_investment_percentage variable is already set to 0.30.