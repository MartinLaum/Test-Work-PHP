# test-work
create a RESTful service that stores organisations with relations (parent to child relation). Organization name is unique. One organisation may have multiple parents and daughters. All relations and organisations are inserted with one request (endpoint 1). API has a feature to retrieve all relations of one organization (endpoint 2). This endpoint response includes all parents, daughters and sisters of a given organization.
# What I used
- XAMPP
- VS Code
- Postman
# Installation
1. Download the repo files and place them into your preferred server.
2. Make any neccessary changes in db.php
3. Use Postman or any other similar program to insert your data.
4. Included api_db.sql as example data to test out endpoint 2. (exactly the same data as it is in the test work task.)
# File explanation
- api.php   - Has the necessary code to run both endpoints.
- db.php    - Has the necessary database connection settings.
- .htaccess - Should be self explanatory.
