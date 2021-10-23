# Forms and Events

An HTML form is used to collect user input. The user input is most often sent to a server for processing. The ```<form>``` Element
The HTML ```<form>``` element is used to create an HTML form for user input

The <input> or ```<input>``` Element
The HTML ```<input>```element is the most used form element.

An ```<input>```element can be displayed in many ways, depending on the type attribute.

Here are some examples:

Type	Description
```<input type="text">	Displays a single-line text input field
<input type="radio">	Displays a radio button (for selecting one of many choices)
<input type="checkbox">	Displays a checkbox (for selecting zero or more of many choices)
<input type="submit">	Displays a submit button (for submitting the form)
<input type="button">	Displays a clickable button
```

# Events 

Events are actions or occurrences that happen in the system you are programming, which the system tells you about so you can respond to them in some way if desired. For example, if the user selects a button on a webpage, you might want to respond to that action by displaying an information box. In this article, we discuss some important concepts surrounding events, and look at how they work in browsers. This won't be an exhaustive study; just what you need to know at this stage

Prerequisites:	Basic computer literacy, a basic understanding of HTML and CSS, JavaScript first steps.


Objective:	To understand the fundamental theory of events, how they work in browsers, and how events may differ in different programming environments.

![plane pic](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events/mdn-mozilla-events-runway.png)

In the case of the Web, events are fired inside the browser window, and tend to be attached to a specific item that resides in it — this might be a single element, set of elements, the HTML document loaded in the current tab, or the entire browser window. There are many different types of events that can occur. For example:

- The user selects a certain element or hovers the cursor over a certain element.
- The user chooses a key on the keyboard.
- The user resizes or closes the browser window.
- A web page finishes loading.
- A form is submitted.
- A video is played, paused, or finishes.
- An error occurs.
You can gather from this (and from glancing at the MDN Event reference) that there are a lot of events that can be responded to.

Each available event has an event handler, which is a block of code (usually a JavaScript function that you as a programmer create) that runs when the event fires. When such a block of code is defined to run in response to an event, we say we are registering an event handler. Note: Event handlers are sometimes called event listeners — they are pretty much interchangeable for our purposes, although strictly speaking, they work together. The listener listens out for the event happening, and the handler is the code that is run in response to it happening.

## It's not just web pages
Another thing worth mentioning at this point is that events are not unique to JavaScript — most programming languages have some kind of event model, and the way the model works often differs from JavaScript's way. In fact, the event model in JavaScript for web pages differs from the event model for JavaScript as it is used in other environments.

For example, Node.js is a very popular JavaScript runtime that enables developers to use JavaScript to build network and server-side applications. The Node.js event model relies on listeners to listen for events and emitters to emit events periodically — it doesn't sound that different, but the code is quite different, making use of functions like on() to register an event listener, and once() to register an event listener that unregister after it has run once. The HTTP connect event docs provide a good example.

You can also use JavaScript to build cross-browser add-ons — browser functionality enhancements — using a technology called WebExtensions. The event model is similar to the web events model, but a bit different — event listeners properties are camel-cased (such as onMessage rather than onmessage), and need to be combined with the addListener function. See the runtime.onMessage page for an example.

You don't need to understand anything about other such environments at this stage in your learning; we just wanted to make it clear that events can differ in different programming environments.