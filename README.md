# DatingApp

Implementation of a project involving the creation of a dating application using ASP.NET Core and Angular technologies.

Project created 2023 March 18, finished 2023 May 16

## Demo

Application is published on https://dating-app-ornez-exanhncfafhkgxa4.polandcentral-01.azurewebsites.net/

## How to run locally

### .NET Backend
- Ensure SDK 7.0.407 is installed, or change it in DatingApp/global.json
- Build and run application from Visual Studio

### Angular Client
- Install mode nodules with 'npm install --force'
- ng serve

### Database
Go to DatingApp level folder and use command:
- docker compose up -d

Application is running on https://localhost:4200/

## Technologies

### ASP.NET Core 7
- Entity Framework (EF) Core
- Authentication & Authorization with JWT
- SignalR
- SqLite (used during developing)
- MS SQL Server (used as production database)

### Angular 14
- SignalR
- RxJs
- Bootstrap 5

### Others
- Docker
- CI/CL

## Udemy course

Udemy course "Build an app with ASPNET Core and Angular from scratch" by __Neil Cummings__ - 
a practical example of how to build an application with ASP.NET Core API and Angular from start to finish.

link to course: https://www.udemy.com/course/build-an-app-with-aspnet-core-and-angular-from-scratch/