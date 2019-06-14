# Node-Js-Router
Basic Node Js router without using any npm modules.

USAGE

This router has only 2 functions router.create() and router.default()

router.default(Function) 
this function is called when the sent path doesn't match any routes.
It takes in a handler function. The handler function receives the Request and Response objects.

router.create(path, Function)
First parameter takes in the parsed URL path. 
Example: if the URL is https://domain/users then the path shoud be "/users"
The second parameter takes in the handler function for that pirticular path. 
Each request type should be handled seperately using a switch statement
