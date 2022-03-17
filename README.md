# Esercizio-4
In entrambi i casi, data la definizione della funzione f che esegue la somma delle due variabili in argomento, si hanno diversi output.
La differenza tra la funzione a sinistra e quella a destra sta nel fatto che:
-a sinistra, nonostante si chiami la funzione f per le variabili (100,100) il risultato di questa non viene assegnato ad alcuna variabile, 
e quando si chiede di stampare la variabile somma, il programma cercherà l'unica variabile con quel nome, che non è il risultato della funzione f, 
ma la variabile sum definita pari a 3;
-a destra, si definisce la stessa variabile somma, ma ora si chiede di stampare direttamente il risultato della funzione somma, 
senza nemmeno definire una variabile con quel valore, ma passando come argomento della funzione print() un'altra funzione e allora in questo caso
il valore che verrà visualizzato sarà quello dato dalla somma degli argomenti della funzione f;
