# asp.net-core-angular-skinet
https://github.com/ingafter60/asp.net-core-angular-skinet

START ---------16/11/2020 08:18--------
Course content

## 01. INTRODUCTION

01.1. Introduction
01.2. Setting up the development environtment
01.3. Setting up VS Code for C# development

## 02. API BASICS

02.1. Where to get the source code and course assets
02.2. Introduction

### 02.3. Creating the Web API project

	> help
	>> dotnet new -h
	Welcome to .NET Core 3.1!
	---------------------
	SDK Version: 3.1.403
	...
	Examples:
	    dotnet new mvc --auth Individual
	    dotnet new angular
	    dotnet new --help
	> sln
	>> dotnet new sln
	The template "Solution File" was created successfully.
	> create API
	>> dotnet new webapi -o API
	...
	Restore succeeded.
	> sln help
	>> dotnet sln -h
	> add API to solution
	>> dotnet sln add .\API\API.csproj
	> check the result
	>> dotnet sln list
	Project(s)
	----------
	API\API.csproj
	

02.4. Running the API using the DotNet CLI





02.5. Reviewing the Web API startup files
02.6. Adding our first API Controller
02.7. Adding a C# Entity class
02.8. Setting up Entity Framework
02.9. Adding a connection string
02.10. Adding an Entity Framework migration
02.11. Updating the database
02.12. Reading the data from the Database in the API
02.13. Postman Collections
02.14. Creating the additional projects
02.15. Saving our project into source control using Git and GitHub
02.16. Summary of section 2

## 03. API ARCHITECTURE

03.1. Introduction
03.2. The Repository Pattern
03.3. Adding a Repository and Interface
03.4. Adding the repository methods
03.5. Extending the products entity and creating related entities
03.6. Creating a new migration for the entities
03.7. Configuring the migrations
03.8. Applying the migrations and creating the Database at app startup
03.9. Adding Seed data
03.10. Adding the code to get the product brands and types
03.11. Eager loading of navigation properties
03.12. Summary of section 3

## 04. API GENERIC  REPOSITORY

04.1. Introduction
04.2. Creating a Generic repository and interface
04.3. Implementing the methods in the Generic repository
04.4. Introduction to the specification pattern
04.5. Creating a specification class
04.6. Creating a specification evaluator
04.7. Implementing the repository with specification methods
04.8. Using the specification methods in the controller
04.9. Using the specification methods in the controller
04.10. Using the Debugger to view the spec pattern in action
04.11. Shaping the data to return with DTOs
04.12. Adding AutoMapper to the API project
04.13. Configuring AutoMapper profiles
04.14. Adding a Custom Value Resolver for AutoMapper
04.15. Serving static content from the API
04.16. Summary of section 4

## 05. API ERROR HANDLING

05.1. Introduction
05.2. Creating a test controller for errors
05.3. Creating a consistent error response from the API
05.4. Adding a not found endpoint error handler
05.5. Creating Exception handler middleware
05.6. Improving the validation error responses
05.7. Adding Swagger for documenting our API
05.8. Improving the swagger documentation
05.9. Cleaning up the Startup class
05.10. Summary of section 5

## 06. API PAGING, FILTERING, SORTING & SEARCHING

06.1. Introduction
06.2. Adding a sorting specification class
06.3. Adding a sorting specification part 2
06.4. Working around the decimal problem in Sqlite
06.5. Adding filtering functionality
06.6. Adding Pagination Part 1
06.7. Adding Pagination Part 2
06.8. Adding Pagination Part 3
06.9. Adding CORS Support to the API
06.10. Summary of section 6

## 07. CLIENT - ANGULAR SETUP

07.1. Introduction
07.2. Setting up the developer environment for Angular
07.3. Creating the Angular project
07.4. Reviewing the Angular project files in the template
07.5. Setting up Angular to use HTTPS
07.6. Adding bootstrap and font-awesome
07.7. Adding VS Code extensions for Angular

## 08. CLIENT - ANGULAR BASICS

08.1. Introduction
08.2. Adding a Nav Bar component
08.3. Adding the NavBar HTML code
08.4. Styling the nav bar
08.5. Intro to the Http Client Module
08.6. Observables
08.7. Intro to Typescript
08.8. Typescript Demo
08.9. Creating a products interface
08.10. Summary of section 8

