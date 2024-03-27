# Banking System With Spring Boot And Angular with Spring Security

## Introduction

This project helps us to understand the basic working of Bank accounts. Some of the functionalities implemented are
- Account creation
- Transactions between two accounts
- Fetching of the transaction history

## Prerequisites
- java 1.8.x
- maven 3.x
- npm

### Steps To Setup Backend

**1. Clone the repository**
```bash
    git clone https://github.com/sneh2102/online-banking.git
```

**2. Move to root directory of backend**

**3. Build project**
```bash
    mvn clean install
``` 

**4. Run project** 
```bash
    java -jar target/backend-0.0.1-SNAPSHOT.jar
``` 
- Alternatively, you can run the app without packaging it using -
```bash
    mvn spring-boot:run
```
  #### Explore apis in backend

The app defines following APIs. 
 
```   
    POST /api/signup   
    POST /api/user
    GET /api/user
    PUT /api/user
    GET /api/account
    POST /api/transfer
    GET /api/transaction      
```

### Steps To Setup Frontend

**1. Move To Frontend Derectory**

**2. Install Package**
```bash 
    npm install
```

**3. Run Project**
```bash
    npm start
```

**4. Open url**
```bash
    http://localhost:4200/
```
# Application Screenshots

### Login

![Login image](https://github.com/sneh2102/online-banking/blob/main/images/login.PNG)

### Register

![Register image](https://github.com/sneh2102/online-banking/blob/main/images/register.PNG)

### Home

![Home Page image](https://github.com/sneh2102/online-banking/blob/main/images/home.PNG)

### Profile

![Profile image](https://github.com/sneh2102/online-banking/blob/main/images/profile.PNG)

### Transaction History

![History image](https://github.com/sneh2102/online-banking/blob/main/images/history.PNG)

### Transfer

![Transfer image](https://github.com/sneh2102/online-banking/blob/main/images/transfer.PNG)


# Future Extension
If a further chance is given to take the project ahead, then with the considerable knowledge in Angular and Spring Boot, I would be happy to invest my skills to build a creative and helpful solution for the society.
