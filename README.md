# BOILERPLATE BACKEND SETUP

## DESCRIPTION 
A basic backend set up, (right now 4/27/20 10:08am, leaning towards a authorization (login-register) but it can grow) 


### INSTALLED ORDER

- npm init
- npm i express 
      knex 
      sqlite3 
- npm i -D nodemon
- knex init

created all blank so far
- added index.js
- '   ' .gitignore
- '   ' api folder
        -- server.js
- '   ' auth folder
        -- auth-router
- '   ' data folder
        -- dbConfig.js
- '   ' middleware folder
        -- authorization.js
- '   ' users folder
        -- users-model.js
        -- users-router.js

1. populated the .gitignore with boilerplate stuff. (mostly so the node-modules would not be added.)
2. updated the package.json to have server, start, and test, under scripts.
3. updated the knex file to have the correct location to add migrations and seeds. (to the data folder)
4. boilerplate index.js set up
5. '         ' dbConfig.js set up
6. '         ' server.js set up (with a couple of routes)
7. '         ' users-model set up (with placeholders in place of functions)
8. Routes need to be set up, but that's once you know more about the end points you need. 
9. authorization.js (and other middleware) need to be set up (once you know what you need)