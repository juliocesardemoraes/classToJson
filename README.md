# classToJson

## About It
This is a single script that I made to automate an process(formatting text into proper objects) that was bothering me.

## How to run it

Format the script to your liking but it's better used for common exams

<ol>
  <li>clone the repo</li>
  <li>npm install</li>
  <li>node handleExam.js</li>

</ol>

## What's the process
- [x] Get text from pictures that were taken from popular exams.
- [x] App in the phone turns pictures into text.
- [x] Feeds the text into the script created, and fix some mispelling errors.
- [x] Script returns to me the proper object that will be rendered directly into my program.

## Input/Output
I feed the following questions, with an answer variable
```
1- O condutor de veículo que se preocupa em avisar o outro que está rodando com o pneu murcho ou com a porta semifechada está:
a) Cumprindo a legislação do trânsito
b) Prejudicando a sua atenção no trânsito, podendo causar um acidente
c) Cometendo uma infração
d) Dirigindo com sentimento de solidariedade, cortesia e respeito 

2- Dirigindo um veículo, o condutor que encontrar crianças, deficientes físicos atravessando a via deve:

a) Diminuir a velocidade, buzinar e seguir em frente
b) Para o veículo e facilitar a travessia
c) Diminuir a velocidade, dar um sinal de luz e seguir em frente
d) Diminuir a velocidade, desviar e seguir em frente
```

And he returns it to me like this:
```
  {
    "question": " O condutor de veículo que se preocupa em avisar o outro que está rodando com o pneu murcho ou com a porta semifechada está:",
    "answers": [
      " Cumprindo a legislação do trânsito",
      " Prejudicando a sua atenção no trânsito, podendo causar um acidente",
      " Cometendo uma infração",
      " Dirigindo com sentimento de solidariedade, cortesia e respeito "
    ],
    "rightAnswer": 3
  },
  {
    "question": " Dirigindo um veículo, o condutor que encontrar crianças, deficientes físicos atravessando a via deve:",
    "answers": [
      " Diminuir a velocidade, buzinar e seguir em frente",
      " Para o veículo e facilitar a travessia",
      " Diminuir a velocidade, dar um sinal de luz e seguir em frente",
      " Diminuir a velocidade, desviar e seguir em frente"
    ],
    "rightAnswer": 1
  }
```

# Result
I have managed to time each process that I was doing along with each upgrade I was making towards a better, more automated
process.

- No App to read / Writing all questions in hand / Transforming text -> Object in vscode => 1:30 hour

- App that transform photo to text / Transforming text -> Object in vscode => 1:00 hour ( +33% performance from the first project)

- App that transform photo to text / Transforming text -> Object in vscode/ using hotkeys properly => 50:00 minutes (+16.67% performance comparing to the last process)

- App that transform photo to text / Transforming text -> Object in vscode/ using a macro(for hotkeys) => 44:00 minutes (+11% performance comparing to the last process)

- App that transform photo to text / Transforming text -> Using the script => 20:00 minutes (+60% performance comparing to the last process)

# Conclusion
Took me about 2:30 hours for creating this script, but in each input it saves me about 1 hour of hassle, I have to create more than 20 classes yet, saving me easily 20+ hours. since it was implemented I created 400% more classes comparing to the original database. I know there's room for improvement, but for a small project is pretty good

:white_check_mark: A 70 minutes faster process for each class created

:white_check_mark: A whopping 77.7% increase in performance

:white_check_mark: In overall a 20h+ faster process, considering all classes



