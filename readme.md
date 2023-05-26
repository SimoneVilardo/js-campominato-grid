PROBLEMA:L'utente clicca su un bottone che genererà una griglia di gioco quadrata.
Ogni cella ha un numero progressivo, da 1 a 100. Ci saranno quindi 10 caselle per ognuna delle 10 righe. Quando l'utente clicca su ogni cella, la cella cliccata si colora di azzurro ed emetto un messaggio in console con il numero della cella cliccata.

SOLUZIONE:

1.creo un contenitore con all'interno un bottone nel DOM;

2.recupero con get.ElementById() l'elemento dal DOM in cui creare la griglia;

3.creo una funzione che al click del button faccia apparire una griglia; 

4.creo il singolo quadratino e lo mostro a schermo con la funzione .append();

5.al click di ogni singola cella essa si colora di azzurro e manda un mesaggio in console con il della cella cliccata