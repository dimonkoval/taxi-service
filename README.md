
# taxi-service
The Taxi-Service project is designed to facilitate the process of ordering a taxi through a web-based application. It offers a set of APIs that allow users to interact with the system and perform various actions related to drivers, cars, and manufacturers.

## Technologies
The Taxi-Service project utilizes a range of technologies to provide a robust and efficient taxi ordering API. The key technologies used in this project include:

- JDBC 
- Tomcat 9.0.72
- Maven
- MySQL
- Git
- RESTful API

## Installation

To install the taxi-service project, follow these steps:

Clone the repository with git clone https://github.com/username/taxi-service.git
Navigate to the project directory with cd taxi-service
Run mvn clean package to build the project

## Database Connection

To connect to the database, follow these steps:

1. Create a new database and a user with sufficient privileges to access the database.
2. Replace the `{username}` and `{password}` placeholders in the `<YOUR_USERNAME>` and `<YOUR_PASSWORD>` variables in the `ConnectionUtil` class with the actual values for your database connection.
3. Run the `ConnectionUtil` class to establish a connection to the database.

## Functional

<p style="color:yellow;">/index</p> - main page with access to all functions

<p style="font-size:20px; color:red;">for drivers</p>

<p style="color:yellow;">/drivers</p> - display all drivers with the possibility of deletion

<p style="color:yellow;">/drivers/add</p> - create a new driver

<p style="color:yellow;">/drivers/cars</p> - display list of current cars for authorized driver


<p style="font-size:20px; color:red;">for car

<p style="color:yellow;">/cars</p> - display all cars with the possibility of deletion

<p style="color:yellow;">/cars/add</p> - create a new car

<p style="color:yellow;">/cars/drivers/add</p> - add driver to car


<p style="font-size:20px; color:red;">for manufacturer

<p style="color:yellow;">/manufacturers</p> - display all manufacturers with the possibility of deletion

<p style="color:yellow;">/manufacturers/add</p> - create a new manufacturer
