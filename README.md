Secrets of the JavaScript Ninja Lab 1
===

> NOTE: This lab follows examples in the book and is
> by no means my own work only my interpretation of the content.
>
> In order to move between the steps, you can checkout individual steps
> for instance:
>
> > git checkout -f step-1
>
> checks out the commit pertaining to step-1. Git will mention that HEAD
> is now operating in a detached state, but that's OK. As we continue 
> through the lab, we'll continually check out different steps and it will
> remove all changes made by you during the lab so feel free to experiment!
>
> If you'd really like to save your changes, you can checkout a new branch:
>
> > git checkout -b branchToSaveWork
>
> and commit your changes on that branch (you can change to that branch at some later time
> with your previous work saved)
>
> Finally to return HEAD to its former state, simply checkout the branch we
> started on:
>
> > git checkout master

The lab is composed of the following steps:
---

# step-0

* Consists of a simple, cross-browser implementation of a logging function
* This function initially exists in the main.html file in a script tag

# step-1

* Moves the previous log function out of main.html and into log.js
* This step focuses on a simple assert statement used for creating tests
* Here we'll begin emphasizing testing as a means of making strong, cross-browser JS

# step-2

* Now we advance the idea of the simpler assertion into a full-fledged test suite
* Assertions are now grouped into tests which pass or fail based on their sub assertions
* Additonally it develops a sense of logical grouping for related tests

# step-3

* Finally we conclude with taking our previous test runner and allow it to handle asynchronus testing
* This section demonstrates the fundamentals of handling asynchronus events
