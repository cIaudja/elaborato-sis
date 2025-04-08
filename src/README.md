# Codice Ottimizzato - Cartella `src/`

Questa cartella contiene i file **.blif** ottimizzati per il progetto, tra cui i principali come **FSMD.blif**.

## Come Avviare

### 1. Apri Docker
Assicurati che Docker sia in esecuzione sul tuo computer. Se non l'hai ancora fatto, puoi scaricarlo e installarlo da [qui](https://www.docker.com/products/docker-desktop).

### 2. Avvia il contenitore Docker
Apri il terminale e avvia il contenitore Docker eseguendo il comando seguente:

`docker run -it -v $PWD/.:/esercizio-sis -v $PWD/.bsis_history:/root/.bsis_history sis`

Questo comando:
- Mappa la cartella corrente (`$PWD/`) alla cartella `/esercizio-sis` nel contenitore.
- Mappa anche la cartella `.bsis_history` per mantenere la cronologia dei comandi.

### 3. Naviga nella directory del progetto
Nel terminale, dopo aver avviato il contenitore, naviga fino alla directory dove si trovano i file **.blif** eseguendo:

`cd Desktop/uni/1_anno/architettura degli elaboratori/sis/Elaborato/Elaborato consegnato/sis`

### 4. Avvia il programma
Una volta dentro la cartella corretta, avvia il programma **sis** eseguendo il comando:

`sis`

Questo comando aprirà l'ambiente di simulazione.

### 5. Carica il file FSMD.blif
Per caricare il file **FSMD.blif**, esegui il comando:

`read_fsmd FSMD.blif`

### 5.1. Visualizza `write_enq`
Se desideri visualizzare l'output di `write_enq`, esegui il comando:

`write_enq`

### 6. Testa i vari input
Per testare il circuito e provare vari input, usa il comando `sim` seguito dai valori binari (0 o 1) per ogni input:

`sim i1 i2 i3 i4 i5 i6`

Dove `i1`, `i2`, `i3`, `i4`, `i5`, e `i6` rappresentano i valori binari (0 o 1) che vuoi fornire come input al circuito.
