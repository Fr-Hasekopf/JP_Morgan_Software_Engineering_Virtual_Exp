# JP_Morgan_Software_Engineering_Virtual_Exp

<p align="center">
  <img src="https://i.ibb.co/X503Pzw/1.png">
</p>
 
For this project, a trader from the equities team (publicly listed company stocks) has requested functionality be added to their dashboard to allow them to input specific information so they can monitor a new trading strategy.

In order to do this, we set up the system interface with the relevant financial data feed, make the required calculations and then present this in a way that allows the traders to visualize and analyze this data in real time.

The visualization of charts and data analysis our trader’s see is all built on JPMorgan Chase's own open sourced software called Perspective. 

##  Task Outline

<p align="center">
  <img src="https://i.ibb.co/4tjzhG2/2.png">
</p>

##  Task 1: Interface with a stock price data feed
This task includes:  
  
*__getDataPoint__ function should return correct tuple of stock name, bid_price, ask_price and price. 
*__getRatio__ function should return the ratio of the two stock prices  
*main function should output correct stock info, prices and ratio  
  
##  Task 2: Use JPMorgan Chase frameworks and tools - Open Source Tool Perspective
This task includes:  
*Fix the broken typescript files in repository to make the web application output correctly  
    
This ticket is done when the graph displayed in the client-side web application is a continuously updating line graph whose y axis is the stock’s top_ask_price and the x-axis is the timestamp of the stock. The continuous updates to the graph should be the result of continuous requests and responses to and from the server for the stock data.  
  
This ticket is done when the graph is also able to aggregate duplicated data retrieved from the server.  

<p align="center">
  <img src="https://i.ibb.co/gwZpmsL/3.png">
</p> 
  
##  Task 3: Display data visually for traders
This ticket is done when the numbers from the python script render properly in the live perspective graph. This means the ratio between the two stock prices is tracked and displayed. The upper and lower bounds must be shown on the graph too. And finally, alerts are shown whenever these bounds are crossed by the ratio.  
  
<p align="center">
  <img src="https://i.ibb.co/vD8Lfzx/4.png">
</p>