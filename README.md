# Ecommerce App Backend

A backend service made with [Fiber](https://gofiber.io/) to manage accounts, jwt authentications, add products, manage user cart, connect to 2 databases (mysql and mongodb), etc.

## Instalation

1. Clone this project
2. Copy .env.template file and rename it to .env
3. Create a mongo database and get the connection url
4. Change env mongo database url for the one you just created
6. Change env mysql variables to your connection
7. Create in your mysql db a table called "user" with the structure presented in the folder ```models/user.model.go```
8. Run the project with command:
```
go run .
```

## Frontend
This backend runs to give data to this [mobile app project](https://github.com/Sebas3270/ecommerce-app), if you would like to check how this front end use this backend, the requests and everything, visit the link provided!