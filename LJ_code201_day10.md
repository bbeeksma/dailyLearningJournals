# Code 201, day 10

### Debugging

Debugger tool allows us to se what is going on in our code. Can set breakpoints to stop and see exactly what is going on.  Can also go line by line.  Scope will show variables and what values they currently have.  Call Stack shows what functions you are inside.  Error messages in console will show you the stack trace and where the error occurred.  You can click on the line it gives you to go to that line in the source.

Try/catch  try part attempts to run. if there is an error catch runs, finally part always runs.

Pg. 484 and 485 have good lists of common errors.


### CSS

css-tricks.com - good resource.  today we grabbed media query from here.

#### media queries:
start with @media the you define what you are targeting. today we looked at 'only screen'.
```
@media only screen and (min-width: 1024px){
  body{
    background-color: yellow;
  }
}
```
can have more than one and (something) if you want.
you move the things you want to change into the media queries for the condition you are targeting.  example width, margin.
In inspector you only see media queries when they would apply.
Best practice is to set the default settings for mobile and then add style as you go up in size.  To keep from having to rewrite all the css best to thing about how things might need to move or resize then layer the changes on from your base layer.
