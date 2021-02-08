# reinforcement-learning-trading-agent
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

A trading agent:
  - El problema a resolver es comprar y vender acciones en el mercado a través de un bot entrenado por aprendizaje por refuerzo
  - El dataset es sacado de "yahoo" y las acciones a analizar son las de apple
  - El modulo src/* contiene la clase agente el cúal define los métodos policy, trade and train
  - El proceso de entrenamiento se hace en reinforcement_learning_trading.py en donde se define un episodio el
### SETUP 
Pasos a seguir para probar el agente

```sh
$ git clone https://github.com/matheus695p/reinforcement-learning-trading-agent.git
$ cd reinforcement-learning-trading-agent
$ echo instalar los requirements
$ pip install -r requirements.txt
```

```sh
│   README.md
│   reinforcement_learning_trading.py
│   requirements.txt
│
└───src
        reinforcement_learning_module.py
```
