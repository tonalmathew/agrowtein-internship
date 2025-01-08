# Homework Task: Interactive Quiz Application

Create an interactive quiz application using JavaScript. This task will help reinforce intermediate concepts like working with arrays of objects, higher-order functions, local storage, and more advanced DOM manipulation.

### Here's the starter code for the task:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Interactive Quiz</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <div class="quiz-container">
      <h1>Interactive Quiz</h1>
      <div id="quiz">
        <h2 id="question"></h2>
        <div id="choices"></div>
        <button id="submit">Submit</button>
        <button id="next" style="display:none;">Next Question</button>
      </div>
      <div id="results" style="display:none;">
        <h2>Quiz Complete!</h2>
        <p>Your score: <span id="score"></span></p>
        <h3>High Scores:</h3>
        <ol id="highScores"></ol>
        <button id="restart">Restart Quiz</button>
      </div>
    </div>
    <script src="script.js"></script>
  </body>
</html>
```

### This Interactive Quiz Application incorporates several intermediate JavaScript concepts:

1. Working with arrays of objects (quizData)
2. Advanced DOM manipulation (dynamically creating and updating elements)
3. Event delegation (for handling choice selections)
4. Local storage (for saving high scores)
5. Higher-order functions (forEach, sort)
6. Closures (in event listeners)
7. State management (tracking current question, score, and selected choice)

### Final output demo

<video width="100%" height="auto" controls>
  <source src="demo.mp4" type="video/mp4">
</video>
