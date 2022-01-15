# Homestead Core

## Introduction

Homestead core is a collection of packages and modules that are used to build an app with Homestead. 

Since homestead is built on top of FastAPI it is possible to use anything from FastAPI, however, there are certain
things that we have overloaded to make FastAPI work better as an app building platform than just an api. 

## The base app

When developing an app with FastAPI you will have to import FastAPI and create an app.  
The same is true for Homestead. However, your app will import Homestead and create a Homestead app.

```python
from homestead import Homestead

app = Homestead()
```

## Routing

Homestead uses FastAPI's routing system to handle requests. We have decided that every route must be contained within a router
to make it possible to automatically import all of your routes for you. This means any router you create will automatically
be registered with the app.

Since Homestead is aimed at building apps as well as APIs we created a new router called `WebRouter` which is a clone of 
FastAPI's `APIRouter` but it overwrites the `include_in_schema` to be false. This means the routes will not be included in
the OpenAPI schema.