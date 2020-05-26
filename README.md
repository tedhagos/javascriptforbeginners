**Contents**
* TOC
{:toc}

# Overview


# Basic Dev Environment

There are plenty of ways to setup a development environment for learning JS, here are some options;
* Use the VM engine of whatever (modern) browser you have. Chrome, Edge, FireFox and Opera all have modern VM engines that's more than sufficient for your playground
* Use online code-editors/environments like CodePen, JSBin, JSFiddle, Scrimba and many others
* Install a local development stack; a runtime enviroment (Node), a capable editor (Visual Studio Code, or whatever editor you feel comfortable with), a JS linter etc.

For purposes of learning JS basics, an online code-editor/environment will do.

# Typographic convention

When I mark certain parts of the text like this

*Example. How to generate package.json*
```
npm init -y
```

That means you need to type it in a command line.

When I'm referring to a piece of code that you need to type in a program files (JS files), I will mark it like this

*Listing. hello.js*

```javascript
console.log("Hello JS")
```

Or, sometimes, I may omit the *Listing label* and simply refer to the code, like this

```
console.log("Hello JS")
```

# Introduction and the Hello World program

A JS program, like many programs, are written in a source file, then ran on some sort of runtime. There are many runtime environments for JS, but the most popular is probably the V8 engine from Google. This is the same V8 engine that's inside Chrome, Safari and now Microsoft Edge. 

You can run some JS programs using a REPL (Read Eval Print Loop) which you can find in most browsers or a NodeJS environment, but that's not what we will use for the following examples. 

JS is interpreted (not compiled). When you write an executable statement in a program file, the runtime will execute whatever you wrote first. So, if you created a source file named **hello.js** and wrote the following;

_Listing. filename: hello.js_ 

```javascript
// filename: hello.js
/* 
  This is our first JS program
*/

console.log("Hello World)
```

Unlike Java, C/C++ or C#, JS does not need a main function. Simply write your statements one after another, and it will be executed in the same sequence as you wrote it. 

**Point of clarification**: The runtime will execute top-level statements. Statements that are inside functions, will be ignored. If you want to execute the statements inside any function, you have to call that function.

# Language elements

**Statements and expressions**

Expressions are built by combining operands and operators. The operands can be variables, function calls, literals etc.; for example

*Listing. example expression*
```
4 + 4
```

Expressions results in a value. 

A statement is a line of complete instruction to the interpreter. Statements are built with expressions. Statements don't (usually) result to a value. For example

Listing. example statement

```
var num = 4 + 4
```

Statement in JS may or may not be terminated by a semicolon; whether you use on or not is a matter of convention for you (or your team)

**Comments**

Comments are ignored by the interpreter. They're a good way of documenting the intentions and thought processes in the code. You can write comment using the double forward slash like this

*Listing. same line comment*

```
var num = 10 // this is a comment
```

Everything to the right of `//` are ignored

You can also write a comment that spans multi-lines, like this

*Listing. multiline comment*

```
/*
  This comment spans multiple
  lines.
  
  This is good for explaining the thought processes for certain
  passages in your code

*/
```

Everything in between the `/* */` are ignored

**Variables**

To store values for later use, we use variables. Variables JS are generally declared like this

```javascript
var lastname = "Doe"
var firstname = "John"
```

**var** is a special word in JS. You use it when you want to declare a variable. JS variables don't have a type; meaning, you don't have to say what kind of variable is *lastname* or *num*. JS will infer what kind of variable you're declaring and it will act accordingly. JS infers the type of variable and it does this automatically for us; this is why programmers refer to JS as "dynamically typed". 

JS variables are also "malleable"; my meaning of malleability is best illustrated in code, like this

```
var lastname = "Doe"
var firstname = "John"

// some statements

lastname = 10 // JS won't complain. It looks weird, but it's legit
```

In JS, you can declare a variable having an intial type of Number, then later in the code, you can completely change its type to something else (a String, like in our example above)

**Naming your variables**

Some rules to observe when naming your variables
1. Use alphanumeric characters
2. Avoid special characters
3. Don't use numbers as the first letter
4. Don't use JS keywords for variable names

**JS Keywords**

These are the keywords in JS:

**break, case, catch, continue, debugger, default, delete, do, else, finally, for, function, if, in, instanceof, new, return, switch, this, throw, try, typeof, var, void, while**, and **with**

**Operators**

http://lib.ru/JAVA/javascr/expr.html

**Blocks**

**Literals**

**Objects**

**Functions**


# Types/Values

* **Numbers** like 10, 43.2 or 3.1416
* **Logical** (Boolean) like true or false
* **Strings** like "John Doe" or "Hello World"
* **Null** this is a special keyword denoting a null value
* **Objects** everything else is an object; an array is an object, a function is an object. Loosely speaking, a JS object is a collection of data that's in key-value format, like this

```
{
  "name" : "John Doe",
  "email": "jdoe@gmail.com"
}
```

# If else


# Switch


# Loops


# Common built-in functions


# Some more words on Functions


# Basic DOM management


# Resources

1. [Mozilla Development Network/JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

