GROUP PROJECT

Authors:
Agapiou Marinos
Kamaras Georgios

We used Python, Mysql and Bottle web framework in order to create a dynamic webapp for storing and retrieving information about songs singers and their albums.

NOTES:
The changes that our program does in the database are negated right after
./app.py stops running. This can be changed, by uncommenting the
autocommit = True
parameter of the database connection, in our connection() function. We chose to
deliver the project with this parameter commented.
