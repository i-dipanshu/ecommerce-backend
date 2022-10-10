## E-commerce Application Server in Node.js

* This web server is build for an E-commerce in Node.js.
* It uses `express` framework for Node.js and `mongoose` for mongodb.
* It's frontend is under development which uses `Redux` for state management and `React` for frontend.

## Project Background

* The E-commerce sector is one of the fastest growing sectors in today's world. 
* This brings far greater challenge that a developer need to meet cutting-edge commercial requirement.
* I build this project in order to test the limit of my skill in Web development.

## Application Overview

* Api calls are made by redux to node.js which then communicates with mongodb to do a specific task.

<img src="https://user-images.githubusercontent.com/84374342/193429719-add08b93-4c54-4b53-8d1e-8ce3b2b3f226.png"/>

## Key Features

<img src="https://user-images.githubusercontent.com/84374342/193429841-c8f4c987-d7c6-462c-9a70-aefaf4e14186.png"/>

## REST Api's

* Base Address = http://<hostname>:port/api/v1
* Routes catagories
    - **/**- routes every body can access, however some routes can accessed only if you are logged in.
    - **/admin** - routes to resources that can only accessed by admin

<img src="https://user-images.githubusercontent.com/84374342/193429900-badff158-494d-4af4-b16d-0245b36f87cf.png"/>

<!-- ## Folder Structure -->

## Awaited Feature


- [ ] Payment gateway for payments using `RazorPay`

- [ ] Google and Apple Authorization using `Passport.js`
- [ ] Realtime Customer Chat Service using  `socket.io`
- [ ] Implement servers for hosting images .


## Contribution Guide

* Clone the repository and run `npm i`.

* Add a `config.env` file in `config` folder and paste the below fields in it and then fill up the your preferred data
```.env
WEBSITE_NAME = 

PORT = 

DB_URI = mongodb://<hostname>:27017/<db_name>

JWT_SECRET = 

JWT_EXPIRES = 

COOKIE_EXPIRE = 

SMTP_HOST = smtp.gmail.com

SMTP_PORT = 587

SMTP_SERVICE = gmail


SMTP_MAIL= 

SMTP_PASSWORD= 
```

* To start a development server
```
npm run dev
```
* Feel free to raise a issue 