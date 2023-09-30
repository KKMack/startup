# Make-Your-Own Quiz Game

## Description deliverable

### Elevator pitch

The best games are the ones you make yourself--thus, the make-your-own quiz game: the easist way to create a multi-choice quiz for others to test their mettle with. Simply sign in, make a quiz, and submit it for others to take--the topic and questions are entirely up to you.

### Design

![Login](Login.png)
![Homepage](Home.png)

### Key features

* Login to account
* Quiz titling and creation, storing completed quizzes
![Quiz Title](Title.png)
![Quiz Editing](Edit%20Quiz.png)
* Taking quizzes made by other users
 ![Quizzes](Quizzes.png)
 ![Quiz Taking](Take%20Quiz.png)
 * Displays score of taken quizzes

 ### Technologies

 - **HTML** - 5(?) pages of HTML, links to each page  
 - **CSS** - arrangement of elements, use of whitespace, adapts to screen size
 - **JavaScript** - Login information, opening quizzes, saving quizzes, etc.
- **Service** - All the backend for login, retrieving past quizzes, submitting quizzes
- **DB** - Store quizzes and users in database
- **Login** - Allows users to create an account and securely login, cannot take or create quizzes without account
- **WebSocket** - Past quizzes are available to all users
- **React** - Porting to React

## HTML deliverable

- **HTML pages** - Seven deliverable pages, including login, home, a quiz list, a quiz editor, and a page to take the quiz and receive a score.
- **Links** - Login links to the homepage, homepage links to past quizzes and for creating new quizzes.
- **Text** - Most pages include some kind of text element.
- **Images** - As far as I can tell, I did not need to include any images--this may change as development continues.
- **Login** - There is input for an account login.
- **Database** - Past quizzes will be retrieved from the database.
- **WebSocket** - Newly created quizzes will be update the quiz list.