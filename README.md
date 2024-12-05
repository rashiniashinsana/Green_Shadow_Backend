# Green Shadow Pvt Ltd  

Green Shadow Pvt Ltd is a forward-thinking agricultural company specializing in the cultivation of root crops and cereals. Our mission is to revolutionize farming with modern technology, sustainable practices, and efficient resource management. This repository contains the system developed to manage various aspects of our agricultural operations.  

## Features  
The system is designed to manage:  
- **Fields**: Allocation and monitoring of cultivation areas.  
- **Crops**: Detailed tracking of crop types and their growth.  
- **Staff**: Management of human resources and roles.  
- **Monitoring Logs**: Observations and activity records for fields and crops.  
- **Vehicles**: Tracking and maintenance of agricultural vehicles.  
- **Equipment**: Management of tools and machinery used in farming.  

## System Overview  

### Technologies Used  
- **Backend**: Spring Boot, Spring Data JPA, Hibernate  
- **Frontend**: HTML, CSS, JavaScript, AJAX  
- **Database**: MySQL  
- **Security**: JWT for secure authentication  
- **Server**: Apache Tomcat  

### Endpoints  
- **Authentication**:  
  - `POST /auth/signup`: Create a new user account.  
  - `POST /auth/signin`: Log in and retrieve access token.  
  - `POST /auth/refresh`: Refresh an expired token.  

- **Field Management**:  
  - `POST /field`: Save a new field.  
  - `PUT /field/{id}`: Update existing field details.  
  - `DELETE /field/{id}`: Delete a field.  
  - `GET /field`: Retrieve all fields.  

- **Crop Management**:  
  - `POST /crop`: Save a new crop.  
  - `PUT /crop/{id}`: Update crop details.  
  - `DELETE /crop/{id}`: Delete a crop.  
  - `GET /crop`: Retrieve all crops.  

- **Staff Management**:  
  - `POST /staff`: Add new staff.  
  - `PUT /staff/{id}`: Update staff details.  
  - `DELETE /staff/{id}`: Remove staff.  
  - `GET /staff`: Retrieve staff details.  

- **Vehicle Management**:  
  - `POST /vehicle`: Save a new vehicle.  
  - `PUT /vehicle/{id}`: Update vehicle details.  
  - `DELETE /vehicle/{id}`: Delete a vehicle.  
  - `GET /vehicle`: Retrieve all vehicles.  

- **Equipment Management**:  
  - `POST /equipment`: Add a new equipment item.  
  - `PUT /equipment/{id}`: Update equipment details.  
  - `DELETE /equipment/{id}`: Remove equipment.  
  - `GET /equipment`: Retrieve equipment details.  

- **Monitoring Logs**:  
  - `POST /log`: Add a new monitoring log.  
  - `PUT /log/{id}`: Update log details.  
  - `DELETE /log/{id}`: Remove a log.  
  - `GET /log`: Retrieve all monitoring logs.  

## Installation  

### Prerequisites  
- Java 11 or higher  
- MySQL Database  
- Apache Tomcat Server  

### Steps  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/GreenShadowPvtLtd/project.git  
