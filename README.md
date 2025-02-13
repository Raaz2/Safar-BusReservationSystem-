

## SAFAR :- BUS RESERVATION MANAGEMENT PORTAL


 Project code: few-houses-4121

The bus reservation system portal is a web-based application that enables users to book bus tickets online. The system will allow users book available buses based on their source and destination cities, reserve the seats, and make payments securely. The system will also provide a UI based dashboard for admin to manage their bus related operations.


## Features

 * User and Admin authentication & validation with session uuid.

#### Admin Features:

    - Administrator Role of the entire application
    - Only registered admins with valid session token can add/update/delete route and bus from main database
    - Admin can access the details of different users and reservations.
#### User Features:
    - Registering themselves with application, and logging in to get the valid session token
    - Viewing list of available buses and booking a reservation
    - Only logged in user can access his reservations, profile updation and other features.

<br>

## ER Diagrm
<img src="https://images.unsplash.com/photo-1690961698101-76b8efea1308?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=940&q=80" > </img>

<br>

## Flow Chart
<img src='https://images.unsplash.com/photo-1690961931664-6a30a59822e7?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1334&q=80'></img>

## Modules

* Login, Logout Module
* Admin Module
* User Module
* Route Module
* Bus Module
* Reservation Module
* Feedback Module

## 🏷️ Tech Stack Used :-
* Java
* Spring Framework
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL
* HTML
* CSS
* JavaScript

## Contributors

* [@Abhay Kumar Vishwakarma](https://github.com/AbhayKumarVishwakarma)
* [@Ankit Kumar](https://github.com/Github2k10)
* [@Niharika Pandey](https://github.com/niharikapandey94)
* [@Yash Nimkar](https://github.com/Yash-Nimkar0)
* [@Rajeev Ranjan Mishra](https://github.com/Raaz2)

## Installation & Run

* Before running the API server, you should update the database config inside the [application.properties](https://github.com/AbhayKumarVishwakarma/few-houses-4121/blob/main/Bus%20Reservation%20System%20Portal/Backend/bus_reservation/src/main/resources/application.properties) file. 
* Update the port number, username and password as per your local database config.

```
      server.port=8999

      #db specific properties
      spring.datasource.url=jdbc:mysql://localhost:3306/busdb
      spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
      spring.datasource.username=root
      spring.datasource.password=root

      #ORM s/w specific properties
      spring.jpa.hibernate.ddl-auto=update
      spring.jpa.show-sql=true

```

## API Root Endpoint

`https://localhost:8999/`
 
`http://localhost:8999/swagger-ui/`

