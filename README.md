# Geolocalization Task

ELT project with Nominatin to enhance data from geolocalization points.

## Getting Started

Endpoints -

GET enhanced address list - /api/address/users-address/
GET single enhanced address - api/address/users-address/{id}
POST single enhanced address - api/address/users-address/
POST text file with geolocalization codes - /api/address/geo-points/

### Prerequisites

All you need to run this project is Docker and Postman (or any other API development environment). Simple as that.

### Installing

1 - Clone this project
2 - If you don't have docker installed run install_docker.sh or install docker and docker-compose
3 - Run deploy.sh
4 - Open your postman import the collection and done!

## Running the tests

It's pretty simple to run the unit tests. All you need to do is run the tests.sh script or execute the following command:
docker exec -it admissiontask_admissiontask_1 ./manage.py test address

### And coding style tests

These tests test the endpoints and their funcionality.

## Built With

* [Nominatim](https://nominatim.openstreetmap.org/) - Geolocalization
* [django-rest-framework](https://www.django-rest-framework.org/) - Endpoints

## Authors

* **Eduardo Lemos** - *Initial work* - [task-4all] (https://github.com/eDuhz/task-4all/)
