

Build a quiz app as per the mockup presented below

![Mockup](https://akiranr.github.io/QuizApp/QuizApp_Mockup.jpg)

## Requirements

1. The endpoint for fetching categories is [CategoriesAPI](https://opentdb.com/api_category.php)
2. The options for Difficuly and Type are hardcoded
3. When user clicks "Go", fetch and display 10 questions at a time, indicated by the "amount" querystring parameter below
4. The endpoint for fetching questions based on the selected dropdown options is [QuestionsAPI](https://opentdb.com/api.php?amount=10&category=22&difficulty=medium&type=multiple). Ignore corresponding querystring parameters if user selects "Any"
5. Validate if all questions are answered before user can "Check score"
6. Display scoring percentage based on the no. of correct answers
7. "Try again" will clear all the answers and allow user to start answering again
