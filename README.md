# quiz_app

* The questions will be fetched from the Open Trivia DB API.
* For each fetched question, we'll create a different object using a Question class. All these Question objects will be appended to a question_bank list.
* This question_bank will be passed to the brain of the application, Controllers and a quiz object will be created. This class will be responsible for checking if there are more questions, for getting the next question, calculating the score, and so on.
* Finally, this quiz object will be passed to the QuizInterface class, and the user will be able to interact with it.
