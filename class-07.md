# Tables

![tablepic](https://flaviocopes.com/html-tables/proper-table.png)
A table in HTML consists of table cells inside rows and columns.
The ```<table>``` HTML element represents tabular data — that is, information presented in a two-dimensional table comprised of rows and columns of cells containing data.
(https://flaviocopes.com/html-tables/)



# JS Constructor Functions
The constructor property returns a reference to the Object constructor function that created the instance object. Note that the value of this property is a reference to the function itself, not a string containing the function's name.
All objects (with the exception of objects created with Object.create(null)) will have a constructor property. Objects created without the explicit use of a constructor function (such as object- and array-literals) will have a constructor property that points to the Fundamental Object constructor type for that object.
```
let o = {}
o.constructor === Object // true

let o = new Object
o.constructor === Object // true

let a = []
a.constructor === Array // true

let a = new Array
a.constructor === Array // true

let n = new Number(3)
n.constructor === Number // true
```


In JavaScript, a constructor function is used to create objects. For example,
```
// constructor function
function Person () {
    this.name = 'John',
    this.age = 23
}

// create an object
const person = new Person();
```
In the above example, function Person() is an object constructor function.

To create an object from a constructor function, we use the new keyword.