## 09. CLIENT - BUILDING THE UI FOR OUR SHOP

09.1. Introduction
09.2. Organising our files and folders
09.3. Intro to Angular services
09.4. Consuming services in the component
09.5. Designing the shop page
09.6. Adding a child component for the product items
09.7. Passing down data to child components
09.8. Adding the product filters
09.9. Adding the filter functionality
09.10. Hooking up the filter to the HTML
09.11. Adding the sort functionality
09.12. Adding the pagination functionality
09.13. Adding the pagination functionality part 2
09.14. Adding the pagination functionality part 3
09.15. Adding a pagination header
09.16. Making the pagination component a shared component
09.17. Pagination and Output properties
09.18. Adding the search functionality
09.19. Resolving the Bug!
09.20. Summary of section 9

## 10. CLIENT - ROUTING

10.1. Introduction
10.2. Creating additional components to route to
10.3. Creating the routes
10.4. Setting up the nav links
10.5. Making the links active
10.6. Getting an individual product
10.7. Adding the product detail page
10.8. Lazy loading angular modules
10.9. Summary of section 10

## 11. CLIENT - ERROR HANDLING

11.1. Introduction
11.2. Creating an error component for testing the error responses
11.3. Creating additional error components
11.4. Using the Http Interceptor to catch errors
11.5. Adding toast notifications
11.6. Handling validation errrors
11.7. Improving the internal server error component
11.8. Summary of section 11

## 12. CLIENT - PAZZAZZ

12.1. Introduction
12.2. Adding a section header
12.3. Adding breadcrumbs
12.4. Using the breadcrumb service
12.5. Setting the section header title from the breadcrumb service
12.6. Styling the product items
12.7. Changing the bootstrap theme
12.8. Adding loading indicators
12.9. Cleaning up loading issues
12.10. Adding the home page content
12.11. Summary of section 12

## 13. API - BASKET

13.1. Introduction
13.2. Setting up Redis
13.3. Setting up the basket class
13.4. Creating a basket repository interface
13.5. Implementing the basket repository
13.6. Adding the basket controller
13.7. Installing Redis on a Mac
13.8. Installing Redis on Windows
13.9. Testing the basket functionality
13.10. Summary of section 13

## 14. CLIENT - BASKET

14.1. Introduction
14.2. Creating the basket module
14.3. Creating the basket types
14.4. Basket service methods
14.5. Adding an item to the basket service method
14.6. Adding the add item to basket in the component method
14.7. Persisting the basket on startup
14.8. Displaying the basket item count in the nav bar
14.9. Styling the basket page
14.10. Adding the basket totals to the service
14.11. Creating the order summary component
14.12. Adding the increment and decrement functionality
14.13. Adding the basket component functions
14.14. Hooking up the product detail component to the basket
14.15. Adding the checkout module
14.16. Summary of section 14

## 15. API - IDENTITY

15.1. Introduction
15.2. Setting up the identity packages
15.3. Setting up the identity classes
15.4. Adding the IdentityDbContext
15.5. Adding a new migration
15.6. Seeding identity data
15.7. Adding the Startup services for identity
15.8. Adding identity to program class
15.9. Adding an Account controller
15.10. Registering a user
15.11. Adding a token generation service
15.12. Setting up identity to use the token
15.13. Testing the token
15.14. Troubleshooting auth issues
15.15. Adding additional account methods
15.16. Adding user manager extension methods
15.17. Adding another Dto for the user
15.18. Summary of section 15

## 16. API - VALIDATION

16.1. Introduction
16.2. .Net core error responses
16.3. Model validation
16.4. Checking for duplicate email addresses
16.5. Validating the basket
16.6. Updating swagger config for identity
16.7. Summary of section 16

## 17. CLIENT - IDENTITY

17.1. Introduction
17.2. Creating the account module
17.3. Creating the account service methods
17.4. Creating the login form
17.5. Angular forms introduction
17.6. Using reactive forms in Angular
17.7. Submitting data to the server
17.8. Updating the nav bar for the logged in user
17.9. Persisting the login
17.10. Adding a dropdown to the navbar
17.11. Form Validation in Angular
17.12. Displaying validation errors
17.13. Creating a reusable text input
17.14. Reusable text input template
17.15. Creating a register form
17.16. Dealing with modelstate errors
17.17. Async validation
17.18. Improving the async validator
17.19. Creating an auth guard
17.20. Using the replay subject
17.21. Summary of section 17

