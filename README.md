# CodingAssignment

## Case: Survey App

In this case we want you to create a simple survey web application. 

The user of the web application should be able to:
- See the subjects, questions and answers in the survey
- Give an answer to a question
- Persist his answers on the server

Your project should consist of at least two parts: a front end application that handles user interaction and one or multiple API's that provide the necessary endpoints for the front end.

For local development we recommend you set up a Docker compose file to run your application. We want to be able to run your application by calling `docker-compose build`.

We are open to any suggestion about how we should host your app when bringing it in production (e.g. an Azure hosted Kubernetes server).

The goal of the case is not to create a completely finished and polished application, we want to get an idea of your ability to learn, analyse and reason.

## The JSON

In this repository you can find a JSON file called `questionnaire.json`. This JSON contains a datastructure that represents your survey. It contains subjects, questions and answers.

We leave it to you to figure out how to interpit this data. Please write down what questions you had about the data and what assumptions you made.
