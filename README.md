• Studente.java raccoglie studenti da prompt e li appende subito a students.csv.

  - Classe Studente: campi nome, cognome, matricola, annoNascita; toCsv() formatta matricola;nome;cognome;anno.
  - main: ciclo finché digiti exit. Per ogni studente chiede i campi, valida l’anno come intero, salva la riga CSV con StandardOpenOption.CREATE, APPEND, stampa la riga salvata. Dopo ogni inserimento chiede se continuare o uscire con exit.
  - Salva il file in UTF‑8, separatore ; (niente escaping avanzato: ok per dati semplici).

  File: Studente.java.
