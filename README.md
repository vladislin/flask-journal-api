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


