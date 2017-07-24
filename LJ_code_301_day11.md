# Code 301, day 11

## URLs and Routing

### Routing and Controllers
  - Controller includes the bit of code that handles a request AND the route that gets the request to the correct handler.
  - Routing lets you remove file extensions.
  - client-side route can let you know what resource the user wants AND some additional information.  can use javascript to interpret the route, take it apart, and then call the correct handler function for the pieces.  
  - if you set up all the routing client side you can have just one index page and not have to navigate between sites.
  - Controller will handle user request, convert the route into displayed content with proper data loaded.  Controller is just a list of functions waiting to be called. typically one per resource.
  - When you are setting up a single page app, you can sort your scripts into models, views, and controllers.

### Aside
  - When working on today's stretch goal, Jason and I found that there were some interesting interactions between the client-side and server-side routing.  We eventually figured out that they could behave how we wanted, but only if we changed them appropriately to work together.
