# classToJson

## About It
This is a single script that I made to automate an process(formatting text into proper objects) that was bothering me.

## What's the process
- [x] Get text from pictures that were taken from popular exams.
- [x] App in the phone turns pictures into text.
- [x] Feeds the text into the script created, and fix some mispelling errors.
- [x] Script returns to me the proper object that will be rendered directly into my program.


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
