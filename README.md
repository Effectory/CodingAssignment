# CodingAssignment

## Case: Survey App

For your Effectory job application, we want you to create a _simple web application_, using the JSON provided to create a survey application, consisting of at least:
- a _front-end application_ that handles user interaction
- one or multiple _API's_ that provide the necessary endpoints for the front end

The user of the web application should be able to:
- See the subjects, questions and answers in the questionnaire
- Give an answer to a question
- Persist their answers on the server

The goal of the assignment is to get an idea of your experience, creativity, and ability to learn, analyse and reason.

## The JSON

In this repository you will find a JSON file called `questionnaire.json`. This JSON contains a datastructure that represents your sample survey. It contains `subjects`, `questions` and `answers`.

We leave it to you to interpret this data in the way you want. Please write down what questions you had about the data and what assumptions you made.

## Tech stack

For the application(s), you can use any language or framework or your choosing, but it is recommended to stay close to Effectory's tech stack, so we get a better understanding of how you fit within our current product portfolio. You can read more about what our Tech Stack contains [here](https://tech.effectory.com/)

## Expectations

Depending on your degree of experience, we would like to see some creative ideas integrated in your application. This is entirely up to you, and you can choose anything you want to enrich your application. Some examples include
- Using event-based messaging to store the answers of the questionnaire
- Making the front-end application a PWA

For local development we recommend you set up a Docker compose file to run your application. We want to be able to run your application by calling `docker-compose build`.

We are open to any suggestion about how we should host your app when bringing it in production (e.g. an Azure hosted Kubernetes server).
