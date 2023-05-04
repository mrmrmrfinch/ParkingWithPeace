# 🚗 Parking With Peace

**Project in progress. Help Appreciated!**

Have you ever gotten a parking ticket when parking on campus? On top of already expensive tuition, most universities enforce strict regulations around parking. Each ticket can cost anywhere between $15 to $60, and if you don't pay it on time, the price can double, triple; one day you may even find your car being wheellocked.

You may not believe this, but parking tickets are a huge source of revenue for universities. As an example, Montclair State University made over $1 million just in parking tickets from the last three years (See [News](https://themontclarion.org/news/montclair-state-university-made-over-1-million-in-parking-tickets-in-the-last-three-years/)). That's a lot of money! As a result, many students have to pay hundreds, even thousands of dollars in parking tickets each year. 

Parking with Peace attempts to solve this problem.

## How it works
We start by building an interactive website for everyone to log where and when they received a parking ticket. Anyone can log a ticket, and at the same time, see the tickets logged by others. We aim to provide a "trend map" that allows you to visualize where and when tickets have been given out in the past days.

It doesn't stop here. We believe in the power of crowd-sourcing, not just on the data collection end, but also the analyzation end. To this front, we plan to release the logged data regularly in CSV format as part of a Kaggle Challenge. The key question we want to answer is: **What's the probability heatmap for getting a ticket, at a certain time range in a given day?**. We hope that by answering this question, we can help students avoid getting tickets, and save them money.

Once we 1) collect enough data, and 2) have an accurate-enough model to predict, we expect students to be able to input the time range they plan to park, and get a probability heatmap of the entire campus for getting a parking ticket, thereby deciding whether or not to buy a one-day pass.

## Potential Issues
- **Privacy**: We understand that some people may be concerned about privacy. We will not be collecting license plate numbers, and we will not be collecting any personal information. The only information we collect is the time range and location. We will also be releasing the data in CSV format, so that anyone can download and analyze the data themselves. The process is entirely transparent.

- **Attacks**: Since anyone can log data, it is possible for a malicious user to log fake data. We see this as a data analyzation problem, and we will be working on ways to detect and remove fake data. However, we don't see "downvoting" tickets or removing information arbitarily as a long-term solution. Any suggestions are welcome.