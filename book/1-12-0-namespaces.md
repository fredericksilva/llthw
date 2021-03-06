<ol class="breadcrumb">
  <li><a href="/">Home</a></li>
  <li><a href="/book/">Book</a></li>
  <li><a href="/book/1-0-0-overview/">Part One: Grokking Lisp</a></li>
  <li class="active">Namespaces, Symbols, Packages, and Systems</li>
</ol>

## Chapter 1.12

# Namespaces, Symbols, Packages, and Systems

> "Every law that was ever written opened up a new way to graft."
> <footer>Robert A. Heinlein, <em>Red Planet</em></footer>

As briefly introduced in previous chapters, Common Lisp is a Lisp-2: that is to say, within any given package, you can use the same symbol to refer to both a function and a variable, if you like, because functions and variables have separate namespaces.  The namespaces for functions and variables are managed by the symbol object itself, which exist within a package.

Obviously, scope is important too.  A symbol inside a function body may not have the same definition as in the top-level.  This is by design---and whenever you use a symbol, it is important to remember dynamic and lexical scope.  Not all enclosing forms introduce a new lexical scope like `defun` does.

So, as you can see, what a symbol happens to mean is highly contextual---and for the most part, the Lisp reader is very good at figuring out which definition of a symbol you happen to mean in any given context.  When you want to stray from the norm, Lisp has tools to help you be more specific.

We will also cover some basic aspects of packaging your Lisp code for the wild, and working with ASDF and the Quicklisp package manager built on top of it.

This chapter will contain exercises on:

* Dynamic and Lexical Scope
* Forms that introduce Lexical Scope
* Function and Variable Namespaces
* First-class Functions
* Symbol Names
* Defining Packages

Extra Credit Exercises (intro material, more detail in Chapter 2.20):

* ASDF and Systems
* The Quicklisp Package Manager

## Exercise 1.12.1

**Dynamic and Lexical Scope, Revisited**

## Exercise 1.12.2

**Implicit Lexical Scope**

## Exercise 1.12.3

**Function and Variable Namespaces, Revisited**

## Exercise 1.12.4

**First-Class Functions**

## Exercise 1.12.5

**Symbol Names**

## Exercise 1.12.6

**Packages**

## Exercise 1.12.7

**More Packages: Nicknames**

## Exercise 1.12.8

**More Packages: Exporting Symbols**

## Exercise 1.12.9

**More Packages: Using Other Packages**

## Exercise 1.12.10

**More Packages: Importing Specific Symbols**

## Exercise 1.12.11

**More Packages: Shadowing-Imports**

## Extra Credit Exercise 1.12.12

**ASDF and Systems**

## Extra Credit Exercise 1.12.13

**ASDF Systems: Dependencies**

## Extra Credit Exercise 1.12.14

**ASDF Systems: Files**

## Extra Credit Exercise 1.12.15

**ASDF Systems: Modules**

## Extra Credit Exercise 1.12.16

**ASDF Systems: Serial mode vs. Dependency Tree**

## Extra Credit Exercise 1.12.17

**The Quicklisp Package Manager**

<ul class="pager">
  <li class="previous"><a href="/book/1-11-0-text-adventure/">&laquo; Previous</a></li>
  <li><a href="/book/">Table of Contents</a></li>
  <li class="next"><a href="/book/1-13-0-simple-web-app/">Next &raquo;</a><li>
</ul>
