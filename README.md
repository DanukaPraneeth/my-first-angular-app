# Angular Smart Table - Employee Managment System

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.0.

## Prerequisites

Below are the front-end technologies that used in this project. 
 * Angular 9 or above
 * Bootstrap 4
 * npm 6.9.0 or above
 * Node js 10+
 * Angular CLI 
 
Dummy REST API has used for data record into table and delete records from database. 

For coding, you can use Visual Studio 2017 or any other editor that supports Angular App development

## Development server

System should have installed Node.js and proper NPM version (run `nmp install`). Also install the latest version of Angular CLI. 

Then go to the downloaded source file where you should have all the files. In command prompt, navigate the directory to root workstation(...\Angular-employee-table-master) and execute `nmp install` (this will create `node_modules` folder) to install required JSON files and then run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you have not made any changes for the source files.

By default, the Angular app runs on 4200 port but you can change default port with the following command:  `ng serve --port 4201`

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
 
## Code explanation

In this app following features have implemented;
  * Create an Employee
  * Update an Employee
  * List of Employees
  * Delete Employee
  * View Employee
 
Used Components, Services, Modules, and Class;

Components
 * create-employee
 * employee-list
 * employee-details

Services
 * employee.service.ts - Service for Http Client methods

Modules
 * FormsModule
 * HttpClientModule
 * AppRoutingModule
 
Employee Class (Typescript class)
 * employee.ts: class Employee (id, firstName, lastName, emailId

## Output
Output interfaces at `http://localhost:4200/` are as follows. 


<img src="images/Screenshot from 2020-11-21 23-16-16.png">

<img src="images/Screenshot from 2020-11-21 23-17-01.png">
