---
layout: post
title: Encounter with Java Kind 
---

* The ecosystem of the Java Programming language has never been my forte. In the past three days
I will try to explain some of my understanding into this blog post.

* Lets start with the amount of buzz words in the ecosytem:
1. JAVA_HOME == Enviroment variable in the shell envrionment which points to the JAVA programming language binaries
1. IntelliJ - Preferred IDE for JAVA atleast for now :)
1. Maven - Maven is one of the package manager in your software project.Maven installs all the 
required packages on the project and even compiles all the libraries. The sequence in which compilation needs is also dictated by Maven.
    - Maven dependencies are defined in a file called `pom.xml`.
    - The structure of each dependency is as below:
    
    ```xml
    <dependency>
    <groupId>foo.group</groupId>
    <artifactId>fooId</artifactId>
    </dependency>
    ```
    - Maven downloads all your dependencies in the `/Users/<<user_name>>/.m2/repository/` folder.
    - Java Application might be defined by several modules.
    - For e.g.:-

    - In order for a project... hello
