
API-Powered True/False Quiz in Python with Tkinter GUI

This project demonstrates a well-structured and interactive quiz application that utilizes Object-Oriented Programming (OOP) principles and integrates with an external API to provide a dynamic and engaging learning experience.

Key Features:

1.Data-Driven Quiz Content: The quiz questions are retrieved from the opentdb.com API, ensuring a diverse and up-to-date pool of trivia prompts.

2.Question-Answering Mechanism: The QuizBrain class manages the quiz flow, including presenting questions, checking answers, and tracking the user's score.

3.User Interaction with GUI: The QuizInterface class creates a user-friendly GUI using Tkinter, allowing users to interact with the quiz by selecting their answers.

4.Real-Time Feedback and Scoring: Immediate feedback is provided after each answer, and the score is displayed at the top of the screen.

5.Interactive Elements and Aesthetics: The GUI features attractive visuals, such as images for true/false answers, to enhance the user experience.

6.End-of-Quiz Summary: Upon completion of the quiz, the final score is displayed along with a message congratulating the user.

Project Structure and Usage:

1.Question Model: The Question class represents a single question, encapsulating its text and answer.

2.Quiz Brain: The QuizBrain class manages the quiz logic, including question retrieval, answer checking, and score tracking.

3.Data Acquisition: The question data is fetched from the opentdb.com API using the requests library.

4.User Interface: The QuizInterface class creates the interactive GUI using Tkinter, handling user interactions and displaying questions and feedback.

5.Application Execution: The main script initializes the QuizBrain with the question data, creates the QuizInterface, and runs the quiz.

This project demonstrates the practical application of OOP principles and API integration, providing a comprehensive and engaging quiz experience.
