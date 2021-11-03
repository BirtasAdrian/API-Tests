# API-Tests

Below are some API test samples that I tested in my experience.

-----------------
## CRUD Tests
**Read**

Get single user by id.

**Parameters:**

* key: action and value: fetch_single represents the action to get a single user. 
* key: id and value: 19 represents the user id.

<img src="API-Test Images/CRUD tests 1.jpg">  

-----------------

**Insert**

Insert user by first name and last name.

**Parameters:**

* key: first_name and value: Adrian represents the first name. 
* key: last_name and value: Birtas represents the last name.

<img src="API-Test Images/CRUD tests 2.jpg">  

-----------------

**Update**

Updates a user's first or last name by id.

**Parameters:**

* key: id and value: 64 represents the persons's id in the database. The other parameters represent the name and the last name.

<img src="API-Test Images/CRUD tests 3.jpg" >  

-----------------

**Delete**

Delete a user by id.

**Parameters:**

* key: action and value: delete represents the action to delete a user by id. The other parameter is the user id.

<img src="API-Test Images/CRUD tests 4.jpg" >  

-----------------

## Weather Tests

API for searching weather forecast for 5 days with data every 3 hours by city name.

**Parameters:**

* key: q and value: Baia Mare represents the city
* key: appid represent your unique API key generate by https://openweathermap.org/ 
* key: units represent units of measurement, can take values: standard, metric and imperial 
* key: lang and the value: ro represents the language

<img src="API-Test Images/Weather tests.jpg" >  

-----------------


## News Tests

<img src="API-Test Images/News tests.jpg" >

-----------------

## OMDb API Tests

<img src="API-Test Images/OMDb API tests.jpg" >

-----------------
