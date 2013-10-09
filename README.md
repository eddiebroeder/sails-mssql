![image_squidhome@2x.png](http://i.imgur.com/RIvu9.png) 

# sails-mssql

This is the salils adapter for using Microsoft SQL Server with Sails.js.

# todo

* ~~Required CRUD methods~~
* Add pagination support
* ~~Optional CRUD methods~~
    * ~~createEach~~
    * ~~findOrCreate~~
    * ~~findOrCreateEach~~
* ~~Database generation~~
* Refactor all queries with a criteria to use sql parameters
* Batch queries to prevent multiple database calls (such as createEach, findOrCreate, etc...)


## about sails.js and waterline
http://SailsJs.com

Waterline is a new kind of storage and retrieval engine for Sails.js.  It provides a uniform API for accessing stuff from different kinds of databases, protocols, and 3rd party APIs.  That means you write the same code to get users, whether they live in mySQL, LDAP, MongoDB, or Facebook.
