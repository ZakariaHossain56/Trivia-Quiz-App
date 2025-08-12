
## Trivia Quiz App
A quiz app featuring user authentication, custom quizzes and API-powered questions.

### Project Features
- Secure user sign-in and sign-up for personalized experience
- Create custom quizzes with your own questions and answers
- Generate and share unique Quiz IDs for easy access to custom quizzes
- Join custom quizzes using a Quiz ID for community play
- API-based trivia questions from the Open Trivia Database for diverse topics
- JSON parsing to load API questions into the UI
- Recent result tracking with scores and Quiz ID for last played quiz
- SwiftUI-based modern, responsive, and visually appealing interface
- Engaging experience for both casual players and quiz enthusiasts

### Project Snapshots

<table>
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/ZakariaHossain56/Trivia-Quiz-App/master/snapshots/signup.png" alt="Sign up" width="200">
      <div align="center"><i>Sign up</i></div>
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/ZakariaHossain56/Trivia-Quiz-App/master/snapshots/signin.png" alt="Sign in" width="200">
      <div align="center"><i>Sign in</i></div>
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/ZakariaHossain56/Trivia-Quiz-App/master/snapshots/home_page.png" alt="Home Page" width="200">
      <div align="center"><i>Home Page</i></div>
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/ZakariaHossain56/Trivia-Quiz-App/master/snapshots/add_quiz.png" alt="Add quiz" width="200">
      <div align="center"><i>Add quiz</i></div>
    </td>
  </tr>


  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/ZakariaHossain56/Trivia-Quiz-App/master/snapshots/join_quiz.png" alt="Join quiz" width="200">
      <div align="center"><i>Join quiz</i></div>
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/ZakariaHossain56/Trivia-Quiz-App/master/snapshots/right_ans.png" alt="Right ans" width="200">
      <div align="center"><i>Right ans</i></div>
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/ZakariaHossain56/Trivia-Quiz-App/master/snapshots/wrong_ans.png" alt="Wrong ans" width="200">
      <div align="center"><i>Wrong ans</i></div>
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/ZakariaHossain56/Trivia-Quiz-App/master/snapshots/result.png" alt="Result" width="200">
      <div align="center"><i>Result</i></div>
    </td>
  </tr>


  
</table>






### Directory Structure

```
📂TriviaGame
 │───📂Components
 |   │──AnswerRow.swift
 |   │──PrimaryButton.swift
 |   └──ProgressBar.swift
 │───📂Models
 |   │──Answer.swift
 |   └──Trivia.swift
 │───📂Views
 |   │──AddQuiz.swift
 |   │──ContentView.swift
 |   │──ContentViewBackUp.swift
 |   │──Home.swift
 |   │──JoinQuiz.swift
 |   │──Profile.swift
 |   │──QuestionView.swift
 |   │──ResultView.swift
 |   │──ShowQuiz.swift
 |   │──SignUp.swift
 |   │──TestView.swift
 |   └──TriviaView.swift
 │───Extensions.swift
 │───TriviaGameApp.swift     
 └───TriviaManager.swift
    
```
