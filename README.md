<h1> StudyReviewApp </h1>
The StudyReviewApp is a Python-based interactive application that allows users to create and manage review questions in preparation for an upcoming exam. The app provides users with the ability to add new questions, categorize them by topic, and review them in a randomized order.


# Installation 
To use this app, you'll need to have Python and Jupyter Notebook installed on your machine. Here's how to install them:

* Python
Go to the official website of Python (https://www.python.org/downloads/) and download the latest version of Python.
Run the installer and follow the prompts to install Python.

* Jupyter Notebook
Go to the Anaconda website (https://www.anaconda.com/download) and download the latest version of Anaconda.
Run the installer and follow the prompts to install Anaconda.
Open Anaconda Navigator and launch Jupyter Notebook.


# Running the Application
Clone or download the repository to your local machine.
Open Jupyter Notebook and navigate to the cloned repository.
Open the StudyReview.ipynb notebook.


# Usage
When you start up the application, you'll be given a choice between beginning a study session or adding a new question to the list. If you choose to add a new question, you'll be asked to provide the question text, a list of possible responses separated by commas, the designation of which response is correct, and a list of topic tags separated by commas.

If you choose to start a review session, the program will present a random question from the question list. You'll be provided with the question text and all response options with labels. You'll then be prompted to provide your response using the labels presented. The program will inform you of the correct answer, and you'll be prompted to choose whether to continue the session or quit.

The application stores the created questions in a .csv file and tracks your performance by keeping record of your correct and incorrect answers for each question. It also employs a logical system to provide you with questions that you have previously answered incorrectly. Additionally, the application tracks the average time taken by users to answer each specific question.


# Contributing
Contributions are welcome! To contribute to the project, please follow these steps:
1. Fork the repository
2. Create a new branch
3. Make your changes and commit them
4. Push your changes to your forked repository
5. Create a pull request


# Author
Fatemeh Karami (karami.f@gmail.com)
