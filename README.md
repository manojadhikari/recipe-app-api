<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/6wj0hh6.jpg" alt="Project logo"></a>
</p>

<h3 align="center">Recipe App Api</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]() 
  [![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> A virtual Recipe box to help you organize your favorite recipes by title, ingredients, cookingtime, tags, and image
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](../TODO.md)
- [Contributing](../CONTRIBUTING.md)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>
This is a fully functioning REST API that was developed using Test Driven Development approach. It provides services for authenticating users, creating objects, data filtering, and uploading images. This API is built using Python 3.7 and Django as a web framework. It also uses Django REST Framework for features such as authentication and serialization. In order to ensure a consistent dev environment, this API was developed using a virtualization tool called Docker. In addition, this project is integrated with Travis-CI and is tested automatically everytime a new push is made to github. Finally, it uses postress as its database.

## 🏁 Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites
To follow the installation instructions you need a Linux system. For runnining on windows, some steps may be different.

### Installing
1. Clone the project on your machine
2. Use virtual environment(Optional)
3. Navigate to the root directory of project and install required packages: ```pip install -r requirements.txt```
4. <a href='https://docs.docker.com/docker-for-mac/install/'> Install Docker </a>
5. Run the python server locally: ```docker-compose run app sh -c "python manage.py runserver"```

## 🔧 Running the tests <a name = "tests"></a>
To run tests type ```docker-compose run app sh -c "python manage.py test"```

### How tests are set up
Each app (subfolder within main folder) contains its own folder of tests. These tests drive the implementation of associated model, views, urls, and serializer files. For example if you navigate to the file ```app/user/tests/test_user_api.py``` you can see the test for creating and authenticating users and updating user profile. All models are defined in the ```models.py``` file in the core app. 
Explain what these tests test and why


## ⛏️ Built Using <a name = "built_using"></a>
- [Postgress](https://www.postgresql.org/) - Database
- [Python](https://expressjs.com/) - Programming Language
- [Django](https://www.djangoproject.com/) - Web Framework
- [Django REST Framework](https://www.django-rest-framework.org/) - REST Framework
- [Docker](https://www.docker.com/) - Virtualization Tool
- [Travis CI](https://travis-ci.org/) - Integration Service

## ✍️ Authors <a name = "authors"></a>
- [@manojadhikari](https://github.com/manojadhikari) - Idea & Initial work

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- Hats off to Stack Overflow & Google
