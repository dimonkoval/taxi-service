
# taxi-service
The Taxi-Service project is designed to facilitate the process of ordering a taxi through a web-based application. It offers a set of APIs that allow users to interact with the system and perform various actions related to drivers, cars, and manufacturers.

## Technologies
The Taxi-Service project utilizes a range of technologies to provide a robust and efficient taxi ordering API. The key technologies used in this project include:

- JDBC 
- Tomcat
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

## Functional API Endpoints

The Taxi-Service project offers the following API endpoints and functionalities:

- For Drivers:

  - Display All Drivers (/drivers): Retrieves and displays a list of all drivers registered in the system. Users have the option to delete a driver from the database.

  - Create a New Driver (/drivers/add): Allows the creation of a new driver by providing the necessary details such as name, contact information, and license information.

  - Display List of Current Cars for Authorized Driver (/drivers/cars): Displays the list of cars associated with each authorized driver. This feature enables users to view the cars assigned to a specific driver.

- For Cars:

  - Display All Cars (/cars): Retrieves and displays a list of all cars available in the system. Users can delete a car from the database using this endpoint.

  - Create a New Car (/cars/add): Allows the addition of a new car to the system. Users need to provide details such as the car's make, model, and registration information.

  - Add Driver to Car (/cars/drivers/add): Associates a driver with a specific car. This endpoint enables users to assign a driver to a car within the system.

- For Manufacturers:

  - Display All Manufacturers (/manufacturers): Retrieves and displays a list of all car manufacturers registered in the system. This endpoint allows users to view and delete manufacturers from the database.

  - Create a New Manufacturer (/manufacturers/add): Enables the addition of a new car manufacturer to the system. Users can provide details such as the manufacturer's name, country of origin, and other relevant information.
- Main Page (/index): The main page provides access to all available functions and actions within the system.  
