# Error Handling & Debugging

![bugs](https://miro.medium.com/max/1400/0*FS04SrmkxxSWGrL-.png
)


Error handling in JavaScript
JavaScript is a loosely-typed language. It does not give compile-time errors. So some times you will get a runtime error for accessing an undefined variable or calling undefined function etc.

JavaScript provides error-handling mechanism to catch runtime errors using try-catch-finally block, similar to other languages like Java or C#.

syntax 

```
try
{
    // code that may throw an error
}
catch(ex)
{
    // code to be executed if an error occurs
}
finally{
    // code to be executed regardless of an error occurs or not
}
```

### try: 
wrap suspicious code that may throw an error in try block.
 ### catch: 
 write code to do something in catch block when an error occurs. The catch block can have parameters that will give you error information. Generally catch block is used to log an error or display specific messages to the user.
### finally: 
code in the finally block will always be executed regardless of the occurrence of an error. The finally block can be used to complete the remaining task or reset variables that might have changed before error occurred in try block.
Let's look at simple error handling examples.

```
Example: Error Handling in JS
try
{
    var result  =  Sum(10, 20); // Sum is not defined yet
}
catch(ex)
{
    document.getElementById("errorMessage").innerHTML = ex;
}
```

In the above example, we are calling function Sum, which is not defined yet. So, try block will throw an error which will be handled by catch block. Ex includes error message that can be displayed.

The finally block executes regardless of whatever happens.

Example: finally Block
```
try
{
     var result  =  Sum(10, 20); // Sum is not defined yet
}
catch(ex)
{
    document.getElementById("errorMessage").innerHTML = ex;
}
finally{
    document.getElementById("message").innerHTML = "finally block executed";
}
```

throw
Use throw keyword to raise a custom error.

Example: 
```
throw Error
try
{
    throw "Error occurred";
}
catch(ex)
{
    alert(ex);
}
```
You can use JavaScript object for more information about an error.

Example: throw error with error info

```
try 
{
    throw {
        number: 101,
        message: "Error occurred"
    };
}
catch (ex) {
    alert(ex.number + "- " + ex.message);
}
```




![debug](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2019/08/hero-snapshot-debugger.png)

# Debugging

## Code Debugging
Programming code might contain syntax errors, or logical errors.

Many of these errors are difficult to diagnose.

Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.

Searching for (and fixing) errors in programming code is called code debugging.

## JavaScript Debuggers
Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.

Built-in debuggers can be turned on and off, forcing errors to be reported to the user.

With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.

Normally, otherwise follow the steps at the bottom of this page, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.

## The console.log() Method
If your browser supports debugging, you can use console.log() to display JavaScript values in the debugger window:

Example
```
<!DOCTYPE html>
<html>
<body>

<h1>My First Web Page</h1>

<script>
a = 5;
b = 6;
c = a + b;
console.log(c);
</script>

</body>
</html>
```
## Setting Breakpoints
In the debugger window, you can set breakpoints in the JavaScript code.

At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values.

After examining values, you can resume the execution of code (typically with a play button).

## The debugger Keyword
The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function.

This has the same function as setting a breakpoint in the debugger.

If no debugging is available, the debugger statement has no effect.

With the debugger turned on, this code will stop executing before it executes the third line.

Example
```
let x = 15 * 5;
debugger;
document.getElementById("demo").innerHTML = x;
```
### Major Browsers' Debugging Tools

Normally, you activate debugging in your browser with F12, and select "Console" in the debugger menu.

Otherwise follow these steps:

- Chrome
Open the browser.
From the menu, select "More tools".
From tools, choose "Developer tools".
Finally, select Console.
- Firefox
Open the browser.
From the menu, select "Web Developer".
Finally, select "Web Console".
- Edge
Open the browser.
From the menu, select "Developer Tools".
Finally, select "Console".
- Opera
Open the browser.
From the menu, select "Developer".
From "Developer", select "Developer tools".
Finally, select "Console".
Safari
- Go to Safari, Preferences, Advanced in the main menu.
Check "Enable Show Develop menu in menu bar".
When the new option "Develop" appears in the menu:
Choose "Show Error Console".