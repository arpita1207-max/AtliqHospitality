```
Bussiness Problem 
1.AtliQ is a company that owns multiple hotel chains across various cities of India

2.The Managing director / CEO of AtliQ wants to incorporate ‘Business and Data Intelligence’ to identify
and track the source of revenue for AtliQ hotels

3.Hence, it is decided to develop a KPI Dashboard for AtliQ, using May-22 to July-22 data, which can help
track its revenue sources and other relevant KPIs across various dimensions

4.It’ll help the management take strategic business decisions based on the insights generated from the
dashboard
```

```
Solution Approach
There are 3 dimension tables: rooms, hotels, date and 2 fact tables: bookings, aggregated_bookings.
Power BI is used as the visualization tool in this project.
The data is imported, analyzed, and transformed in the SQL Server and Power BI.
The relationships between the tables have been created in SQL Server and Power Pivot.
```

```
Solution Approch
I have create few measures for the KPI:-
Measures	                            Description / Purpose
Revenue	                              To get the total revenue_realized
Total Bookings	                      To get the total number of bookings happened
Total Capacity	                      To get the total capacity of rooms present in hotels
Total Succesful Bookings	            To get the total succesful bookings happened for all hotels
Occupancy %	                          Occupancy means total successful bookings happened to the 
                                      total rooms available(capacity)Occupancy means total successful bookings happened to the 
                                      total rooms available(capacity)
Average Rating	                      Get the average ratings given by the customers
No of days	                          To get the total number of days present in the data.
                                      In our case, we have data from May to July. So 92 days.To get the total number of days present in the data.

Total cancelled bookings	            To get the"Cancelled" bookings out of all Total bookings happened
Cancellation %	                      calculating the cancellaton percentage.
Total Checked Out	                    To get the successful 'Checked out' bookings out of all Total bookings happened
Total no show bookings	              To get the"No Show" bookings out of all Total bookings happened 
                                      ("No show" means those customers who neither cancelled nor attend to their booked rooms)To get the"No Show" bookings out of all Total bookings 
                                      happened.("No show" means those customers who neither cancelled nor attend to their booked rooms)
No Show rate %	                      calculating the no show percentage.
Booking % by Platform	                To show the percentage contribution of each booking platform for bookings in hotels.
                                      We have booking platforms like makeyourtrip, logtrip, tripster etc)To show the percentage contribution of each booking platform for bookings in 
                                      hotels.

Booking % by Room class	              To show the percentage contribution of each room class
                                      over total rooms booked.We have room classes like Standard, Elite, Premium, Presidential.To show the percentage contribution of each room class
                                      over total rooms booked.We have room classes like Standard, Elite, Premium, Presidential.

ADR 	                                Calculate the ADR(Average Daily rate).It is the ratio of revenue to the total rooms booked/sold. It is the measure of the average paid for rooms 
                                      sold in a given time period.

Realisation %	                        Calculate  the realisation percentage.It is nothing but the succesful "checked out" percentage over all bookings happened.


RevPAR	                              Calculate the RevPAR(Revenue Per Available Room)
                                      RevPAR represents the revenue generated per available room, whether or not they are occupied. RevPAR helps hotels measure their revenue 
                                      generating performance to accurately price rooms. RevPAR can help hotels measure themselves against other properties or brands.

DBRN	                                calculate DBRN(Daily Booked Room Nights).This metrics tells on average how many rooms are booked for a day considering a time period


Realisation %	                        calculate DSRN(Daily Sellable Room Nights).This metrics tells on average how many rooms are ready to sell for a day considering a time period


DURN	                                calculate DURN(Daily Utilized Room Nights).This metric tells on average how many rooms are succesfully utilized by customers for a day considering a time period




AtliqHospitality Report
````
```Semantic Model ```



````
````

````
````

````
Metrics Performance OverTime
````


```
Bussiness Insights




```
