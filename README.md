# Read Product Service

This is the microservice for List Product in the +Kotas App.

## Group Members

- Christopher Pallo
- Brayan Dávila

## Table of Contents

1. [Microservice Description](#microservice-description)
2. [Installation](#installation)
   - [Requirements](#requirements)
   - [Clone the Repository](#clone-the-repository)
   - [Install Dependencies](#install-dependencies)
   - [Start the Server](#start-the-server)
   - [Evidence](#evidence)
3. [Usage](#usage)
   - [Verify Server Functionality](#verify-server-functionality)

## Microservice Description

The `read-product-service` microservice is responsible for managing the list of users in the +kotas App. Allows you to list products using an HTTP GET request to the corresponding route.

## Installation

### Requirements

- Node.js
- npm (Node Package Manager)

### Clone the Repository

```sh
https://github.com/ChristopherPalloArias/gr8-read-product-service.git
cd read-product-service
```

### Install Dependencies
```sh
npm install
```

### Starting the Server
Before starting the application you must change the database credentials in the index.js file if you want to use the application locally and independently, this is because initially the application is configured to be used in conjunction with the rest of Microservices.
Repository: [https://github.com/ChristopherPalloArias/kotas-frontend](https://github.com/ChristopherPalloArias/kotas-frontend.git)

### Evidence
![image](https://github.com/user-attachments/assets/a8e67651-17df-47e3-8e71-46027b3a325d)

## Usage
### Verify Server Functionality

Method: GET 
URL: `http://gr8-load-balancer-users-1651289822.us-east-2.elb.amazonaws.com:8091`  
Description: This route displays a message to verify that the server is running.
![image](https://github.com/user-attachments/assets/6d2357b7-7f9c-4885-8f58-328f965a9c2a)

### List the Products

Method: GET  
URL: `http://gr8-load-balancer-users-1651289822.us-east-2.elb.amazonaws.com:8091//products`  
Description: This route returns the list of users in the +kotas app.
![image](https://github.com/user-attachments/assets/dd311bdd-f099-4a71-be5e-041607db4c9f)

