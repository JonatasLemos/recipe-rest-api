# recipe-rest-api

A **CRUD REST API**  built using **Django REST Framework** which may serve as the **backend** for an **recipe app** or **website**. After authenticating the **user** is able to create food recipes which may contain ingredients, tags and images. The recipes, ingredients or tags can be **created**, **updated**, **deleted**, **listed** and **filtered**. 

###  Tools and best practices
* Test Driven Development
* Docker and Docker Compose
* Github Actions workflows
* Use of docstrings
* Swagger API Documentation

### Steps to execute
    
1. Clone the project

    ``git clone git@github.com:JonatasLemos/recipe-rest-api.git``

2. Check the module **app/app/settings.py** for the env variables missing in **.env**

3. Run **docker compose**

    ``docker compose up``

4. Go to http://localhost:8000/api/docs/ to see the API documentation
