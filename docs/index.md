# Homestead

Homestead is pre-alpha and still in active development.

## What is Homestead

Homestead is beign developed to help developers scaffold and create applications using best in class Python packages.

We are trying to solve the problem of having to setup the basic architecture of a Python web application.  We know everyone loves
FastAPI but setting up a new project can be a pain. You need to setup the folder strucutre, setup a database connection and a list of other things.  
Using Homesteads `craft` command you can scaffold a new project with one cli command and get coding fast.

How about setting up a new endpoint? Homestead is opinionated on how a project is setup and as long as you adhear to the structure defined you can use `craft` to create new modules which will contain a controller. Just choose if you want an api or web controller and we will create a controller that returns a json response or a template using Jinja2 and [fastapi-jinja](https://github.com/AGeekInside/fastapi-jinja).
