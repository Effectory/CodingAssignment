# CodingAssignment

## Case: Questionnaire App

For your Effectory job application, we want you to create a _simple web application_, using the JSON provided to create a questionnaire application, consisting of at least:
- a _front-end application_ that handles user interaction
- one or multiple _API's_ that provide the necessary endpoints for the front end

The user of the web application should be able to:
- See the subjects, questions and answers in the questionnaire
- Give an answer to a question
- Persist their answers on the server

The goal of the assignment is to get an idea of your experience, creativity, and ability to learn, analyse and reason.

## The JSON

In this repository you will find a JSON file called `questionnaire.json`. This JSON contains a datastructure that represents your sample questionnaire. It contains `subjects`, `questions` and `answers`.

We leave it to you to interpret this data in the way you want. Please write down what questions you had about the data and what assumptions you made.

## Tech stack

For the application(s), you can use any language or framework or your choosing, but it is recommended to stay close to Effectory's tech stack, so we get a better understanding of how you fit within our current product portfolio.
More specifically, we suggest you use:
- C# for the API's / backend
- Javascript (framework) for the front-end (preferably Aurelia or Angular)

You can read more about what our Tech Stack contains [here](https://tech.effectory.com/).

## Expectations

Depending on your degree of experience, we would like to see some creative ideas integrated in your application. This is entirely up to you, and you can choose anything you want to enrich your application. Some examples include
- Using event-based messaging to store the answers of the questionnaire
- Making the front-end application a PWA
- Set up a Docker compose file to run and/or deploy your application

Your front-end application should be able to:
- Run and build without errors
- Provide the user with an interface for the questionnaire
- Interact with the API

Your back-end application should be able to:
- Run and build without errors
- Provide the front-end application with the questionnaire data
- Store the questionnaire answers

We are open to any suggestion about how we should host your app when bringing it in production (e.g. an Azure hosted Kubernetes server).

This assignment can be quite some work. You can spend as much time as you want on it, but in the end we expect a sufficient, working solution.
