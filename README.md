# YYJLocalsforLocals
### YYJLocalsForLocals is a group of community-minded tech and marketing professionals offering pro-bono assistance to local small businesses, restaurants, and bars.

Victoria is such a great place to live because of the amazing restaurants, bars, breweries, coffee shops, and unique local retailers. The overall goal of the project is to help make sure that when this is over and everyone is safe and healthy, all those great places will still exist.

To get work out quickly, YYJLocalsForLocals offers eight main services, listed below. Any small business in the area can request one of these services through the website located at yyjlocalsforlocals.com.

Some of our pro-bono services:

* Help designing merch to drive sales
* Building a single page website (landing page)
* Write a message about how your business is handling COVID-19
* Email design to send to your customers
* Social media post or ad copy & design
* Help setting up gift card sales on your website
* Marketing help to promote your delivery service
* Help setting up a subscription box service 

## Contact
For press inquiries, please contact yyjlocalsforlocals@gmail.com. 

## Quick start
* Clone GitHub Repo: `$ git clone https://github.com/yyjlocalsforlocals/yyjlocalsforlocals.git`
* Switch to project root: `$ cd yyjlocalsforlocals/`
* Build the images: `$ docker-compose build`
* Run the containers: `$ docker-compose up -d`
* Create the database: `$ docker-compose exec users python manage.py recreate_db`
* Seed the database: `$ docker-compose exec users python manage.py seed_db`


## File Structure
#### Within the download you'll find the following directories and files:
```
├── .gitignore
├── .gitlab-ci.yml
├── Dockerfile.deploy
├── README.md
├── docker-compose.yml
├── makefile
├── release.sh
└── services
    ├── client
    │   ├── .dockerignore
    │   ├── .eslintrc.json
    │   ├── .gitignore
    │   ├── Dockerfile
    │   ├── Dockerfile.ci
    │   ├── README.md
    │   ├── coverage
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── public
    │   │   ├── favicon.ico
    │   │   ├── index.html
    │   │   ├── logo192.png
    │   │   ├── logo512.png
    │   │   ├── manifest.json
    │   │   └── robots.txt
    │   └── src
    │       ├── App.jsx
    │       ├── components
    │       │   ├── About.jsx
    │       │   ├── AddUser.jsx
    │       │   ├── LoginForm.jsx
    │       │   ├── Message.jsx
    │       │   ├── NavBar.css
    │       │   ├── NavBar.jsx
    │       │   ├── RegisterForm.jsx
    │       │   ├── UserStatus.jsx
    │       │   ├── UsersList.jsx
    │       │   ├── __tests__
    │       │   │   ├── About.test.jsx
    │       │   │   ├── AddUser.test.jsx
    │       │   │   ├── App.test.jsx
    │       │   │   ├── LoginForm.test.jsx
    │       │   │   ├── Message.test.jsx
    │       │   │   ├── NavBar.test.jsx
    │       │   │   ├── RegisterForm.test.jsx
    │       │   │   ├── UserStatus.test.jsx
    │       │   │   ├── UsersList.test.jsx
    │       │   │   └── __snapshots__
    │       │   │       ├── About.test.jsx.snap
    │       │   │       ├── AddUser.test.jsx.snap
    │       │   │       ├── App.test.jsx.snap
    │       │   │       ├── LoginForm.test.jsx.snap
    │       │   │       ├── Message.test.jsx.snap
    │       │   │       ├── NavBar.test.jsx.snap
    │       │   │       ├── RegisterForm.test.jsx.snap
    │       │   │       ├── UserStatus.test.jsx.snap
    │       │   │       └── UsersList.test.jsx.snap
    │       │   └── form.css
    │       ├── index.js
    │       └── setupTests.js
    └── users
        ├── .coverage
        ├── .coveragerc
        ├── .dockerignore
        ├── .flake8
        ├── Dockerfile
        ├── Dockerfile.prod
        ├── entrypoint.sh
        ├── htmlcov
        ├── manage.py
        ├── project
        │   ├── __init__.py
        │   ├── .isort.cfg
        │   ├── api
        │   │   ├── __init__.py
        │   │   ├── auth.py
        │   │   ├── ping.py
        │   │   └── users
        │   │       ├── __init__.py
        │   │       ├── admin.py
        │   │       ├── crud.py
        │   │       ├── models.py
        │   │       └── views.py
        │   ├── config.py
        │   ├── db
        │   │   ├── Dockerfile
        │   │   └── create.sql
        │   └── tests
        │       ├── __init__.py
        │       ├── conftest.py
        │       ├── pytest.ini
        │       ├── test_admin.py
        │       ├── test_auth.py
        │       ├── test_config.py
        │       ├── test_ping.py
        │       ├── test_user_model.py
        │       ├── test_users.py
        │       └── test_users_unit.py
        ├── requirements-dev.txt
        ├── requirements.txt
        └── setup.cfg
```

## Common Commands
### Docker Compose
#### Set the `REACT_APP_USERS_SERVICE_URL` environment variable:
```$ export REACT_APP_USERS_SERVICE_URL=http://localhost:5001```

#### Build the images:
```$ docker-compose build```

#### Build and spin up the new containers:
```$ docker-compose up -d --build```

#### To stop the containers:
```$ docker-compose stop```

#### To bring down the containers:
```$ docker-compose down```

### Client
#### Run the tests without coverage:
```$ docker-compose exec client npm test```

#### Run the tests with coverage:
```$ docker-compose exec client npm test --coverage```

#### Check formatting with Prettier:
```$ docker-compose exec client npm run prettier:check```

#### Lint with eslint:
```$ docker-compose exec client npm run lint```

### Server
#### Create the database:
```$ docker-compose exec users python manage.py recreate_db```

#### Seed the database:
```$ docker-compose exec users python manage.py seed_db```

#### Run the tests without coverage:
```$ docker-compose exec users python -m pytest "project/tests" -p no:warnings```

#### Run the tests with coverage:
```$ docker-compose exec users python -m pytest "project/tests" -p no:warnings --cov="project"```

#### Lint with Flake8:
```$ docker-compose exec users flake8 project```

#### Run Black and isort with check options:
```$ docker-compose exec users black project --check```

```$ docker-compose exec users /bin/sh -c "isort project/**/*.py --check-only"```

#### Make code changes with Black and isort:
```$ docker-compose exec users black project```

```$ docker-compose exec users /bin/sh -c "isort project/**/*.py"```

### Postgres
#### Want to access the database via psql?
```$ docker-compose exec users-db psql -U postgres```

##### Then, you can connect to the database and run SQL queries. For example:
```# \c users_dev```
```# select * from users;```

### Other Commands
#### Want to force a build?
```$ docker-compose build --no-cache```

#### Remove images:
```$ docker rmi $(docker images -q)```
