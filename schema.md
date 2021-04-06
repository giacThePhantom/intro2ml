# Intro to machine learning

## INtro

## Data Features and models

## Models, Generalizatioon Error
* Definire dati, modelli e errore
* Scegliere un modello che minimizza l'errore.
* Dato un problema si osserva data, famiglia di modelli e funzione di errore.
* 5 Elementi principali di ML: formalizzare il problema in una di task rilevanti, secondo elemento chiave i dati, definire una famiglia di modelli, un'ipotesi di modello, definire una funzione obiettivo, e un algoritmo di learning.

### Task
* Una task rappresenta il tipo di predizione che viene svolta per risolvere un problema su qualche dato.
* Si identifica una task con l'insieme di funzioni che potenzialmente lo risolvono.
* Consiste di una funzione che assegna ad ogni input $x\in X$ un output $y\in Y$
$$f:X\rightarrow Y$$
$$F\_{task}\subset Y^X$$
* La natura degli insieme dipende dal tipo di task.

#### Classification
* Trovare una funzione $f$ che assegna ogni input a un'etichetta discreta:
$$f(x)\in Y={c\_1, \cdots c\_k}$$

#### Regression
* Una funzione $F$ che assegna ogni input a un'etichetta continua:
$$f(x)\in Y$$

#### Density estimation
* Trova una distrobuzione di probabilita
$$f\in \Delta(X)$$
Tale che fits i dati $x\in X$, ovvero che li approssima al meglio.

#### Clustering
Trova una funzione che assegna a ogni input un indice di cluster numero naturale.
Tutti i punti mappati allo stesso input formano un cluster.

#### Dimensionality reduction
* Trova una funzione $f\in Y^X$ che mappa ogni input a un output di dimensione minore.


## KKK and linear models
