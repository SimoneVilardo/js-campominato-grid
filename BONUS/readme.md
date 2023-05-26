PROBLEMA:Aggiungere una select accanto al bottone di generazione, che fornisca una scelta tra tre diversi livelli di difficoltà:
- con difficoltà 1 => 100 caselle, con un numero compreso tra 1 e 100, divise in 10 caselle per 10 righe;
- con difficoltà 2 => 81 caselle, con un numero compreso tra 1 e 81, divise in 9 caselle per 9 righe;
- con difficoltà 3 => 49 caselle, con un numero compreso tra 1 e 49, divise in 7 caselle per 7 righe;

SOLUZIONE:

1.creo all'interno del click del bottone un if 
    1.1 recupero la select
    1.2 SE seleziono la difficoltà facile e clicco play inserirà la griglia con 49 quadrati
    1.3 ALTRIMENTI SE seleziono la difficoltà normale e clicco play inserirà la griglia con 81 quadrati
    1.4 ALTRIMENTI seleziono la difficoltà difficile e clicco play inserirà la griglia con 100 quadrati