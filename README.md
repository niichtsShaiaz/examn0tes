
# 1. Plain JavaScript 
- Variable/function-Hoisting
> This means that all variables and functions will be hoisted to the beginning so all references will work. This is making sure no crashes or nullpointer errors occuers in nested functions, function closures, or variables.

- *this* in JavaScript and how it differs from what we know from Java/.net.
> In javascript **This** Refers to 'parent' calling it, be it a function or object. In javascript it refers to the instance of the object calling it - https://www.w3schools.com/js/js_this.asp

- Function Closures and the JavaScript Module Pattern
> Function closures refers to that a function calling another function is still able to acces the variables of the outer function. 
The javascript module pattern is the way that all 'modules' are similar to classes in Java. Since there is no actual classes.
A module can have private or public variables.

## Express
- Explain Pros & Cons in using Node.js + Express to implement your Backend compared to a strategy using, for example, Java/JAX-RS/Tomcat
>pro: Super hurtigt, JS only
Con: single threaded, newer



- Explain, using relevant examples, the Express concept; middleware.
>Middleware er noget der sker på alle requests, eller kun på specifikke routes hvis man vælger det. Det kan exekvere kode eller logge, eller bruge 3rd party plugins.
expressLogging and Express test

- Compare the express strategy toward (server side) templating with the one you used with Java on second semester and demonstrate a simple Server Side Rendering example using a technology of your own choice


**Coding Example:** *ExpressJS / ExpressDEBUG*
