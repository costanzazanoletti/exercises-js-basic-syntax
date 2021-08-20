# Pseudocodice: trova il numero più grande

```text
definisci procedura trova_numero_maggiore:
  input: una pila di numeri, chiamala PILA

  guarda il primo NUMERO nella pila e scrivilo sul post-it, chiamalo MAX_FINORA

  per_ogni NUMERO nella PILA, esegui:
    se NUMERO > MAX_FINORA, allora:
      sostituisci MAX_FINORA con NUMERO sul post-it
    fine se
  fine per_ogni

  restituisci post-it con MAX_FINORA
fine definisci procedura

assegna PILA uguale a [10, 9, -2, 100, 17]
chiama la procedura trova_numero_maggiore con input: PILA // ci restituisce 100

```
