# ArbolDecision - Decision tree
Un árbol de decisión es un modelo de predicción utilizado en diversos ámbitos que van desde la inteligencia artificial hasta la Economía. Dado un conjunto de datos se fabrican diagramas de construcciones lógicas, muy similares a los sistemas de predicción basados en reglas, que sirven para representar y categorizar una serie de condiciones que ocurren de forma sucesiva, para la resolución de un problema.

Consulte https://es.wikipedia.org/wiki/%C3%81rbol_de_decisi%C3%B3n

# La Aplicación
Esta fue pensada como una aplicación académica que nos muestra todo el proceso de cálculo detrás para su compresión. Por ejemplo suponga un banco que otorga créditos, el cual necesita saber a quienes otorgar créditos y a quienes no. Para ello se basa de un histórico de créditos representado por la siguiente tabla:

| Age        | Has_job      | Own_house   | Credit_rating  | Clases   |
|:----------:|:------------:|:-----------:|:--------------:|:--------:|
|young|false|false|fair|No|
|young|false|false|good|No|
|young|true|false|good|Yes|
|young|true|true|fair|Yes|
|young|false|false|fair|No|
|middle|false|false|fair|No|
|middle|false|false|good|No|
|middle|true|true|good|Yes|
|middle|false|true|excellent|Yes|
|middle|false|true|excellent|Yes|
|old|false|true|excellent|Yes|
|old|false|true|good|Yes|
|old|true|false|good|Yes|
|old|true|false|excellent|Yes|
|old|false|false|fair|No|

 Al correr la aplicación nos genera un árbol de decisión como el que se ve a continuación y nos muestra todo el proceso que ha realizado.

![alt text](https://github.com/nicoangelico/ArbolDecision/blob/master/ArbolDecision.png "Logo Title Text 2")

Una vez armado el árbol de decisión podemos clasificar nuevos clientes para ver si se le debe o no otorgar un crédito.

| Age        | Has_job      | Own_house   | Credit_rating  | Give credit |
|:----------:|:------------:|:-----------:|:--------------:|:--------:|
|young|false|false|good|No|
|middle|true|false|fair|Yes|
|middle|false|true|good|Yes|
