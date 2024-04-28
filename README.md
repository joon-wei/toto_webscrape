# Toto results webscraper
This script scrapes a website for the past 10 winning draws of Toto and prints it into a csv file, which can be used for importing into a model, in excel or such, and be further analysed. The excel comes with macros to easily import the csv into an empty sheet and append the results to the main table, which analyses the frequency of the winning numbers. You can modify the excel sheet to do your own analysis!

Why did I make this script? Mainly because it saves me about 10 seconds of manually adding new winning numbers into my excel table.

By default, the script generates the csv into the same directory which the script is located in.<br />

## Background
Toto is a legalised form of lottery where participants purchase a set of six numbers selected from 1 to 49. Any matching 3 or more numbers with the winning set nets a prize, with the jackpot prize being a full correct matching set of 6 numbers. 

There are multiple forms of tickets available for purchase, including an ordinary ticket with 6 numbers, or "System" 7 - 12 tickets, which allows 7 - 12 selection of numbers in a single ticket respectively. 

At it's core, the lottery is simply a game of statistics. The number of combinations of numbers covered in a "System" ticket drastically increases, increasing your probability to win. However, the price of such tickets also drastically increase, and many who do the math will realise it is still a stupendously small probability of winning the jackpot. 

## Winning methodology?
Just like in investing, there are statistics models which analyse historical data to predict future outcomes. By simply gathering the historical data of winning numbers, we can apply two methods to predict winning numbers; Monte Carlo principal where the numbers with the highest frequency will be likely to come out, and the Law of Large numbers where every number will come out an equal number of times given enough toto draws, and numbers with the lowest frequency will come out sooner rather than later.

Of course, assuming the draws are truly random, no amount of historical analysis will increase my chances of winning. This is mainly a experiment to see if the statistical principals actually have weight to them, while netting me a sweet pot at the same time. 

Based on actual studies, I read online that the best way to win is to pick the lowest picked, unpopular numbers such as percieved "unlucky" numbers like '13'. The study shows that popular, "luckier" numbers such as '7' are picked more by the population, and assumming every ticket has an equal probabiltiy of winning, it is better to choose a number set which is less picked by the population to reduce the chances of sharing the pot, thus increasing your overall intrinsic value of your ticket purchase.

In the future I may dive into more analysis between the winning numbers; intervals between winning numbers, correlation of winning numbers etc... There are many things you can choose to investigate, who knows you may actually find a winning pattern one day!
