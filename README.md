# POLLING SYSTEM API

A simple polling system API where anyone can create questions with options and can also add votes to those options. The project is a simple polling system API that allows developers to create, manage, and retrieve data from a polling platform. Users can create questions with options and collect votes from participants. This API is a versatile tool for integrating polls, surveys, and quizzes into various applications and websites, making it easy to gather valuable feedback and insights from users.
### Hosted Link: https://polling-system-api-x8xt.onrender.com
### Github Repo Link: https://github.com/keerthy97/polling-system-API/tree/master

- Sample Question
  ![question](./images/view_question.png)

## Requirements

- Install [Node.js](https://nodejs.org/en/)
- Install [MongoDB](https://docs.mongodb.com/manual/installation/)
- Install [Postman](https://www.postman.com/downloads/) or use any other api testing tool

## Getting Started

- Clone the repository

```
git clone <repo url> <project_name>
```

- Install dependencies

```
npm install
```

- Open "config/mongoose.js" and add MongoDB URI, local or Atlas

- Build and run the project

```
npm start
```

- Navigate to `http://localhost:8000/` for the local client
- Navigate to `https://polling-system-api-x8xt.onrender.com` for the web hosted url link
- Perform the actions listed below in the postman or any other API testing app 

## Endpoints for testing the API

- /questions/create (To create a question)
- /questions/:questionId/options/create (To add options to a specific question)
- /questions/:questionId/delete (To delete a question)
- /options/:optionId/delete (To delete an option)
- /options/:optionsId/add_vote (To increment the count of votes)
- /questions/:questionId (To view a question and it’s options)
- /questions/ (To list down all the questions)

---

#### The project is developed solely as an API without a frontend for user visualization.
