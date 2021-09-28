# Basics of HTML, CSS & JS
 
## Text
<p>In HTML Markup is a way to manipulate and characterize your text to give it different characteristics.  **Markup** is what HTML tags do to the text inside of them; they mark it as a specific type of text. For example, markup text could come in the form of boldface or italicized type to draw specific attention to a word or phrase. (https://www.investopedia.com/terms/h/html.asp).,</P> 

<br> There are typically two types of markup text.  Semantic and structural, <br>

**Semantic**-
 HTML is the use of HTML markup to reinforce the semantics, or meaning, of the information in webpages and web applications rather than merely to define its presentation or look. Examples below.

 ```
 <p>Why do <em>you</em> think that is interesting?</p>
<p>You must <strong>never</strong> let that happen.</p>
<p>I used the <code>&lt;li&gt;</code> tag for each item.</p>
```
This what the rendering would look like.<br>
>Why do you think that is interesting?

>You must never let that happen.

>I used the `<li>` tag for each item.
 

**Structural**-
Structural Markup provides information such as where emphasis is placed in a sentence, that something you have written is a quotation, the meaning of acronyms and so on. These are the basic tags which must be a part of every web page. They tell the browser that the document is a web page.
```
<html>
<head>
<title>Title of Webpage</title>
</head>
<body>
This is where the main part of the web page would go
</body>
</html>
```
# Intro to CSS

Cascading Style Sheets, fondly referred to as CSS, is a simple design language intended to simplify the process of making web pages presentable.<br>

<p>CSS handles the look and feel part of a web page. Using CSS, you can control the color of the text, the style of fonts, the spacing between paragraphs, how columns are sized and laid out, what background images or colors are used, layout designs,variations in display for different devices and screen sizes as well as a variety of other effects.</P>

<p>CSS is easy to learn and understand but it provides powerful control over the presentation of an HTML document. Most commonly, CSS is combined with the markup languages HTML or XHTML.</P>

- CSS saves time − You can write CSS once and then reuse same sheet in multiple HTML pages. You can define a style for each HTML element and apply it to as many Web pages as you want.

- Pages load faster − If you are using CSS, you do not need to write HTML tag attributes every time. Just write one CSS rule of a tag and apply it to all the occurrences of that tag. So less code means faster download times.

- Easy maintenance − To make a global change, simply change the style, and all elements in all the web pages will be updated automatically.

- Superior styles to HTML − CSS has a much wider array of attributes than HTML, so you can give a far better look to your HTML page in comparison to HTML attributes.

- Multiple Device Compatibility − Style sheets allow content to be optimized for more than one type of device. By using the same HTML document, different versions of a website can be presented for handheld devices such as PDAs and cell phones or for printing.

- Global web standards − Now HTML attributes are being deprecated and it is being recommended to use CSS. So its a good idea to start using CSS in all the HTML pages to make them compatible to future browsers. (https://www.tutorialspoint.com/css/what_is_css.htm)

THE LANGUAGE: SYNTAX AND GRAMMAR
Like any new language, there are new words to learn (the vocabulary) and rules for how these can be put together (the grammar and syntax of the language). (Jon Duckett Javascript and jquery book)

GIVING INSTRUCTIONS: FOR A BROWSER TO FOLLOW
Web browsers (and computers in general) approach tasks in a very different way than a human might. Your instructions need to reflect how computers get things done. (Jon Duckett Javascript and jquery book)


# Decisions and Loops
**Decision** are results of evaluations, you can deicide which path to go down.
![decision pic](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals/cookie-choice-small.png)

**loops** are code that perform the same task multiple times when called upon instead of having to write the code over and over again. 

![loop pic](https://media.geeksforgeeks.org/wp-content/uploads/Loop1.png)
this a basic visual break down of a loop. The condition is ran until the statement becomes false.<br>

<p>Loops are used in JavaScript to perform repeated tasks based on a condition. Conditions typically return true or false when analysed. A loop will continue running until the defined condition returns false.</P>

The three most common types of loops are

- **for** The for loop is used to repeat a section of code known number of times. Sometimes it is the computer that knows how many times, not you, but it is still known.(https://study.com/academy/lesson/for-loop-definition-example-results.html)


- **while** In most computer programming languages, a while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The while loop can be thought of as a repeating if statement.(https://www.cs.utah.edu/~germain/PPS/Topics/while_loops.html)
- **do while**If you recall the way the for and while loops work, you will remember that these loop types check for the loop condition at the beginning of the loop. Unless the condition is satisfied the loop will not be executed. The **do while** loop checks the condition at the end of the loop. This means that the statements inside the loop body will be executed at least once even if the condition is never true. (https://study.com/academy/lesson/do-while-loop-definition-example-results.html)

