# Building a RESTful Web Service

## What You Will Build

This guide walks you through the process of creating a “Hello, World” RESTful web service with Spring.

You will build a service that will accept HTTP GET requests at http://localhost:8080/greeting.

It will respond with a JSON representation of a greeting, as the following listing shows

{"id":1,"content":"Hello, World!"}

You can customize the greeting with an optional name parameter in the query string, as the following listing shows:

http://localhost:8080/greeting?name=User

The name parameter value overrides the default value of World and is reflected in the response, as the following listing shows:
{"id":1,"content":"Hello, User!"}


## What You Need

* About 15 minutes

* A favorite text editor or IDE

* Java 17 or later

* Gradle 7.5+ or Maven 3.5+

## Create a Resource Representation Class

![{D9631D38-4765-49AC-81EC-4B0A8569CD6C}](https://github.com/user-attachments/assets/d4ff907b-fca8-414f-ad67-90276ef45d7e)


## Create a Resource Controller

![{F1DA9B01-39FD-4E59-A964-443DCA424BFD}](https://github.com/user-attachments/assets/b3860050-2360-4c79-8478-7e457525623e)

## Run the service

![{E8D5E6D6-D790-468B-BB20-CECCAC75F835}](https://github.com/user-attachments/assets/951e0e60-1e1f-4db0-9e17-ea43752b7be5)

