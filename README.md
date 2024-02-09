# Backend clone  of social media app by using FastAPI

Welcome to the FastAPI Social Media Backend Clone project! This project aims to provide a full-fledged API for a social media application using FastAPI, a modern, fast (high-performance) web framework for building APIs with Python 3.7+.

### Features

- **API Routes:** Define endpoints for user registration, authentication, posting, following, and more.
- **Serialization/Deserialization:** Serialize and deserialize data to/from JSON format.
- **Schema Validation:** Ensure data consistency and validity with Pydantic models.
- **Database Integration:** Utilize SQL for data persistence.
- **Testing with pytest:** Write test cases to ensure the functionality and reliability of the API.
- **CI/CD Pipeline:** Automate the testing and deployment process using GitHub Actions.

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7 or higher installed on your system.
- Basic understanding of RESTful API concepts.
- Familiarity with SQL databases.
- Optional: GitHub account for utilizing GitHub Actions for CI/CD.




# how to run locally
First clone this repo by using following command
````
git clone my_github_repo_link

````
then 
````

cd fastapi-course

````

Then install fastapp using all flag like 

````

pip install fastapi[all]

````

Then go this repo folder in your local computer run follwoing command
````

uvicorn main:app --reload

````

Then you can use following link to use the  API

````

http://127.0.0.1:8000/docs 

````

## After run this API you need a database in postgres 
Create a database in postgres then create a file name .env and write the following things in you file 

````
DATABASE_HOSTNAME = localhost
DATABASE_PORT = 5432
DATABASE_PASSWORD = passward_that_you_set
DATABASE_NAME = name_of_database
DATABASE_USERNAME = User_name
SECRET_KEY = 09d25e094faa2556c818166b7a99f6f0f4c3b88e8d3e7 
ALGORITHM = HS256
ACCESS_TOKEN_EXPIRE_MINUTES = 60(base)



