# Code 301, day 6

### JSON
- Something to keep in mind, JSON uses double quotes and has quotes around the keys. Strings in the values also use double quotes.
- Used to serialize objects (or parse on the other end) so machines can talk to other machines.
- Works well with AJAX to send data back forth to server.
- Good for local storage, keep preferences, locations, cache data.

### AJAX
- 'Asynchronous JavaScript and XML' but moving towards JSON instead of XML for objects.
- Asynchronous so you don't need to load/reload whole page every time you want to communicate with a server.
- You can also make requests programmatically (on event handling, or on a timer for example).
- Doesn't run the callback function until the data request is done.

### AJAX with JQUERY
- Send Request, register a callback function(async). (Ajax jquery methods listed on https://oscarotero.com/jquery/).
- Request is usually a header and a body. GET only uses the header, GET is probably the simplest type of request but more limited than POST.
- Make sure that anything that depends on the response goes in the callback!
- Only works in your domain.  Different ways to make it work cross-domain like JSONP. (JSONP is in reading starts on page 384).
