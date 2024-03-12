-src
--main
---java
----Controller
----Models
----Services

-implemented MVC framework

Q) How to set up?
A) Fork the project and run with all the required dependencies

API end points
-GET
1) /carts - to get all carts in the database.
2) /carts/{id} - to get a specific cart by id.
3) /carts/{idS}/{idE} - to get carts in range of id from starting idS till ending idE.
4) /carts/user/{id} - to get a cart associated with a user with id = {id}
5) /carts/user - to give error message (additional functionality)
-POST
1) /carts - request for adding a cart
-PATCH
1) /carts/{id} - request for updating a specific cart with id = {id}
-DELETE
1) /carts/{id} - request for deleting a specific cart with id = {id}

