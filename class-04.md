# links 

![link pic](https://martech.org/wp-content/uploads/2018/08/links-blue-ss-1920_gvstuk.jpg)

<p>Hyperlinks, usually called links, are a foundational concept behind the Web. To explain what links are, we need to step back to the very basics of Web architecture.</p.>

<p>Back in 1989, Tim Berners-Lee, the Web's inventor, spoke of the three pillars on which the Web stands:<p>

- URL, an address system that keeps track of Web documents
- HTTP, a transfer protocol to find documents when given their URLs
- HTML, a document format allowing for embedded hyperlinks

<p> As you can see in the three pillars, everything on the Web revolves around documents and how to access them. The Web's original purpose was to provide an easy way to reach, read, and navigate through text documents. Since then, the Web has evolved to provide access to images, videos, and binary data, but these improvements have hardly changed the three pillars.</p>

<P> Before the Web, it was quite hard to access documents and move from one to another. Being human-readable, URLs already made things easier, but it's hard to type a long URL whenever you want to access a document. This is where hyperlinks revolutionized everything. Links can correlate any text string with a URL, such that the user can instantly reach the target document by activating the link.</P>

<p>Links stand out from the surrounding text by being underlined and in blue text. Tap or click a link to activate it, or if you use a keyboard, press Tab until the link is in focus and hit Enter or Spacebar.Links are the breakthrough that made the Web so useful and successful. In the rest of this article, we discuss the various types of links and their importance to modern Web design.</P>


### Writing links 
Below is an example of attaching a link to yu code.
```
<a href="http://www.example.com">EXAMPLE</a>

Rendered output -  EXAMPLE (clickable link)
```
(https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_hyperlinks)

# Layout

![layout pic](https://colibriwp.com/blog/wp-content/uploads/2018/07/build-develop-site-web-design-content-1571569-pxhere.com_.jpg)

A website layout is a pattern (or framework) that defines a website’s structure. It has the role of structuring the information present on a site both for the website’s owner and for users. It provides clear paths for navigation within web pages and puts the most important elements of a website front and center.

Website layouts define the content hierarchy, regardless of whether or not you’re learning how to start a blog or building a simple website for your small business. Content will guide visitors around the website, and it must convey your message as well as possible to them. To put it short,  website layouts are critical elements that make a website a success, or a failure.

# Function, Methods and Objects

### Methods and Functions
Use this article as a reference sheet for JavaScript methods and functions.

Use this article as a reference sheet for JavaScript methods and functions.

### Function — a set of instructions that perform a task.
### Method — a set of instructions that are associated with an object.
### Functions

Functions are like recipes. They can execute a set of instructions on data or variables and return the result. The beauty of functions is that they are recyclable. That is, the function can be used repeatedly without having to write the same code again.

```
// Define a function that prints a string
function welcomeMessage() {
  console.log('Welcome to JavaScript');
}
// Call the function
welcomeMessage();
```
In the example above, the welcomeMessage function is used to display Welcome to JavaScript in the console. Let’s walk through this code step-by-step:

The function keyword indicates the start of a function.
The word that follows (welcomeMessage) is the function’s name.
The empty parentheses after welcomeMessage indicate that there are no parameters, or inputs, for the function.
The code between the opening ({) and closing (}) curly braces is a set of instructions. This code will only execute when the function is called.
To call a method, you need the function’s name, a pair of parentheses, and a semicolon. In this example, the function is called with welcomeMessage();.
Let’s also consider a function that receives inputs and returns outputs:

```
function concatName(firstName, middleName, lastName) {
  return firstName + ' ' + middleName + ' ' + lastName;
}
```

Let’s walk through this example step-by-step:

The concatName function is created with three parameters (inputs): firstName, middleName, and lastName. Think of these as variables that have not been set yet.
Inside of the function, the return keyword will return the concatenation of firstName, middleName, and lastName, with spaces in between each. The return keyword terminates the function it is within, and returns a value — any code inside the function that comes after the return keyword will not be evaluated (nor executed, itself).
You can save the returned string to a variable or log it to the console when you call the function.

```
var concatGWC = concatName('George', 'Washington', 'Carver');
```
In the example above, the concatName function is called with the following arguments: 'George', 'Washington', and 'Carver'. These values are saved into the variables firstName, middleName, and lastName inside of the function. The function returns a concatenation of these three strings — the concatGWC variable stores the returned concatenated string.
In this reference sheet we have used the words parameters and arguments to reference similar, but distinctly different elements of a function and function call. What’s the difference between these words?

Parameters are fields that serve as variable names inside of a function. In the example above, firstName, middleName, and lastName are parameters.
Arguments are the values passed to the function when it is called. In the example above, 'George', 'Washington', and 'Carver' are arguments.
### Methods

A method, like a function, is a set of instructions that perform a task. The difference is that a method is associated with an object, while a function is not. Let’s explore some of JavaScript’s built-in methods.

```
var str = 'Code';
var str1 = str.toLowerCase();
var str2 = str.toUpperCase();
```
The variable str in the example above stores the string ‘Code’. The .toLowerCase() and .toUpperCase() methods in the example above are called on str. Let’s talk through each line:

On the second line, the .toLowerCase() method is called on the str variable, which returns the lowercase string 'code'.
On the third line, the .toUpperCase() method is called on the str variable, which returns the uppercase string 'CODE'. Notice, periods are used to call a method on an object, as in str.toLowerCase();.

(https://www.codecademy.com/articles/fwd-js-methods-functions)

# Pair Programming 

![pair image](https://miro.medium.com/max/1400/1*v4q4iD3dQHgferJNNjmvag.jpeg)

Pair programming essentially means that two people write code together on one machine. It is a very collaborative way of working and involves a lot of communication. While a pair of developers work on a task together, they do not only write code, they also plan and discuss their work. They clarify ideas on the way, discuss approaches and come to better solutions.

There are many different ways to pair here are a couple examples:
- Ping Pong
- Strong-Style Pairing
- Pair development
- Remote pairing 

and many more 

There are also many advantages to pair programming here are a few below 

- Greater efficiency
- Engaged collaboration
- Learning from fellow students/co workers 
- Social skills
- Job interview readiness
- Work environment readiness

Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product. Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome. 
(https://www.codefellows.org/blog/6-reasons-for-pair-programming/)
(https://martinfowler.com/articles/on-pair-programming.html)
