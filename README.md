# Angular-Large-Scale-Application-Architecture
Advanced architecture and guidelines to create large-scale Angular applications.

**Types of architect**

| Architect type | Strategic thinking | System interactions | Communication | Design
| ------ | ------ | ------ | ------ | ------
| [enterprise architect](https://en.wikipedia.org/wiki/Enterprise_architect "Enterprise architect") | across projects | highly abstracted | across organization | minimal, high level
| [solutions architect](https://en.wikipedia.org/wiki/Solutions_architect "Solutions architect") | focused on solution | very detailed | multiple teams | detailed
| [application architect](https://en.wikipedia.org/wiki/Application_architect "Application architect") | component re-use, maintainability | centered on single application | single project | very detailed

[Source] https://en.wikipedia.org/wiki/Software_architect

**Run towards the Goal**

Our main goal is used to have something that's easy to develop, maintian and test. If we are able to achieve this on planned duration, then our application is going to be future proof as well.

Most of us think how to start architecture & designing new large scale project / re-design exisiting project to new technology. 

Here I am going share my knowledge on architect of Large Scale Web Application using Angular.

As web technology growing fast now a days (Javascript), we need to adpot to the technology growth.

https://differential.com/insights/behind-the-explosive-growth-of-javascript/

# How and where to start?

Most of us think how to start architecture & designing for new large application / re-design exisiting application to new technology. 

* Understand the product / application which we are going to design. 

**Ask yourself more question and find the answers**

    1. Why this product?
    2. What this product will do for customer?
    3. How to make customer life easier by using this product?
    4. How to integrate this product with other vendor?
    5. Whether are we using right technology?
    6. Whether this product will be a application or framework?
    7. What are the Functional Requirements?
    8. What are the Non Functional Requirements?
    9. How easy to maintain the product?
    10. How easy to migrate the product?
    
If you are satisfied with your answers, then we can move to the next stage.
