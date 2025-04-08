# Codice Ottimizzato - Cartella `src/`

Questa cartella contiene i file **.blif** ottimizzati per il progetto, tra cui i principali come **FSMD.blif**.

## Come Avviare

### 1. Apri Docker
Assicurati che Docker sia in esecuzione sul tuo computer. Se non l'hai ancora fatto, puoi scaricarlo e installarlo da [qui](https://www.docker.com/products/docker-desktop).

### 2. Avvia il contenitore Docker
Apri il terminale e avvia il contenitore Docker eseguendo il comando seguente:

```bash
docker run -it -v $PWD/.:/esercizio-sis -v $PWD/.bsis_history:/root/.bsis_history sis

### 3. Naviga nella directory del progetto
Nel terminale, dopo aver avviato il contenitore, naviga fino alla directory dove si trovano i file **.blif** eseguendo:

```bash
cd Desktop/uni/1_anno/architettura degli elaboratori/sis/Elaborato/Elaborato consegnato/sis

### 4. Avvia il programma
Una volta dentro la cartella corretta, avvia il programma **sis** eseguendo il comando:

```bash
sis


