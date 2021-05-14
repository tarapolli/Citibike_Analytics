
Assignment:  Analyze the NYC Citibike Program using any datasets provided, then create a dashboard to provide questions and answers for city officials. 
Process:  After downloading the datasets that I wanted to analyze (May – July 2020), the next step was to clean the data. I started to do so in Pandas.  But without visualizing the anomalies yet (in Tableau), I decided to create a union (in Tableau) so I could visualize it before eliminating any data that may identify trends, anomalies, etc.

Focus and study questions:   New York City was greatly affected at the onset of the COVID-19 pandemic, so I wanted to look for trends such as:
Did tourism come to a halt?  (I hypothesized that tourists should be classified as ‘customer’ user types where they rent bikes for 1-3 days, whereas local New Yorkers should be classified as ‘subscriber’ user types by holding an annual pass)
Did New Yorkers stop using the bikes for fear of the virus being on the handlebar surface, for example?
When are the busiest days of week and hours of day by user type?
What and where are the top 10 stations in the city for starting a journey?
What  and where are the top 10 stations for ending a journey?
What are the bottom 10 stations for starting a journey?
What are the bottom 10 stations for ending a journey?

Analysis:  The summer months of May, June, and July would typically see an uptick in Customer ridership due to favorable weather and school not in session.  This is true according to Subscribers but not Customers.  Confirmed by the Daily News, more New Yorkers purchased an annual subscription so they could ride bikes in open air as opposed to the subways.  Tourism virtually halted, so the rate of 1-3 day trips by Customers slowed down. Brief research of the May-July  2019 data confirms. 
 According to the Daily News on December 1, 2020, “New Yorkers ditched the subway for good old-fashioned pedal power this summer, cycling a near-record number of times across the East River bridges as the COVID-19 pandemic scared people away from crowded mass transit. More than 25,000 cyclists crossed the city’s four East River bridges on an average weekday from July through October, according to data from the city Department of Transportation. That’s up by some 4,300 daily cyclists — or 21% — from the same period of 2019. October saw the biggest gains in biking, with 25,537 cyclists crossing the bridges, 30% more than last year. The bike boomed happened as subway ridership fell to just 25% of what it was before  the pandemic. Ridership has since rebounded to roughly 32% of pre-pandemic levels.” https://www.nydailynews.com/new-york/ny-nyc-cycling-bike-counts-east-river-bridges-20201201-qbqdfh2hs5bfxf7p7b53okrnsi-story.html

Furthermore, the busiest hours of the day peak around 5:00pm; a typical commuting hour. The busiest days of the week for both Customers and Subscribers are Saturday and Sundays. Since tourism was virtually halted because non-residents were restricted from entering the state, it is possible that non-subscribing New Yorkers were using bikes on weekends to do their errands.

Phenomena:  Bottom 10 Start Stations:  none in May.  You will notice the lack of data in the “Bottom 10 Stations:  Start Point” bar graph.  There is no data for May. If you look at the end point for these bottom ten stations, many of them are located in Jersey City. Very few trips begin in the state of New York and end in the state of New Jersey, especially due to the state restrictions during the pandemic.  Also note that the June and July end stations have only 1 listed! You may filter station names on this dashboard to confirm.




