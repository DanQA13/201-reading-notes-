# Object Literals and Document Object Model

![OBpic](https://www.mayanovarini.com/wp-content/uploads/2018/02/object-2.png)

<p>Objects in JavaScript, just as in many other programming languages, can be compared to objects in real life. The concept of objects in JavaScript can be understood with real life, tangible objects.

In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.</p>

<p>A JavaScript object has properties associated with it. A property of an object can be explained as a variable that is attached to the object. Object properties are basically the same as ordinary JavaScript variables, except for the attachment to objects. The properties of an object define the characteristics of the object. You access the properties of an object with a simple dot-notation:</p>

Below is an example of and object

```
Let Car = {
name = 'lambo'
cylinders = 12,
seats = 2,
lambo = true,
options = ['navigation', 'dvd','premium sound','remote start' ]
CheckCarsWoptions: function(){
    return this.lambo && this.options;
}
```
This object would be for a dealer that was looking for a specific lambo with the options listed above. 
Objects have "variables" called keys and their values called values, together they form a key value pair. For example the object above has a few keys and next to them are there values. A value can be a 'string', number, boolean or an array. 
- Name = lambo
- Cylinders = 12
- seats = 2
- lambo = true
- options = ['navigation', 'dvd' ,'premium sound','remote start' ]

What you do with these key value pairs or how you access them is up to your imagination. They are usually accessed with a function. But within an object a function is called a method. 
```
CheckCarsWoptions: function(){
    return this.lambo && this.options;
```
This function or 'method' accesses the info in the object by checking if the key Lambo and the key options are true. 

![lambo](https://pictures.dealer.com/l/lamborghinidallas/0770/15a62b1fe548c4a64ab83524b542a1b1x.jpg?impolicy=resize&w=768)

# Document Object model (DOM)

![DOM](https://a.ilovecoding.org/thumb/dom.png)

The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

A web page is a document that can be either displayed in the browser window or as the HTML source. In both cases, it is the same document but the Document Object Model (DOM) representation allows it to be manipulated. As an object-oriented representation of the web page, it can be modified with a scripting language such as JavaScript.

In the Document Object Model, documents have a logical structure which is very much like a tree; to be more precise, it is like a "forest" or "grove" which can contain more than one tree. However, the Document Object Model does not specify that documents be implemented as a tree or a grove , nor does it specify how the relationships among objects be implemented in any way. In other words, the object model specifies the logical model for the programming interface, and this logical model may be implemented in any way that a particular implementation finds convenient. 

In this specification, we use the term structure model to describe the tree-like representation of a document; we specifically avoid terms like "tree" or "grove" in order to avoid implying a particular implementation. One important property of DOM structure models is structural isomorphism: if any two Document Object Model implementations are used to create a representation of the same document, they will create the same structure model, with precisely the same objects and relationships.

The name "Document Object Model" was chosen because it is an "object model" is used in the traditional object oriented design sense: documents are modeled using objects, and the model encompasses not only the structure of a document, but also the behavior of a document and the objects of which it is composed. In other words, the nodes in the above diagram do not represent a data structure, they represent objects, which have functions and identity. As an object model, the Document Object Model identifies:

- The interfaces and objects used to represent and manipulate a document
- The semantics of these interfaces and objects - including both behavior and attributes
- The relationships and collaborations among these interfaces and objects

The structure of SGML documents has traditionally been represented by an abstract data model, not by an object model. In an abstract data model, the model is centered around the data. In object oriented programming languages, the data itself is encapsulated in objects which hide the data, protecting it from direct external manipulation. The functions associated with these objects determine how the objects may be manipulated, and they are part of the object model.

The Document Object Model currently consists of two parts, DOM Core and DOM HTML. The DOM Core represents the functionality used for XML documents, and also serves as the basis for DOM HTML. All DOM implementations must support the interfaces listed as "fundamental" in the Core specification; in addition, XML implementations must support the interfaces listed as "extended" in the Core specification. The Level 1 DOM HTML specification defines additional functionality needed for HTML documents.

## What the dom is not.

What DOM is not? 

- The Document Object Model is not a binary description where it does not define any binary source code in its interfaces.
- The Document Object Model is not used to describe objects in XML or HTML whereas the DOM describes XML and HTML documents as objects.
- The Document Object Model is not represented by a set of data structures; it is an interface that specifies object representation.
- The Document Object Model does not show the criticality of objects in documents i.e it doesn’t have information about which object in the document is appropriate to the context and which is not.

(https://codescracker.com/js/js-dom-levels.htm)
(https://www.w3.org/TR/DOM-Level-3-Core/introduction.html)
(https://www.geeksforgeeks.org/)