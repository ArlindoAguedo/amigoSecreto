<h1 align="center" id="title">Amigo Secreto</h1>

<p align="center"><img src="https://pbs.twimg.com/profile_images/378800000749000200/62cd4dd7fb172264419712b48438aa3b_400x400.png" alt="project-image"></p>

<p id="description">Quizz is an application that allows you to find out the secret friend that a list of friends. You can add more friends to the list using this application to prepare to meet the secret friend. You will only need to sort through the list by clicking on the Amigo Sorteat.</p>

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Installation Step](#installation-steps)
- [The process](#the-process)
  - [Built with](#built-with)
  - [Structure](#quiz-structure)
- [Useful resources](#useful-resources)
- [License](#license)
- [Author](#author)

## Demo

![Quiz](https://media.giphy.com/media/pwVeGTcr39AErOnBOU/giphy.gif)
  
## Features

Here're some of the project's best features:

*   Get a question with multi options
*   Get an automatic feedback about if the answer is correct or not
*   Track the score
*   Track the progres across the questions.

## Installation Steps:

1. Clone the repository.
2. Open the project with VSCode.
3. Run the app and enjoy it.

## The process 
### Built with

Technologies used in the project:

*   Visual Studio Code
*   HTML
*   CSS
*   JavaScript

### Quiz structure

``` Swift
// Question struct
struct Question {
  let question: String
  let answers: Array<String>
  let correctAnswer: String
  
  init(q: String, a: Array<String>, b: String){
      question = q
      answers = a
      correctAnswer = b
  }
}
```

``` Swift
// Question collection
let quiz = [
  Question(
      q: "¿Quién pintó Las meninas?",
      a: ["Francisco de Goya", "Diego Velázquez", "Salvador Dalí"],
      b: "Diego Velázquez"),
  Question(
      q: "¿Cuál es la capital de Hungría?",
      a: ["Viena", "Praga", "Budapest"],
      b: "Budapest")
]
```

## Useful resources

* [Trello](https://trello.com/es) - Used to manage application development.
* [MDN Web Docs](https://developer.mozilla.org/en-US/) - Provides information on open web technologies.

## License:

> This project is licensed under the MIT License

## Author

Made with 💙 by [ArlindoAguedo](www.linkedin.com/in/arlindoat)
