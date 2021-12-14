## Data Visualization Final Project: Coffee Trades

Coffee is an important beverage commodity. Many economies, particularly developing economies, are heavily dependent on coffee trade. Major coffee producing countries are developing countries in Southeast/South Asia, Africa, and Latin America. While coffee being a popular, and sometimes pricy beverage, many coffee farmers live in poverty or extreme poverty. 

Fair trade coffee was introduced with the intention of maintaining sustainability and transparency, as well as improving farmers’ living conditions. However, these years, fair trade coffee has been criticized for its “strict requirements [which] are resulting in uneven economic advantages for coffee growers and lower quality coffee for consumers” as discussed in “The Problem With Fair Trade Coffee” by Haight in Stanford Social Innovation Review .   

This project is inspired by the discussion on fair trade coffee and a sustainability project in my alma mater. We will extract insights from the data and visualization to understand more about coffee trade. 

Due to the limitations of the dataset, 9 countries, which are major coffee producers and exporters, are included in the project: Brazil, Dominican Republic, Colombia, El Salvador, Ethiopia, Guatemala, Honduras, India, and Uganda. 

### Domestic Consumption Versus Export

<iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~fw215/4.embed"></iframe>

This scatterplot shows domestic consumption versus export measured in thousand 60-kg bags over time. The size of the bubble is determined by the production amount. 

Brazil is a significant outlier, as its domestic consumption, export and productions have been significantly greater than other countries. It is not difficult to observe that Brazil experienced fluctuations in exports and production but the general trend for domestic consumption is upward. 

We can hide Brazil and re-scale the plot to observe patterns and trends for other countries. Guatemala had an upward trend for domestic consumption, while Colombia had an increasing trend for exports. Other countries experienced fluctuations but generally had an upward trend on production and either export or domestic consumption, except for El Salvador and Dominican Republic. 

### Domestic Consumption, Production And Export Over Time

- Domestic Consumption
<iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~fw215/14.embed"></iframe>

- Production
<iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~fw215/17.embed"></iframe>

- Export  
<iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~fw215/22.embed"></iframe>

We can observe volatilities in production and exports, while domestic consumption has a general trend and is steadier for most of the countries included in the project. 

The graph for production amount shows significant volatilities. Since Brazil has higher number in everything, including it in the graph would make it difficult to observe patterns for other countries; therefore, if we hide Brazil, we could see the similar fluctuating patterns for other countries. 

### Prices Paid to Growers Over Time with Retail Price as the Comparison

<iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~fw215/6.embed"></iframe>

Prices paid to farmers dropped significantly starting 1998 and went back up in 2008. The prices for farmers peaked in 2011 across all countries as the commodity price reached its peak in 2011 . The trend for this decade was similar across all countries. If we look at the retail price, we can also observe the similar trend. But still, we can see the gap between the retail price and the price paid to farmers. Although farmers have been gradually paid more, we know they are still not fairly compensated for their working conditions and risks they take. 

### Horizontal Comparison of Prices Paid to Growers 

<iframe width="900" height="800" frameborder="0" scrolling="no" src="//plotly.com/~fw215/19.embed"></iframe>

It’s interesting to see Dominican Republic, despite having relatively low production and exports, has been paying farmers more than its peer countries have been in the past 5 years. Similar trend can apply to Guatemala too. Though Brazil is the largest coffee producer and exporter in the world, the farmers are paid less than its peers. After the peak, farmers are only paid half of the amount paid in Dominican Republic. 
