VarsMovies-django-Movie-Web-App.
-----------------------------------
Movie Rating & Review WebApp Using Django displays the latest movies, TV series info, and provides search and personal collection functionality, recommendations

Table of Content
----------------
* Demo
* Overview
* Motivation
* What does Django code look like & its working
* Advantages & Disadvantages
* Installation
* Features/Result
* Future scope of project

DEMO
-------
Link : http://varsmovies.herokuapp.com/

![2020-09-28 (29)_LI](https://user-images.githubusercontent.com/41515202/94376503-8f5d8800-0138-11eb-9c2c-7064753f56e9.jpg)

![2020-09-28 (30)_LI](https://user-images.githubusercontent.com/41515202/94376504-908eb500-0138-11eb-9353-ca8fe945c2be.jpg)

![2020-09-28 (31)_LI](https://user-images.githubusercontent.com/41515202/94376506-91bfe200-0138-11eb-9234-4487abc448ca.jpg)

![2020-09-28 (34)_LI](https://user-images.githubusercontent.com/41515202/94376507-92f10f00-0138-11eb-8d15-d401f4baf0ab.jpg)

![2020-09-28 (35)_LI](https://user-images.githubusercontent.com/41515202/94376508-94223c00-0138-11eb-9178-751eb6081e5d.jpg)


Overview / What is it ??
---------------------------
* A WebApp made in Django which displays the latest movies and TV series info.

* Provides search and personal collection functionality, recommendations, and much more. Provides option with writing reviews and rating for movie

* DJANGO - python high-level backend web framework based on python for building dynamic websites used for rapid development, pragmatic, maintainable, clean design, and secure websites.

* Django provides a dynamic CRUD (create, read, update and delete) interface, configured with admin models and have basic database commands, which means the interface facilitates viewing, changing, and searching for information.

* All functions and components (e.g., HTTP responses are called “views”). It also has an admin panel, which is deemed easier to work ::::
 
* Pre-built authentication, URL routing, a template engine, an object-relational mapper (ORM), and database schema migrations are all included with the Django framework

* Simple syntax;

* Its own web server;

* MVC (Model-View-Controller) core architecture;

* HTTP libraries;

* A Python unit test framework.

Motivation / Why / Reason ???
----------------------------------
* It’s fast and simple & simplify work for developers

* Allow you to quickly and efficiently create a quality Web application, and is suitable for both frontend and backend.

* More fully-featured than many other frameworks out there

* The main goal are simplicity, flexibility, reliability, and scalability

* Allow developers to focus on components of the application that are new instead of spending time on already developed components.

* As a result, it takes a lot less time to get the project to market 7 provide multiple flexible framework which are ::: 

* The principles of rapid development, which means developers can do more than one iteration at a time without starting the whole schedule from scratch;

* DRY philosophy — Don’t Repeat Yourself — which means developers can reuse existing code and focus on the unique one.

* Maintainable ::::::
    encourage the creation of maintainable and reusable code. 
    Makes use of the Don't Repeat Yourself (DRY) principle so there is no unnecessary duplication, reducing the amount of code

* It’s secure ::::
    Security is also a high priority for Django. It has one of the best out-of-the-box security systems out there, and it helps developers avoid common security issues

* Ridiculously fast:::::::: 
    quickly as possible
Scalable:::::

* Portable ::::
    can run your applications on many flavours of Linux, Windows, and Mac OS X. Furthermore, Django is well-supported by many web hosting providers

* Django Admin::::
    very well structured
    comes with a built-in admin interface
    Provide option to customize the admin panel as per your requirements & perform various CRUD operations & allow create, edit and publish content, manage site users, and perform other administrative tasks
    Generating admin sites for your staff or clients to add, change and delete content is tedious work that doesn’t require much creativity. Django entirely automates creation of admin interfaces for models.
    Can authenticate users, display and handle forms, and validate input, all automatically.
    It reads metadata from your models to provide a quick, model-centric interface where trusted users can manage content on your site

* well-established :::: 
    great documentation, the best of any other open-source framework
    big, supportive community accessed through numerous forums, channels, and dedicated websites
    easy to find help when there’s a problematic function in the code 
    Famous companies that use the Django framework -> INSTA, SPOTIFY, MOZILLA, PINTERST

* It suits any web application project :::
    tackle projects of any size and capacity, whether it’s a simple website or a high-load web application
    It’s fully loaded with extras and scalable, so you can make applications that handle heavy traffic and large volumes of information;
    It is cross-platform, meaning that your project can be based on Mac, Linux or PC;
    It works with most major databases and allows using a database that is more suitable in a particular project, or even multiple databases at the same time.



What does Django code look like & its working ??
--------------------------------------------------
•	Traditional website, a web application waits for HTTP requests from the web browser.
When a request is received the application works out what is needed based on the URL and possibly information in POST data or GET data. 
Depending on what is required it may then read or write information from a database or perform other tasks required to satisfy the request. 
The application will then return a response to the web browser, often dynamically creating an HTML page for the browser to display by inserting the retrieved data into placeholders in an HTML template. 

•	Django web applications typically group the code that handles each of these steps into separate files ::::

![image](https://user-images.githubusercontent.com/41515202/94377479-b2d80100-013f-11eb-9bf0-ae750af5a36d.png)

* URLs:::: Sending the request to the right view (urls.py)
URL mapper is used to redirect HTTP requests to the appropriate view based on the request URL. The URL mapper can also match particular patterns of strings or digits that appear in a URL and pass these to a view function as data.

* Models :::::::::: (M)::::: Defining data models (models.py)
are Python objects that define the structure of an application's data, and provide mechanisms to manage (add, modify, delete) and query records in the database.

* View :::::::::::: (V) ::: Handling the request (views.py), Querying data (views.py)
is a request handler function, which receives HTTP requests and returns HTTP responses. Views access the data needed to satisfy requests via models, and delegate the formatting of the response to templates.
* Templates:::::: (T)::::: Rendering data (HTML templates)
is a text file defining the structure or layout of a file (such as an HTML page), with placeholders used to represent actual content. A view can dynamically create an HTML page using an HTML template, populating it with data from a model.

Above -> refers as / Supports  "Model View Template (MVT)" architecture. It has many similarities to the more familiar MVC architecture.

Advantages
-----------
Scalable
Extremely fast
Fully secure
Can work extremely well with operating systems and databases
Support MVT – for faster impletation of project – due to pre-built made in libraries & fold.
well-established 
Portable
Maintainable
Django Admin

Disadvantages
--------------
Does not have the capacity to take care of multiple requests at the same time

Installation /  TECH USED
-------------------------------
Python backend high-level web framework - DJANGO

Features/Result:
-----------------
* A WebApp made in Django which displays the latest movies and TV series info.

* Provides search and personal collection functionality, recommendations, and much more. Provides option with writing reviews and rating for movie

* Rate, review, and track your media (films, series, games, books and music).

* Receive personalized media recommendations based on your ratings, or browse the media database using various filters.

Future Scope
--------------
Can handle more data

can be more optimized & effienct to load pages quickly
