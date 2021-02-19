# ECSE3038_lab3
# Aim of Lab
* This lab purpose is to get students more accustomed to the technologies used in designing and implementing a RESTful API server.
# Program Description
# Requirements
* In continuation of the previous lab, the client's budget recently increased and now they're able to pat for a database service. A research has been conducted and found that MongoDB is the most suitable database platform for the project. With this information, the client has asked to modify the API server to store all `Tank` related data to be stored in the database. The `Profile` data can be handled the same way as it was originally implemented, where the profile data is saved in a variable on the server.

# Function Description
* GET /data
As previously implemented, when this route is requested, the server should respond with an array of zero more tank objects.
* POST /data
As previously implemented, the server should be able to handle a POST request that consumes a JSON body, validates it against schema and returns the saved document.
* PATCH /data/:id
As previously implemented, your server should allow a user to alter the parts of one of the tanks after it has been posted. The server should allow the requester to make a JSON body with any combination of the four attributes and update them as necessary.
* DELETE /data/:id
Your server should allow the requester to delete any previously POSTed object.
