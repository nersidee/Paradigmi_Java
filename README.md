# Esercizi di Paradigmi di Programmazione - UPO

Questo repository contiene una serie di micro-applicazioni ed esercizi sviluppati per il corso di **Paradigmi di Programmazione** presso l'Università del Piemonte Orientale (UPO). 

Lo scopo del progetto è applicare i concetti fondamentali della programmazione orientata agli oggetti (OOP) in Java, inclusa la gestione delle classi, l'ereditarietà, le strutture dati e il testing automatizzato.

## 📂 Struttura del Progetto

Il repository è diviso in diversi sotto-progetti (moduli Eclipse):

### 1. PrimiEsercizi
Una raccolta di algoritmi e piccoli programmi per prendere confidenza con la sintassi Java e i costrutti base:
* Conversione di temperature (Fahrenheit in Celsius).
* Calcolo del Massimo Comune Divisore (MCD).
* Gestione e stampa di matrici.
* Manipolazione di stringhe.
* Ricerca di duplicati in un array.
* Utilizzo delle enumerazioni (`enum`).

### 2. Gestione Rubrica
Una serie di progetti che mostrano l'evoluzione di una struttura dati, passando da un approccio procedurale a uno orientato agli oggetti:
* **RubricaStatica**: Implementazione procedurale di una rubrica utilizzando array statici e costanti.
* **RubricaDinamica**: Implementazione che fa uso di `ArrayList` per una gestione dinamica dei dati.
* **RubricaContatto**: L'implementazione finale e più completa. Introduce il concetto di classe `Contatto` (nome, email, multipli numeri di telefono) separata dalla classe `Rubrica`, applicando correttamente i principi dell'OOP.

### 3. MasterMind
Un'implementazione completa del classico gioco da tavolo MasterMind. Il progetto utilizza i concetti di astrazione ed ereditarietà per definire i giocatori:
* **Giudice**: Gestisce le regole del gioco, la validazione delle stringhe e calcola "Bulls" (numeri corretti in posizione errata) e "Maggots" (numeri e posizioni corretti).
* **Umano**: Permette a un utente di inserire i tentativi da console.
* **Computer**: Genera tentativi e target in modo casuale.
* **SmartComputer**: Un'intelligenza artificiale che deduce la combinazione corretta riducendo progressivamente lo spazio delle soluzioni possibili in base ai feedback ricevuti.

## 🛠️ Tecnologie Utilizzate
* **Linguaggio**: Java
* **Testing**: JUnit 5 (Jupiter) per la verifica della logica di business nei progetti *MasterMind* e nelle varianti della *Rubrica*.
* **IDE**: Eclipse

## 🚀 Come eseguire i progetti
1. Clona questo repository sul tuo computer.
2. Apri il tuo IDE (es. Eclipse, IntelliJ IDEA o VS Code).
3. Importa la cartella come progetto/workspace Java esistente.
4. Per `PrimiEsercizi` o `MasterMind` (se presenti classi `main`), esegui direttamente le classi.
5. Per eseguire i test, clicca col tasto destro sulla cartella `src/test` di uno dei progetti e seleziona **Run As > JUnit Test**.

---
*Progetto sviluppato a fini didattici.*
