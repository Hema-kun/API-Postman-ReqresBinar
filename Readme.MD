## API Testing Using Postman@
Welcome to API Testing using Postman. This testing is handler request and assert the response from assert time to data body.


## Framework and How to Install
- clone the repo

### Run with Postman
- Import json to postman
- Or click documentation in evidence

### Run with Newman
- npm install newman 
- newman run [collection.json] -e [environment.json]

### Run with Html Reporter
- npm install -g newman-reporter-html
- newman run [collection.json] -e [environment.json] -r html

## API / Features
Features tested includes:
- LIST USERS
- SINGLE USER
- SINGLE USER NOT FOUND
- LIST <RESOURCE>
- SINGLE <RESOURCE>
- SINGLE <RESOURCE> NOT FOUND
- CREATE
- UPDATE
- DELETE
- REGISTER - SUCCESSFUL
- REGISTER - UNSUCCESSFUL
- LOGIN - SUCCESSFUL
- LOGIN - UNSUCCESSFUL

## Evidence

**Html Report**

[https://hema-kun.github.io/API-Postman-ReqresBinar/]

**documentation**

[https://documenter.getpostman.com/view/20672644/2sA3e48TvX]
