---
layout: essay
type: essay
published: true
title: Understanding Design Patterns
date: 2021-04-29
labels:
   -Design Pattern
   -Software Development
---

Software design began decades ago. Soon after that, developers noticed within their code that certain kinds of designs fail and pass.  Various people were having similar issues, and it didn't take long to recognize the pattern. Ultimately, different design patterns are created to resolve the recurring problems by providing templates and making problem-solving more straightforward and efficient. 

## What are Design Patterns?  
Developers have been working on application designs for years and more likely came across common design challenges while working. As a result, they decided to create design patterns to overcome those kinds of recurring issues. Design patterns make it easier for developers to develop and maintain their applications by providing features such as reusability, time efficiency, and many more. Design patterns do not necessarily solve every problem but provide a foundation for how to solve a problem. In other words, it provides a starting point to solve the problem; therefore, it is considered a best practice to use design patterns in software development.  However, developers shouldn't overlook the cons of design patterns. Poorly designed patterns could make life difficult for developers. 

## My experience using Design Patterns
   For the [project "RateMyClasses"](https://rate-my-classes-manoa.github.io/) that my team and I are currently working on, we're using different design patterns for efficiency. Our project uses Meteor and Javascript, and the few design patterns we're using are listed below. 
   
1) Observer: This pattern notifies the component to change its state and re-render when there are changes on the publication.

2) Prototype: This pattern creates a new object by cloning an existing object class instance.  

3) Singleton: We use a singleton pattern to initialize the mongo collection to create the only instance of the collection.

4)MVC: We use MVC to organize our code and distribution of behaviors. The model contains database- mongo in our case, the view is for user interface- react in our case, and finally, we use react-router for the controller.  

 Patterns provide the way to think about how an application works. Understanding how an application works make it way easier to debug and fix issues within the application. So we shouldn't overlook the benefits of using good design patterns. 
