# PeopleManager API

[![Author](https://img.shields.io/badge/author-GuilhermeRodrigues-11BC83?style=flat-square)](https://github.com/iamgrodrigues)
[![Languages](https://img.shields.io/github/languages/count/iamgrodrigues/peoplemanager-api?color=11BC83&style=flat-square)](#)
[![Stars](https://img.shields.io/github/stars/iamgrodrigues/peoplemanager-api?color=11BC83&style=flat-square)](https://github.com/iamgrodrigues/peoplemanager-api/stargazers)
[![Forks](https://img.shields.io/github/forks/iamgrodrigues/peoplemanager-api?color=11BC83&style=flat-square)](https://github.com/iamgrodrigues/peoplemanager-api/network/members)
[![Contributors](https://img.shields.io/github/contributors/iamgrodrigues/peoplemanager-api?color=11BC83&style=flat-square)](https://github.com/iamgrodrigues/peoplemanager-api/graphs/contributors)

> A Rest API that helps you to manage people register :rocket:

<p align="center">
  <img align="center" src="https://i.ibb.co/6s7NVDv/People-Manager-API.png" alt="Web-Signin" border="0">
</p>


# :pushpin: Table of Contents

* [Features](#rocket-features)
* [Requirements](#requirements)
* [Installation](#construction_worker-installation)
* [Getting Started](#runner-getting-started)
* [FAQ](#postbox-faq)
* [Found a bug? Missing a specific feature?](#bug-issues)
* [Contributing](#tada-contributing)
* [License](#closed_book-license)

# :rocket: Features

- CREATE 
- READ 
- UPDATE 
- DELETE 

Sample Valid JSON Request Bodys

Create -> ```/api/v1/people```

```json
[
  {
    "id": 1,
    "firstName": "Guilherme",
    "lastName": "Rodrigues",
    "cpf": "369.333.878-79",
    "birthDate": "24-03-1990",
    "phones": [
      {
        "id": 1,
        "type": "MOBILE",
        "number": "(11)999999999"
      }
    ]
  }
]
```
[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=PeopleManagerAPI%20API&uri=https%3A%2F%2Fgithub.com%2Fiamgrodrigues%2Fpeoplemanager-api%2Fblob%2Fmaster%2F.github%2Fdocs%2PeopleManager-API.json)
# Requirements

For building and running the application you need:

- [JDK 11](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Maven](https://maven.apache.org)

# :construction_worker: Installation

To install this application, run the following commands:

```git clone https://github.com/iamgrodrigues/peoplemanager-api.git```

If you have a SSH key registered in your Github account, clone the project using this command:

```git clone git@github.com:iamgrodrigues/peoplemanager-api.git```

# :runner: Getting Started

## Running the application locally

There are several ways to run a Spring Boot application on your local machine. One way is to execute the `main` method in the `one.digitalinnovation.peopleapi.PeopleapiApplication` class from your IDE.

Alternatively you can use the [Spring Boot Maven plugin](https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html) like so:

```shell
mvn spring-boot:run
```
Afeter the above command, you can navigate to following address to see the project up and runnig:

```shell
http://localhost:8080/api/v1/people
```

## Status Codes

PeopleManager returns the following status codes in its API:

| Status Code | Description |
| :--- | :--- |
| 200 | `OK` |
| 201 | `CREATED` |
| 204 | `NO CONTENT` |
| 400 | `BAD REQUEST` |
| 404 | `NOT FOUND` |
| 500 | `INTERNAL SERVER ERROR` |

# :postbox: Faq

**Question:** What are the tecnologies used in this project?

**Answer:** The tecnologies used in this project are [Java](https://www.java.com) + [Spring Boot](https://spring.io).

# :bug: Issues

Feel free to **file a new issue** with a respective title and description on the the [PeopleManager API](https://github.com/iamgrodrigues/peoplemanager-api/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**! Have a look at our [contribution guidelines](https://github.com/iamgrodrigues/peoplemanager-api/blob/master/CONTRIBUTING.md) to find out about the coding standards.

# :tada: Contributing

Check out the [contributing](https://github.com/iamgrodrigues/peoplemanager-api/blob/master/CONTRIBUTING.md) page to see the best places to file issues, start discussions and begin contributing.

# :closed_book: License

Released in 2021.
This project is under the [MIT license](https://github.com/iamgrodrigues/peoplemanager-api/blob/master/LICENSE).

Made with love by [Guilherme Rodrigues](https://github.com/iamgrodrigues) 💚🚀
