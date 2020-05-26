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
```
npm init -y
```

That means you need to type it in a command line.

When I'm referring to a piece of code that you need to type in a program files (JS files), I will mark it like this

*Listing. hello.js*

```javascript
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

## Statements and expressions

Expressions are built by combining operands and operators. The operands can be variables, function calls, literals etc.; for example

Listing. example expression
```

```

A statement is a line of complete instruction to the interpreter. Statements are built with expressions. 

## Comments

## Variables

## Operators


## Blocks

## Literals

## Objects

## Functions


# Types



# If else


# Switch


# Loops


# Common built-in functions


# Some more words on Functions


# Basic DOM management


# Resources

1. [Mozilla Development Network/JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

