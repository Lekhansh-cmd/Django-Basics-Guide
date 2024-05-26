# Guide for Django Basics

## Everything you need to know to get started 

1. Django is a high-level Python web framework that enables the rapid development of secure and maintainable websites. 
2. It is free and open source.
3. Some of the notable sites that use Django are Dropbox, Instagram, NASA, Mozilla, and Disqus.
4. Django emphasizes reusability of components, also referred to as DRY (Don't Repeat Yourself), and comes with ready-to-use features like login system, database connection and CRUD operations (Create Read Update Delete).

## Advantages of Django
1. COMPLETE: Django follows the "Batteries included" philosophy and provides almost everything developers might want to do "out of the box".
2. VERSATILE: It can work with any client-side framework, and can deliver content in almost any format (including HTML, RSS feeds, JSON, and XML).
3. SECURE: Django helps developers avoid many common security mistakes like, putting session information in cookies where it is vulnerable or directly storing passwords rather than a password hash
4. Django has many useful features and extras to simplify development: Django has adopted Python’s “batteries included” approach — the framework has everything necessary to develop a fully fledged application out of the box.
5. TIME-EFFECTIVE:
* There’s a flexible, well-structured admin panel, better than Laravel or Yii’s, for example.
* It allows you to reuse code from current or other projects (there is also a library of reusable apps, tools, and features).
* It has great templates and forms; they were even copied by other projects.
* It has many out-of-the-box libraries and tools that allow you to assemble a good prototype in record time.
6. DRY and KISS COMPLIANT: Django follows the DRY (Don’t Repeat Yourself) principle, which means you can replace frequently repeated software patterns with abstractions, or use data normalization. This way, you avoid redundancy and bugs. KISS means “Keep It Short and Simple”, among its many variations. In Django, it means simple, easy to read, and understandable code. For example, methods shouldn’t be longer than 40-50 lines.
7. REST FRAMEWORK: The benefits of using Django for web development also include its Representational State Transfer (REST) framework — a popular toolkit for building web APIs. Django’s REST is powerful enough to build a ready-to-use API in just three lines of code.

## How does Django works?
Django follows the MVT design pattern (Model View Template).
MODEL - The data you want to present, usually data from a database.
VIEW - A request handler that returns the relevant template and content - based on the request from the user.
TEMPLATE - A text file (like an HTML file) containing the layout of the web page, with logic on how to display the data

![cupofcode_blog_django_MVT_diagram](https://github.com/Lekhansh-cmd/Django-Basics-Guide/assets/78807364/a918ca29-7006-4248-8ed5-a34f77db7e71)
