# API-Tests

Below are some API test samples that I tested from my experience.   
 
-----------------
## CRUD Tests 
**Read**

Get single user by id.

Method used: GET

**Parameters:**

* key: **action** and value: **fetch_single** represents the action to get a single user 
* key: **id** and value: **19** represents the user id

<img src="API-Test Images/CRUD tests 1.jpg">  

-----------------

**Insert**

Insert user by first name and last name.

Method used: POST

**Parameters:**

* key: **first_name** and value: **Adrian** represents the first name 
* key: **last_name** and value: **Birtas** represents the last name

<img src="API-Test Images/CRUD tests 2.jpg">  

-----------------

**Update**

Update a user's first or last name by id.

Method used: PUT

**Parameters:**

* key: **id** and value: **417** represents the persons's id in the database. The other parameters represent the name and the last name

* Note: Here we have a bug, the response is [{"success":"0"}] not [{"success":"1"}] as in the documentation and status code is 200 OK for this

![Update](https://user-images.githubusercontent.com/90641668/214389497-c42b36eb-9bc5-4dcd-a9cb-628aac7694b6.jpg)


-----------------

**Delete**

Delete a user by id.

Method used: DELETE

**Parameters:**

* key: **action** and value: **delete** represents the action to delete a user by id. The other parameter is the user id

<img src="API-Test Images/CRUD tests 4.jpg" >  

-----------------

## Weather Tests

API for searching weather forecast for 5 days with data every 3 hours by city name.

**Parameters:**

* key: **q** and value: **Baia Mare** represents the city
* key: **appid** represents your unique API key generate by https://openweathermap.org/ 
* key: **units** represents units of measurement, can take values: **standard, metric or imperial** 
* key: **lang** and the value: **ro** represents the language

<img src="API-Test Images/Weather tests.jpg" >  

-----------------

## News Tests

API for searching live articles from all over the web.

**Parameters:**

* key: **apiKey** represents your unique API key generate by https://newsapi.org 
* key: **q** and value: **Samsung** represents the keyword to search for in the article title and body 
* key: **language** and value: **en** represents the language 
* key: **pageSize** and value : **10** represents the number of results to return per page

<img src="API-Test Images/News tests.jpg" >

-----------------

## OMDb API Tests

API to obtain movie information.

**Parameters:**

* key: **apiKey** represents your unique API key generate by https://www.omdbapi.com/
* key: **t** and value: **Prince of persia** represents movie title to search for
* key: **plot** and value: **full** return full plot
* key: **y** and value: **2010** represents year of relase
* key: **callback** and value: **jsonp** represents JSONP callback name

<img src="API-Test Images/OMDb API tests.jpg" >

-----------------
## Swagger PetStore

API to create a PetStore

**Pet Collection**

* Add a new pet to the store 

![Add a new pet to the store](https://user-images.githubusercontent.com/90641668/206936293-cd0e55b5-22f0-4812-bc9e-dbc225e2b2c3.jpg)

* Update an existing pet

![Update an existing pet](https://user-images.githubusercontent.com/90641668/206936339-9a7f00c4-4ed2-490a-8904-4dfaab9285bd.jpg)

* Find a pet by id

![Find a pet by id](https://user-images.githubusercontent.com/90641668/206936352-0dd349e1-fa9e-42bd-afdd-20404cdbdffc.jpg)

* Delete a pet by id

![Delete a pet by id](https://user-images.githubusercontent.com/90641668/206936395-05f867bb-8f13-4aba-8fe1-58e433e05e41.jpg)

**Store Collection**

* Place an order for a pet

![Place an order for a pet](https://user-images.githubusercontent.com/90641668/206936754-66cfd35f-b5e7-4e21-82a7-62e79dc35a79.jpg)

* Find purchase order by ID

![Find purchase order by ID](https://user-images.githubusercontent.com/90641668/206936795-61cf5253-5f4f-4fa9-9ea0-98db98518aaf.jpg)

* Delete purchase order by ID

![Delete purchase order by ID](https://user-images.githubusercontent.com/90641668/206936822-7ffb9c19-ec9d-4c06-a7ad-6b868ed792ff.jpg)

**User Collection**

* Create User

![Create User](https://user-images.githubusercontent.com/90641668/206937820-52726f6a-6a07-4478-a505-8528144664ec.jpg)

* Create Users with Array

![Create Users with array](https://user-images.githubusercontent.com/90641668/206937837-cf38ef0d-9a2f-427f-954c-dce63fd3d4f0.jpg)

* Logs User into the system

![Logs User into the system](https://user-images.githubusercontent.com/90641668/206937888-123d4311-6f1c-4133-8662-428e2806b521.jpg)

* Get User info

![Get user info](https://user-images.githubusercontent.com/90641668/206937913-5fcba829-7fdf-4c97-ae8a-636f70615a47.jpg)

* Update User

![Update user](https://user-images.githubusercontent.com/90641668/206937938-a417b33d-5985-4505-a254-e8f1bb76fd14.jpg)

* Logs out current logged in User sesion

![Logs out current logged in user session](https://user-images.githubusercontent.com/90641668/206937990-1bfd1b58-898a-44ac-b4f1-723c7a67eded.jpg)

* Delete User

![Delete User](https://user-images.githubusercontent.com/90641668/206938026-4c7ab34f-b9ac-4f83-87ab-bc7ba648c0b9.jpg)













