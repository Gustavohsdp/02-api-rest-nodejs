# Functional requirements

  - [x] User must be able to create a new transaction;
  - [x] User must be able to obtain a summary of their account;
  - [x] User should be able to list all transactions that have ever taken place;
  - [x] User must be able to view a single transaction;

# Business rules

  - [x] The transaction can be of the credit type which will add to the total amount, or debit which will subtract;
  - [x] It must be possible to identify the user among the requests;
  - [x] User can only view transactions which he created;
  
  # Endpoints

  - Create transaction - POST - /transactions
  - List all transactions - GET - /transactions
  - account summary - GET - /transactions/summary
 

# Unit test
  - Unit of your application

# Integration test
  - Communication between two or more units

# E2E -> End to End
  - Simulates a user operating the application
  - Front end example
    - Opens the login page, enter the text xxxx@gmail.com in the field with email id, click the x button
  - Back end example
    - calls HTTP, WebSockets

# Test pyramid
  -E2E (do not depend on any technology, architecture) - are slow tests
