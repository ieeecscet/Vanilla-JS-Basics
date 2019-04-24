
# Vanilla Javascript
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/JavaScript-logo.png/480px-JavaScript-logo.pngg" alt="drawing" width="200"/>

#### Introduction:
VanillaJS is a term for library/framework free javascript. 

Its sometimes ironically referred to as a library, as a joke for people who could be seen as mindlessly using different frameworks.

Here's the [official webisite of Vanilla JS]( http://vanilla-js.com/). (Don't bother clicking on the link)

# Why Javascript?:
In fact, there are no many reasons why you should learn JavaScript, that its appeal is obvious:<br> **If programming languages were people, JavaScript would be the *sexy one*.**
- You can get started using JavaScript right now.

    > JavaScript comes installed on every modern web browser, so you can LITERALLY start programming in JavaScript this very second on the very browser that you are using to read this article. If you’re using Google Chrome, for instance, just go to the “View” menu, click on the “Developer” sub-menu, and you’ll see an option to open a JavaScript console. No muss, no fuss.
 - JavaScript can be used to make sites pretty and to build crazy fast servers.

    >It’s not just that JavaScript is so easy to get started with, it’s also that when you DO start using it there is so much it can be used for. Part of what makes JavaScript versatile is that you can use it for front-end AND back-end development. If you’re wondering what that is, front-end development is the work that goes into building the parts of a website users see and interact with, while back-end development is the work that happens “under the hood”—building and managing the servers and databases that power websites behind the scenes. This means two important things for you:


## **And no, it has nothing to do with Java and no prior knowledge of Java is required.**


A decade back, it was just used to annoy people on internet.

<img src="https://upload.wikimedia.org/wikipedia/en/f/f7/RickRoll.png" alt="drawing"/> 

### Now it's much more than that, it has something for everyone.
 

 # >1.Create your first javascript program

Javascript requires an interpreter to execute the code. Every web browser has its own Javascript engine which acts as an interpreter, each with a different name.

>Chrome: V8 engine
>
>Firefox: SpiderMonkey
>
>Internet Explorer/Edge: Chakra

## >1.1.Let's create a html file that gives an alert. 

**1.Open a blank text file in any text editor with its extension as ".html".**

>eg. helloWorld.html

**2.Type the following code**

```
    <!DOCTYPE html>
    <html>
        <head>
            <script>
                alert("Hello World")
            </script>
        <\head>
        <body>
            Just a basic website.
        <\body>
    <\html>

```

**3.Save the file and open it in any browser**

This should be the output:

<img src="./src/scrn.png" width=500/>

You should see a dialog box with the text "Hello World".

*Cool, you just ran your first js script!!*

# 2.Let's create a cool calculator using Javascript!

But first there are few things you should know


## >2.1.Statements

Statements are syntax constructs and commands that perform actions.</br>
We’ve already seen a statement, alert('Hello, world!'), which shows the message “Hello, world!”.

We can have as many statements in our code as we want. Statements can be separated with a semicolon.
```
alert("Hello");
alert("World");
```
Semi colons are optional in Javascript.</br>
This works too:
```
alert("Hello ")
alert("World)
```
Both give the same output which is <br>
> "Hello World".

## >2.2.Comments
It's necessary to add comments in your js programs as the complexity keeps on growing.
To add a coment  use:
> // This is a comment in js

It also allows multi line comments:
```
/*This 
is
a multi
line comment
*/
``` 
## >2.3.Datatypes in JS
There are seven basic data types in JavaScript. But we need not worry about them as JS is __"dynamicaly typed"__ and the variables we define are not bound to any of them.<br>

To declare a variable we use var or let.
> var has a block scope whereas let has function scope.

An example:
```
let a=10 //declaring a variable which stores a number 
a=12.465 //we assign a float number to predefined a
```
The above code will not give you an error.

### >2.3.4.Objects in JS
Object is the most important datatype in JS.
They are used to store keyed collections of various data and more complex entities.<br>
__In JavaScript, objects penetrate almost every aspect of the language. So we must understand them first before going in-depth anywhere else.__

Declaring an object.
```
let obj={
    name:"Vishnu",
    age:20
}
```
Objects in JS are similar to Dictionary in Python. They are basically storing key-value pairs.

To access values we use dot notation: _objectName.key_.
So if I had to access my age from the object, I could just
>alert(obj.name)

For more info [click here](https://javascript.info/object)

## >2.4.Functions
Quite often we need to perform a similar action in many places of the script.

For example, we need to show a nice-looking message when a visitor logs in, logs out and maybe somewhere else.

Functions are the main “building blocks” of the program. They allow the code to be called many times without repetition.

Function declaration in JS:
```
function hello(){
    alert("Hello,This is a function")
    return 1 //Optional
```
__Note that "function" is a keyword and must be used before every function declaration__<br>
And to call a function we,
```
hello()
let temp=hello() //if return is used   
```




## >2.5.Javascript DOM
DOM is short for __Document Object Model__. <br>
According to DOM, every tag inside a HTML document is an object and can be used accessed using Javascript.<br>
\> For example let's explore the DOM of this document:
```
<!DOCTYPE HTML>
<html>
<head>
  <title>About elks</title>
</head>
<body>
  The truth about elks.
</body>
</html>
```
The DOM represents HTML as a tree structure of tags. Here’s how it looks:

<img src="./src/DOM.png" width=500>

Tags are called element nodes (or just elements). Nested tags become children of the enclosing ones. As a result we have a tree of elements: <html> is at the root, then <head> and <body> are its children, etc.

For more info [click here](https://javascript.info/dom-nodes)











