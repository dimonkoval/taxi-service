# taxi-service
A microservice project that provides an API for ordering a taxi.

INSTALLATION

To install the taxi-service project, follow these steps:

Clone the repository with git clone https://github.com/username/taxi-service.git
Navigate to the project directory with cd taxi-service
Run mvn clean package to build the project

RUNNING

To run the taxi-service project, follow these steps:

Navigate to the project directory with cd taxi-service
Run the application with java -jar target/taxi-service.jar
The application will start at http://localhost:8080

FUNCTIONAL

/index - main page with access to all functions

for drivers

/drivers - display all drivers with the possibility of deletion
/drivers/add - create a new driver
/drivers/cars - display list of current cars for authorized driver

for car

/cars - display all cars with the possibility of deletion
/cars/add - create a new car
/cars/drivers/add - add driver to car

for manufacturer

/manufacturers - display all manufacturers with the possibility of deletion
/manufacturers/add - create a new manufacturer
