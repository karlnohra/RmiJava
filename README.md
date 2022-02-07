# RmiJava

Premierement, on doit demarer notre rmi registry, c'est a dire il demare le local host 1099 sur notre machine.

Deuxiement, il faut demarer le serveur, le serveur fait un rebind au rmiregistry avec l'objet (CalculatorImpl).

Finalement, le Client a fait un lookup qui va obtenir dynamiquement le stub et invoquees les methode d'une class(Calculator).
