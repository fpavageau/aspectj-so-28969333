Examples for [Reading and understanding AspectJ pointcuts?](http://stackoverflow.com/questions/28969333/reading-and-understanding-aspectj-pointcuts)
======

The different branches illustrate the various cases.

## How to compile

The project uses Maven 2+ and Java 8, so just do:

    mvn clean package

and see the results of the test. In master, the test prints:

    Running MainTest
    Before call to void Server.m()
    m()
    Before call to int java.lang.Object.hashCode()

## Feedback welcome!

Add a comment, create an issue, ping me on [Twitter](https://twitter.com/fpavageau)...


------

Licensed under the Apache License, Version 2.0
