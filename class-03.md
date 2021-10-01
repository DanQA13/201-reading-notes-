# Lists Boxes and Control Flow 
HTML offers web authors three ways for specifying lists of information. All lists must contain one or more list elements. Lists may contain −
```
<ul> − An unordered list. This will list items using plain bullets.
```
```
<ol> − An ordered list. This will use different schemes of numbers to list your items.
```
```
<dl> − A definition list. This arranges your items in the same way as they are arranged in a dictionary. 
```
![list pic](https://cdn.educba.com/academy/wp-content/uploads/2019/07/HTML-List-Styles.jpg.webp)
 
 ```
 Ordered list
 <ol>                                
<li>First item</li>
<li>Second item</li>      
<li>Third item</li>
<li>Fourth item</li>
</ol>
```
 
### Rendered output


1. First item
2. Second item
3. Third item
4. Fourth item

```
Unordered lists
<ul>
<li>First item</li>
<li>Second item</li>
<li>Third item</li>
<li>Fourth item</li>
</ul>
```
### Rendered output
- First item
- second item
- Third item
- Fourth item

```
Nested list
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item
```
### Rendered output
1. First item
2. Second item
3. Third item
    - Indented item
    - Indented item
4. Fourth item

```
Definition lists
<dl>
    <dt>Bread</dt>
    <dd>A baked food made of flour.</dd>
    <dt>Coffee</dt>
    <dd>A drink made from roasted coffee beans.</dd>
</dl>
```
### Rendered output
<dl>
    <dt>Bread</dt>
    <dd>A baked food made of flour.</dd>
    <dt>Coffee</dt>
    <dd>A drink made from roasted coffee beans.</dd>
</dl>

# CSS Boxes

![box pic](https://i5.walmartimages.com/asr/81e055fd-a8ce-4fd7-8d21-333f027b1cdc.e5ce12b170e68e910efea49a608515ab.jpeg?odnHeight=612&odnWidth=612&odnBg=FFFFFF)


In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:


![css box](https://miro.medium.com/max/1130/1*6DrszcyPybYDGziiS9CWdg.png)
 

 Explanation of the different parts:

- Content - The content of the box, where text and images appear
- -Padding - Clears an area around the content. The padding is transparent
- Border - A border that goes around the padding and content
- Margin - Clears an area outside the border. The margin is transparent
The box model allows us to add a border around elements, and to define space between elements. 

### Example of css box code
```
div {
  width: 300px;
  border: 15px solid green;
  padding: 50px;
  margin: 20px;
}
```
(https://www.w3schools.com/css/css_boxmodel.asp)

# Switch statements, Decisions and loops.
![light switch](https://www.thespruce.com/thmb/WaPQpUPdvR9uj-5CSsbQFAlZfr8=/960x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/200526811-001-56a5a63e5f9b58b7d0ddd35e.jpg)

The switch statement evaluates an expression, matching the expression's value to a case clause, and executes statements associated with that case, as well as statements in cases that follow the matching case. A switch statement first evaluates its expression. It then looks for the first case clause whose expression evaluates to the same value as the result of the input expression (using the strict comparison, ===) and transfers control to that clause, executing the associated statements. (If multiple cases match the provided value, the first case that matches is selected, even if the cases are not equal to each other.)

If no matching case clause is found, the program looks for the optional default clause, and if found, transfers control to that clause, executing the associated statements. If no default clause is found, the program continues execution at the statement following the end of switch. By convention, the default clause is the last clause, but it does not need to be so.

The optional break statement associated with each case label ensures that the program breaks out of switch once the matched statement is executed and continues execution at the statement following switch. If break is omitted, the program continues execution at the next statement in the switch statement. The break statement is not required if a return statement precedes it.

```
const expr = 'Papayas';
switch (expr) {
  case 'Oranges':
    console.log('Oranges are $0.59 a pound.');
    break;
  case 'Mangoes':
  case 'Papayas':
    console.log('Mangoes and papayas are $2.79 a pound.');
    // expected output: "Mangoes and papayas are $2.79 a pound."
    break;
  default:
    console.log(`Sorry, we are out of ${expr}.`);
}
```

### output 
"Mangoes and papayas are $2.79 a pound."
(https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)

## Decisions and loops 

Loops offer a quick and easy way to do something repeatedly. There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

The various loop mechanisms offer different ways to determine the start and end points of the loop. There are various situations that are more easily served by one type of loop over the others. There are many different types of loops. Here is a list of the commonly used ones.

for loop

![for loop](https://camo.githubusercontent.com/7839db7c8a449b8362f0f800f8017d65642a1bab3198722036a809a1890568a7/68747470733a2f2f7777772e7475746f7269616c73706f696e742e636f6d2f6a6176617363726970742f696d616765732f666f725f6c6f6f702e6a7067)



## for loop

The statement1 is executed first even before executing the looping code. So, this statement is normally used to assign values to variables that will be used inside the loop.

The statement2 is the condition to execute the loop.

The statement3 is executed every time after the looping code is execute

while loop

![while loop](https://camo.githubusercontent.com/b6ca4f9fe2fb5d6b10e186a5dc32d8fedced06f50759c5c408350e0219c12585/68747470733a2f2f7777772e7475746f7269616c73706f696e742e636f6d2f6a6176617363726970742f696d616765732f7768696c655f6c6f6f702e6a7067)

while condition

## while loop

The “while loop” is executed as long as the specified condition is true. Inside the while loop, you should include the statement that will end the loop at some point of time. Otherwise, your loop will never end and your browser may crash.

do while loop


![while loop](https://camo.githubusercontent.com/290b96e1dcef355a1d0beab7fe774c294cf4df2f69aa3af13186ada0dfaf8770/68747470733a2f2f73747564792e636f6d2f63696d616765732f6d756c74696d616765732f31362f39343263323835662d373666662d346462612d626631622d6334373131303162356334635f73637265656e5f73686f745f323031372d31312d32355f61745f31382e31382e31322e706e67)

do while condtion

## do while

The do…while loop is very similar to while loop. The only difference is that in do…while loop, the block of code gets executed once even before checking the condition.