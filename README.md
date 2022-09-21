Welcome to the documentation for the Flask Journal API!

## Introduction

The Flask Journal API is an API (Application Programming Interface) for creating a **daily journal** that documents events that happen each day.

## Key Functionality

The Flask Journal API has the following functionality:

1. Work with journal entries:
  * Create a new journal entry
  * Update a journal entry
  * Delete a journal entry
  * View all journal entries
2. Work with user and authentication
  * Create a new user
  * Get auth-token

## Key Modules

This project is written using Python 3.9.

The project utilizes the following modules:

* **Flask**: micro-framework for web application development which includes the following dependencies:
  * **click**: package for creating command-line interfaces (CLI)
  * **itsdangerous**: cryptographically sign data
  * **Jinja2**: templating engine
  * **MarkupSafe**: escapes characters so text is safe to use in HTML and XML
  * **Werkzeug**: set of utilities for creating a Python application that can talk to a WSGI server
* **APIFairy**: API framework for Flask which includes the following dependencies:
  * **Flask-Marshmallow** - Flask extension for using Marshmallow (object serialization/deserialization library)
  * **Flask-HTTPAuth** - Flask extension for HTTP authentication
  * **apispec** - API specification generator that supports the OpenAPI specification
* **pytest**: framework for testing Python projects

## Project set up

#### Create clone:
```
 $ git clone https://github.com/vladislin/flask-journal-api.git .
 $ cd flask-journal-api
```

#### Create a virtual environment and activate it:
```
 $ python3 -m venv venv
 
 # linux
 $ source venv/bin/activate
 
 # windows
 $ venv\Scripts\activate
```

#### Install all dependencies from the requirements.txt file:
```
 $ pip install -r requirements.txt
```

#### Start the development server:
```
 $ flask run
```

#### Navigate to http://127.0.0.1:5000/docs#/ to see the API documentation: