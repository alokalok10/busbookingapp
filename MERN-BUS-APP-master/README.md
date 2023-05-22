# MERN-BUS-APP
## MFRP (My First Real Project) 



The Bus ticket application is composed of the following Features:

### Front-End

* Sign-In & Sign-Up Pages.

* Uses Token based system, so only registered users can access the website  passport js.

* Password hashing using passport js.

* Has a profile page, which will display all information about the signed in user.

* List of cities for users to choose from (starting city & destination city). 

* Getting list of bus's of different companies with various details.

* Seat selection page has a very user friendly environment, which also generates dynamic forms for storing data's of passengers.

* Has a Confirmation page, which gets a debit card data using react-credit-cards. This version of the application does not include handling the payment process. 

* Final page has a ticket displaying component, it displays all passenger data and also generates a random number as a transaction ID.



This project also demonstrates:

* a typcial React project layout structure

**Screenshots:**
Landing Page:

![](documentationResources/bus.gif)

Signing In Page:

![](documentationResources/signin.png)


---




## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

The following software is required to be installed on your system:

* Node 8.x
* Npm 3.x

Type the following commands in the terminal to verify your node and npm versions

```bash
node -v
npm -v
```

### Install

Follow the following steps to get development environment running.

* Clone _'MERN-BUS-APP.git'_ repository from GitHub

  ```bash
  git clone  https://github.com/alokalok10/busbookingapp.git
  ```

   _OR USING SSH_

  ```bash
  git clone git@https://github.com/alokalok10/busbookingapp.git
  ```

* Install node modules

   ```bash
   
   cd frontend
   npm install react
   npm start
   ```


### Starting  front end 

* Build application

  This command will start the mongodb and the front end part.

  ```bash
  cd frontend
  npm start
  
  ```


---

And Am also working on backend and did comp to update soon to full mern 


