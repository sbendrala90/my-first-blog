**Table of Contents**

[TOCM]

[TOC]

## My First Web Application using Python Django Framework

- This is my First Application in Python Django using Amazon Cloud 9 IDE 
- [Reference](https://tutorial.djangogirls.org/en/ )
- Django is a free and open source web application framework, written in Python. A web framework is a set of components that helps you to develop websites faster and easier.
- A framework is nothing more than a collection of modules that make development easier. They are grouped together, and allow you to create applications or websites from an existing source, instead of from scratch.


## Principles of Django Framework
### Don't repeat yourself (DRY) principle :
- Repetition might be good to emphasize a point, but when it comes to web development, it just leads to additional and time consuming work. In fact, the very nature of web development, which operates across multiple-tiers interacting with one another (e.g. HTML templates, business logic methods and databases) lends itself to repetition.
### Explicit is better than implicit
- Being explicit leads to web applications that are easily understood and maintained by a greater number of people. Adding new features or understanding the logic behind a web application can be hard enough for someone that didn't write it originally, but if you toss into the mix constructs that have implicit behaviors, users only face greater frustration trying to figure out what's being done implicitly. Explicit does require a little more work typing, but it's well worth it when you compare it to the potential effort you can face trying to debug or solve a problem.

###Loosely coupled architecture
- The Django framework being an MVC framework operates across multiple tiers (e.g. HTML templates, business logic methods and databases). However, Django takes great care of maintaining a loosely couple architecture across all the components that operate across these tiers.
- Being loosely coupled means there are no rigid dependencies between the parts that make up a Django application. For example, in Django it's perfectly valid to serve content directly from an HTML template, without the need to use business logic or set up database. Just like in Django it's also perfectly valid to forgo using an HTML template and return raw data directly from a business logic method (e.g. for a REST service).

##MVC Architecre

![](https://www.tutorialspoint.com/django/images/django_mvc_mvt_pattern.jpg)

- **The model(M):** is a model or representation of your data. It’s not the actual data, but an interface to the data. The model allows you to pull data from your database without knowing the intricacies of the underlying database. The model usually also provides an abstraction layer with your database, so that you can use the same model with multiple databases.
- **The view(V)** is what you see. It’s the presentation layer for your model. On your computer,
the view is what you see in the browser for a Web app, or the UI for a desktop app. The view also provides an interface to collect user input.
- **The controller(C)** controls the flow of information between the model and the view. It uses programmed logic to decide what information is pulled from the database via the model and what information is passed to the view. It also gets information from the user via the view and implements business logic: either by changing the view, or modifying data through the model, or both.

References:
1. [Djangogirls](https://tutorial.djangogirls.org/en/ )
2. [Python for Beginners](http://www.pythonforbeginners.com/learn-python/what-is-django/)
3. [Djangobook](https://djangobook.com/model-view-controller-design-pattern/)