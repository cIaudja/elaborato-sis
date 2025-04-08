# elaborato-sis
Elaborato sis per il corso di Architettura degli Elaboratori dell'Università di Verona, anno accademico 2022-2023.

Questo progetto riguarda l'ottimizzazione di circuiti digitali, in particolare il **datapath**, la **FSM** (Finite State Machine) e la **FSMD** (Finite State Machine with Datapath). La simulazione e la verifica del funzionamento sono state eseguite utilizzando l'ambiente **Sis**, che consente la descrizione e la simulazione di circuiti.

## Struttura del Progetto

Il progetto è suddiviso come segue:

### `src/`
Contiene i file ottimizzati per il progetto. I file in questa cartella sono quelli utilizzati per la simulazione e ottimizzazione dei circuiti.

### `legacy/`
Contiene la versione non ottimizzata del codice. Questa versione è stata inclusa per riferimento o per confronti con la versione ottimizzata.

La documentazione del progetto è inclusa nel file **relazione.pdf**, che si trova nella root della repository.

## Come Avviare

Per avviare il progetto, consulta le istruzioni nel `README.md` della cartella `src/`, che descrive come utilizzare Docker e avviare la simulazione dei file **.blif**.

## Tecnologie Usate

- **Sis**: Ambiente di simulazione per circuiti digitali.
- **Docker**: Utilizzato per eseguire l'ambiente Sis in modo isolato e portatile.

## Documentazione

La documentazione completa è inclusa nel file **relazione.pdf**, che descrive:

- Le specifiche del progetto.
- Il funzionamento della FSM.
- La struttura del database.
- I dettagli sull'ottimizzazione dei circuiti e delle componenti.
