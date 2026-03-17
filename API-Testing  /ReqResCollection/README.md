# ReqRes API Testing Collection

## Overview
This folder contains the **Postman collection** for testing the [ReqRes API](https://reqres.in/), a demo REST API for practicing API testing.  
The collection demonstrates **basic CRUD operations**, testing both GET and POST endpoints, and can be used for practice or portfolio purposes.

---

## Folder Contents

| File / Folder | Description |
|---------------|-------------|
| `ReqResCollection.json` | Postman collection containing all API requests |
| `ReqResEnvironment.json` | Postman environment file with variables (base URL, API key, etc.) |
| `README.md` | This file, explaining the project |
|javaScripts/ |  javascripts for automating API tests |

---

## Tools Used
- [Postman](https://www.postman.com/) – for API testing  
- **JavaScript** – Used in Postman for automation scripts (Pre-request & Test scripts)  

---

## How to Use

1. Open **Postman**  
2. Click **Import** → Upload `ReqResCollection.json`  
3. If needed, import `ReqResEnvironment.json` to set environment variables  
4. Run requests individually or use **Collection Runner** to run all tests  

---

## Features Tested
- **GET Users** – Retrieve list of users  
- **GET Single User** – Retrieve a single user by ID  
- **POST Create User** – Create a new user  
- **PUT Update User** – Update user details  
- **DELETE User** – Delete a user  

---

## Notes
- Ensure environment variables are set before running collection  
- You can modify requests or add new endpoints for practice  
- Ideal for **manual and automation testing practice**  

---

## Author
**Your Name** – QA Engineer / Automation Enthusiast  
[GitHub Profile](https://github.com/yourusername)
