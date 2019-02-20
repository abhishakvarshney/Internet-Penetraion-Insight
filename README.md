Total no. of rows and columns:  (267, 7)


Internet Penetration Rate (P.R.) is the number of Internet users divided by the population, and expressed in percentage

Population" column is average number of people, living in the country or region. 

The last column is defined as the date for Internet users data, month and year

"NaN" means that the information is not available


From the data we can see that there are total 267 countries or region.
Here we can see that Japan is having highest Internet Penetration rate in Dec 2013 which means Japanese people use more internet as compared to their population ratio than any other country people compare to their population ratio. 

The amount of data which is missing in this text is presented below:

0
Country or Region Name         0
Sym -bol                   		1
Size (sq. km.)             		3
Population (2018 est.)  	5
Internet Users            		12
Internet Penetration      	12
Data date                  		0
dtype: int64

Now, This is the type of columns.object is basically the default way of storing string data types in python.

0
Country or Region Name     	object
Sym -bol                   		object
Size (sq. km.)           		float64
Population (2018 est.)    	float64
Internet Users            		float64
Internet Penetration      	float64
Data date                  		object
dtype: object

Now I scaled the data to make all values of columns to make each columns into same scale so that i can visualize different features of the data in more effective way.

![internet_user_size_per_ sq km](https://user-images.githubusercontent.com/35887568/53115195-95a67e00-356b-11e9-88c1-ce7518d02c2c.png)

It is clearly visible that the internet_user is increasing as increasing size of the area.

![internet_penetration_size_per_ sq km](https://user-images.githubusercontent.com/35887568/53115187-93442400-356b-11e9-943a-8507766544ff.png)

Well internet penetration is increasing as size increasing but it is not increasing linearly.majority of the internet penetration is not increasing constantly with the size of the area.

![population_size_per_ sq km](https://user-images.githubusercontent.com/35887568/53115204-9a6b3200-356b-11e9-82d3-8193bfe583da.png)

It is clearly visible that population of country is dependent on the size of the area.

![population_internet_users](https://user-images.githubusercontent.com/35887568/53115197-98a16e80-356b-11e9-8ab0-302c66a53ac4.png)

It is also seen from this graph is internet users is increasing as per the population.So if any software company want to establish any project so it is better to target to those country where the population is high and it is also a good idea to start where the area of the country is large because population and size of the country is also dependent.

Conclusion:
Here we can see that Japan is having highest Internet Penetration rate in Dec 2013 which means Japanese people use more internet as compared to their population ratio than any other country people compare to their population ratio.
