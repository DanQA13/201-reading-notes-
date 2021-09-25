# HTML and intro to Javascript
HTML is a markup language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller, and so on. (https://developer.mozilla.org/"html basics")
![HTML logo](https://img-cdn.tnwcdn.com/image?fit=1280%2C720&url=https%3A%2F%2Fcdn0.tnwcdn.com%2Fwp-content%2Fblogs.dir%2F1%2Ffiles%2F2020%2F03%2Fcode-1076536_1920.jpg&signature=2e75357e1e9b104caa33cb3a545dcbeb)

### Basic structure of an HTML document

```
<!DOCTYPE html>
<html>
<head>
<title>Title here</title>
<head>
<body>
Web page content goes here.
<body>
</html>
```
       
       
The basic structure of an HTML document consists of 5 elements:

```
<!DOCTYPE>
<html>
<head>
<title>
<body>
```




* A **DOCTYPE** declaration must be specified on the first line of each web document.

* The **Element**
Immediately following the DOCTYPE declaration is the html element.  The html element tells the browser that the page will be formatted in HTML and, optionally, which language the page content is in.

* The **head** element surrounds all the special behind the scenes elements of a web document.  Most of these elements do not get displayed directly on the web page.

* The **Title** element defines what text will show in the web browser’s title bar:

* The **body** element surrounds all the actual content (text, images, videos, links, etc.) that will be displayed on our web page.

# Extra Markup

Extra markup is a set of elements that perform certain tasks within HTML some examples of extra markup are.

- Comments in HTML
- ID Attribute
- Class Attribute
- Block Elements
- Inline Elements
- Grouping Block Elements
- Grouping Inline Elements
- iFrames
- Meta

Some attributes of extra markup are grouping text together, emphasizing elements within the same paragraph and framing images and text.  In other words **extra markup** is another set of tools to help you develope a good looking HTML page.

# HTML5 Layout 

![HTML 5 logo](https://www.freepnglogos.com/uploads/html5-logo-png/html5-logo-file-html-logo-black-svg-wikimedia-commons-1.png)


HTML5 gives you a set of tools to allow you to divide up parts of the page. The name of the elements indicate the type of content you will find in them. The different elements provide clear code compared to using multiple div elements. "HTML5 was initially released in 2008 by the W3C. W3C (the World Wide Web Consortium) is an international organization that developed this markup language with the objective of improving web accessibility and functionality." (https://www.seobility.net/en/wiki/HTML5)

Below is a basic example of HTML


```
<!DOCTYPE html
<html lang="en">
<head>
 <title>Title of the document</title>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```





# Process and Design 

Process and design is a way to approach building a website. Just like a cookbook lays out the steps of making a recipe. Process and design is a similar way of understanding and building a way of making a website. 

- The first step in yor cookbook would be understanding who the website id for (who is you target audience).  

- Why people visit your website 

- What your visitors are trying to achieve. 

- What information your visitors need 

- How often people will visit your site.

Once this information is gathered a great way to visualize putting your site information together in a meaningful way so that it flows correctly would be by using site map. The idea of a site map is a diagram that will be used to structure the **information** on your site.  It will show you how pages can be grouped. Wire framing is a way to plan the actual layout and structure of your page. 

![site map](https://d2slcw3kip6qmk.cloudfront.net/marketing/blogs/chart/how-to-make-a-site-map/site_map_example2-700x533.PNG)

## Wire framing 

![wireframe](https://wcs.smartdraw.com/website-wireframe/img/what-is-a-website-wireframe.png?bn=15100111806)

A wireframe is a two-dimensional illustration of a page's interface that specifically focuses on space allocation and prioritization of content, functionalities available, and intended behaviors. For these reasons, wireframes typically do not include any styling, color, or graphics.

Design and process is basically a way of effectively communicating to others your thought and ideas from your head to paper to a good looking informative website. 

# The abc of programming 

![adc](https://www.zenefits.com/workest/wp-content/uploads/2018/05/Screen-Shot-2018-05-24-at-4.24.17-PM-1-e1527204334643-790x321.png)

##  What is a script (A) (C) and how to write one 
A script is a series of instructions that a computer can follow to achieve a goal. Similar to my cookbook reference earlier in the my website. A few steps to follow when writing a script are.   

- Define the goal.

- Design the script. 

- code each step. 


```
<!DOCTYPE html>
<html>
 
        <body>
 
            <h1>code fellows</h1>
            <h2><script> Tag</h2>
            <p id="code"></p>
 
            <!-- html script tag starts here -->
            <script>
                document.getElementById("code").innerHTML =
                                     "Hello students!";
            </script>   
            <!-- html script tag ends here -->
 </body>
 ```
 


 
## How do computers fit in the world around them?

Computers create models of the world around them using data similar to how your senses take in information of your surroundings.  "The models use objects to represent physical things. Objects can have: properties that tell us about the object; methods that perform tasks using the properties of that object; events which are triggered when a user interacts with a computer. (Javascript&JQuery Jon Duckett)