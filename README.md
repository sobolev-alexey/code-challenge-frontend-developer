## Quiz Game Coding Challenge

##### Position: Software Engineer
We really appreciate your time and effort working on this home task as part of our interview process. It is meant for you to demonstrate your skills as well as get a taste of what we are looking for and what your job at IOTA Foundation will get you in.  

Please do not share this task with anyone or make it public in any way. We encourage you to contact us if you have any questions, by replying to the email.


### Overview
Your challenge is to create a 10 question, true or false, quiz app in React. **You should not just implement the most basic solution. This is a chance to show off your abilities and impress.**

**The application code will be reviewed and scored on these key areas with many subset areas for each:**

- Functionality
- Code Format
- Project Structure
- Scalability
- Maintainability
- Use of industry best practices  

Some specific things that we are looking for:

 - Typescript if you know it
 - Correct implementation of a context/state manager
 - Correct implementation of a navigation solution
 - Componentization
 - Communication in the repo and/or code (comments, meaningful variable names, readme file)
 - Best practices with API calls and data
 - Separation of concerns between business and UI logic  

### Goals
Implement the screens based off the wireframes and api below using **advanced techniques** and **industry best practices** for React. Note that the wireframes may not be complete, so use your best judgment for UI/UX implementation. **Do not use a boilerplate like React Boilerplate or Ignite for this challenge.** We want to see how you structure your project and what tooling you use from scratch. **Create-react-app is fine to use.**

### Specifications
Data:

The API url is: https://opentdb.com/api.php?amount=10&difficulty=hard&type=boolean

Sample returned json:
```js
{
  "response_code": 0,
  "results": [
    {
      "category": "Entertainment: Video Games",
      "type": "boolean",
      "difficulty": "hard",
      "question": "Unturned originally started as a Roblox game.",
      "correct_answer": "True",
      "incorrect_answers": [
        "False"
      ]
    },…]}
```
#### Intro / Home Screen:
![The Intro screen for the app](https://raw.githubusercontent.com/sobolev-alexey/code-challenge-junior-developer/main/Intro.png "The Intro screen for the app")

 - Static Text
 - BEGIN button navigates to the Quiz screen and starts the Quiz  
 
#### Quiz Screen:
![The Quiz screen for the app](https://raw.githubusercontent.com/sobolev-alexey/code-challenge-junior-developer/main/Quiz.png "The Quiz screen for the app")

 - The headline is from question category
 - The card element contains the current question
 - The next question should appear after the current question is answered True or False
 - After all questions have been answered, navigate to the Results Screen  
 
#### Results screen:
![The Results screen for the app](https://raw.githubusercontent.com/sobolev-alexey/code-challenge-junior-developer/main/Score.png "The Results screen for the app")

 - The Score shows correct and total
 - Displays a list of the questions and whether the answer was correct or not
 - PLAY AGAIN starts over and navigates to the Home Screen
