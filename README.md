# Backend_Test_H45

## Introduction
You are going to build a rest API server to expose a List of Drivers to a client application

### Required dependencies

- Python 3.8+
- pipenv
- Django rest framework
- Postgres 13+

### Deliverables

* Create a Github repo and invite `sedia.jaiteh@horizons45.com`. Your Github repo should contain the whole project with the truck application and basic server settings. Make sure the local server can be spun up without any errors. (You don't need to commit the local database `.sqlite` to the repo)

* Model(s): Design the model to store the driver's information in the database (Note: you may need multiple models and make use of database relationships like one-to-one, one-to-many etc). Each driver has the following fields or attributes:
  * name
  * mobile_number
  * email
  * city
  * district
  * language
  * an_aasigned_truck (each truch has a unique number_plate and and a unique registration_number)

* API endpoints and expected responses:

  #### /domain/driver/
  - Return a list of available drivers
  - Allow filtering using a driver's email, mobile_number, language and his truck's number_plate
  
  #### /domain/driver/id
  - Return a single driver

  #### /domain/driver/id
  - create a single driver

* README
  * Please justify every single library you have used for this test
  * Potential improvements
  * Production consideration
  * Assumptions: For example what assumptions did you make during your schema desiign for example

* Bonus Points
  * Creating bulk drivers
  * Unit test