## 18. API - ORDERS

18.1. Introduction
18.2. Creating the order aggregate part 1
18.3. Creating the order aggregate part 2
18.4. Configuring the order entities
18.5. Store context update and seeding delivery methods
18.6. Creating the order migration
18.7. Creating an order service
18.8. Implementing the create order method
18.9. Creating the order controller
18.10. Debugging the order method
18.11. Introducing the Unit of work
18.12. Implementing the Unit of work
18.13. Updating the generic repository
18.14. Refactoring the Order service to use the Unit of work
18.15. Using the debugger to view the order creation
18.16. Implementing the Order get methods
18.17. Order controller get methods
18.18. Testing the order controller get methods
18.19. Shaping the order data
18.20. AutoMapper config for orders
18.21. Another AutoMapper value resolver
18.22. Summary of section 18

## 19. CLIENT CHECKOUT

19.1. Introduction
19.2. Checkout page layout
19.3. Creating a stepper component
19.4. Setting up the stepper component
19.5. Creating the checkout components
19.6. Adding the checkout form
19.7. Creating the address form
19.8. Creating the delivery form
19.9. Delivery method template
19.10. Using the Http interceptor to send the token
19.11. Making the basket summary shared
19.12. Checkout review component
19.13. Adding the forward back buttons for the stepper
19.14. Using the form status to mark the step complete
19.15. Populating the address form from API
19.16. Letting the user save the address
19.17. Updating the shipping price
19.18. Creating the order interface
19.19. Order submission
19.20. Problem solution and redirect to success
19.21. Checkout success page
19.22. Summary of section 19

## 20. CLIENT - ORDER MODULE

20.1. Introduction
20.2. Demo of finished solution
20.3. Solution to orders exercise
20.4. Solution to orders exercise stretch challenge

## 21. TAKING PAYMENTS

21.1. Introduction
21.2. PCI DSS
21.3. Strong Customer Authentication
21.4. Setting up stripe
21.5. Creating the payment service and interface
21.6. Implementing the payment intent
21.7. Creating the payment controller
21.8. Updating the client basket
21.9. Adding the payment intent function
21.10. Persisting the shipping price
21.11. Implementing stripe elements
21.12. Adding stripe elements to the components
21.13. Displaying card validation errors
21.14. Using the app stepper as an input property
21.15. Submitting the payment
21.16. Testing card failures
21.17. Tying the payment intent to the order
21.18. Making the submission a better experience
21.19. Loading indicators
21.20. Enabling linear mode
21.21. Stripe validation
21.22. Webhooks
21.23. Updating the payments service
21.24. Testing our webhooks with the stripe CLI
21.25. Summary of section 21

## 22. PERFORMANCE

22.1. Introduction
22.2. Setting up caching on the API
22.3. Creating a cache attribute class
22.4. Testing the caching
22.5. Caching on the client part 1
22.6. Caching on the client part 2
22.7. Caching on the client part 3
22.8. Pre-publishing adjustments
22.9. Summary of section 22

## 23. PUBLISHING

23.1. Introduction
23.2. Angular build configuration
23.3. Angular config changes
23.4. Building the angular app and running from Kestrel
23.5. Angular Ahead of Time compilation build
23.6. Installing MySQL
23.7. Switching DB Servers
23.8. Switching to the production database
23.9. Pre deployment work
23.10. Setting up a linux server part 1
23.11. Setting up a linux server part 2
23.12. Getting an HTTPS certificate from Lets Encrypt
23.13. End of course summary

END----------


# Prerequisites
*.d

# Object files
*.o
*.ko
*.obj
*.elf

# Linker output
*.ilk
*.map
*.exp

# Precompiled Headers
*.gch
*.pch

# Libraries
*.lib
*.a
*.la
*.lo

# Shared objects (inc. Windows DLLs)
*.dll
*.so
*.so.*
*.dylib

# Executables
*.exe
*.out
*.app
*.i*86
*.x86_64
*.hex

# Debug files
*.dSYM/
*.su
*.idb
*.pdb

# Kernel Module Compile Results
*.mod*
*.cmd
.tmp_versions/
modules.order
Module.symvers
Mkfile.old
dkms.conf
