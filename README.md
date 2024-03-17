Overview
--------------------------------------------------------------------
This is a simple quiz application built using HTML, CSS, and JavaScript. The application allows users to take a quiz consisting of multiple-choice questions on various topics. It includes features such as a timer, scoring system, and dynamic question rendering.

Structure
--------------------------------------------------------------------
The application consists of three main files:

index.html: This file contains the structure of the web page. It defines the layout of the quiz app, including the start button, quiz box, result box, and various elements such as questions, options, timer, etc.

style.css: This file contains the CSS styling for the quiz app. It defines the appearance of different elements such as buttons, containers, text formatting, and animations.

quizApp.js: This file contains the JavaScript logic for the quiz app. It handles user interactions, such as starting the quiz, selecting options, calculating scores, displaying results, and managing the timer.

Additionally, there is a questions.js file that stores the array of quiz questions, each consisting of a question, options, and correct answer.

Implementation
--------------------------------------------------------------------
index.html:
Defines the structure of the web page.
Includes references to external CSS and JavaScript files.
Contains HTML elements for showing quiz questions, options, timer, and result.

style.css:
Defines the styling for various elements of the quiz app.
Includes styles for buttons, containers, text formatting, animations, and responsive design.

quizApp.js:
Implements the core logic of the quiz app.
Handles user interactions such as starting the quiz, selecting options, and displaying results.
Manages the timer functionality to limit the time for answering each question.
Calculates the user's score based on their answers.
Controls the flow of the quiz, including transitioning between questions and showing the final result.

questions.js:
Contains an array of quiz questions, each with a question, options, and correct answer.
Provides data for populating the quiz questions dynamically in the app.

How to Use
--------------------------------------------------------------------
1. Open the index.html file in a web browser or website from provided by the github pages.
2. Click on the "Start Quiz" button to begin the quiz.
3. Read each question carefully and select the answer.
4. Once an answer is selected, it cannot be changed, the quiz will then give immediate feeback.
5. Complete all questions within the time limit.
6. After answering all questions, the quiz will display your score at the end.
7. Then a prompt will show allowing you to restart or quit the quiz.

Additional Notes
--------------------------------------------------------------------
The quiz app is designed to be responsive and should work well on different screen sizes.
Users can replay the quiz or exit at any time using the provided buttons.
Developers can easily customize the quiz by modifying the questions array in the questions.js file or updating the CSS styles in the style.css file.
