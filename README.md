# Project_hotel

Description:
Project has 2 sub systems that interact with each other via REST web services. First one is frontend application, which is written in Angular and Bootstrap.
Second one is backend project which exposes REST APIs for angular application to consume. The backend is written in C#/.NET. The database used is SQL Server.

Running the application:

1. frontend - 
  npm install(first time user)
  ng serve --open 
  
2. backend -
    For backend we used code first approach, where the tables are auto generated based on the models used.
    So in your SSMS create a schema with : Create Database Hotel Application
    Then inside package console of Visual Studio:
    Write following commands:
    (i). Add-Migration DotNetProjectBackend.Model.ApplicationContext
    (ii). update-database

