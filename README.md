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


DURN	                                calculate DURN(Daily Utilized Room Nights).This metric tells on average how many rooms are succesfully utilized by customers for a day 
                                      considering a time period.

```
```REVENUE```

![revenue](https://github.com/user-attachments/assets/0a3779b9-38fe-4810-9c00-5ac92657bee4)

```TOTAL BOOKINGS ```

![TOTAL_BOOKINGS](https://github.com/user-attachments/assets/3830c63f-ce2c-4a36-8b3c-63bbee4516fe)


```TOTAL CAPACITY ```

![TOTAL_CAPACITY](https://github.com/user-attachments/assets/ebe5d8a5-2b4a-43f3-9a66-666dfb7868d6)


```TOTAL SUCCESSFUL BOOKINGS```

![TOTAL_SUCCESSFUL_BOOKINGS](https://github.com/user-attachments/assets/2d39d7f3-2e6f-4f69-93ea-0c0e8ac4bd3b)

```OCCUPANCY % ```

![OCCUPANCY_PERCENT](https://github.com/user-attachments/assets/7f42d100-27d3-4186-9fc0-4125ef1ad32c)


```AVERAGE RATING ```

![AVERAGE_RATING](https://github.com/user-attachments/assets/9dc98933-ea29-478f-b355-f54d857e1f30)


```NO OF DAYS```

![NO_OF_DAYS](https://github.com/user-attachments/assets/d050ce4c-5046-4c02-ab12-f1f9006a48b1)


```TOTAL CANCELLED BOOKINGS ```

![TOTAL_CANCELLED_BOOKINGS](https://github.com/user-attachments/assets/81a1c5dc-0ad0-4948-a637-775db124a69e)

```CANCELLATION % ```

![CANCELLATION_PERCENT](https://github.com/user-attachments/assets/3424f788-33ac-40c1-a4e5-5f3ba21aece3)


```TOTAL CHECKED OUT ```

![TOTAL_CHECKED_OUT](https://github.com/user-attachments/assets/b0cd0d71-0bf0-4f20-861d-47f291d455d2)

```TOTAL NO SHOW BOOKINGS```

![TOTAL NO SHOW BOOKINGS](https://github.com/user-attachments/assets/6e0b923f-cde1-4acd-b2dd-0b035a95ef15)


```NO SHOW RATE %```

![NO_SHOW_PERCENT](https://github.com/user-attachments/assets/dacb42b0-279e-445b-a04d-13e548888b4e)


``` BOOKING PERCENT BY ROOM CLASS ```

![BOOKING PERCENT BY ROOM CLASS](https://github.com/user-attachments/assets/02d608d6-8052-4388-b9b0-dd0ef32fefc9)

``` BOOKING PERCENT BY PLATFORM ```

![BOOKING PERCENT BY PLATFORM](https://github.com/user-attachments/assets/758ee279-5795-4f99-aa9c-3d02741eccb2)


``` ADR ```

![ADR](https://github.com/user-attachments/assets/4e7b405d-8007-4528-b29c-6bdb572a53bd)



``` REVPAR ```

![REVPAR](https://github.com/user-attachments/assets/76e61f13-af69-4b06-8d1d-2f967f3f56c0)

``` REALIZATION_PERCENT ```

![REALIZATION_PERCENT](https://github.com/user-attachments/assets/aa2ac00e-bd20-43da-98ae-2cd1fb0bd44b)


``` DBRN ```

![DBRN](https://github.com/user-attachments/assets/4c8e3e18-bccf-4df7-adbd-aa78b22b5fae)

``` DSRN```

![DSRN](https://github.com/user-attachments/assets/3ae9fa77-e40e-4e43-9b1f-361b60c5130e)

``` DURN ```

![DURN](https://github.com/user-attachments/assets/45135358-be49-4c38-960a-5d8130991997)

```OCCUPANCY WOW CHANGE %```

![OCCUPANCY WOW CHANGE %](https://github.com/user-attachments/assets/8d87ec7f-e13a-4ecf-877f-f75b49e2f0a3)

```REVENUE WOW CHANGE % ```

![REVENUE WOW CHANGE %](https://github.com/user-attachments/assets/a848685b-fb95-4a91-8355-e224673d67d6)

``` REVPAR WOW CHANGE % ```

![REVPAR WOW CHANGE %](https://github.com/user-attachments/assets/34d42ef4-187c-4a30-9c8a-8cd76e61c6f7)

``` REALIZATION WOW CHANGE % ```

![REALIZATION WOW CHANGE %](https://github.com/user-attachments/assets/a3ee693d-da57-4b33-9db9-875deeec5423)

``` [ADR WOW CHANGE % ```

![ADR WOW CHANGE %](https://github.com/user-attachments/assets/5d8a86b0-5bc4-4a7f-ad2b-a43540d29d69)






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
