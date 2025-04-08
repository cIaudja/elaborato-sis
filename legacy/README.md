# Legacy Code

Questa cartella contiene il codice **non ottimizzato** per le seguenti componenti del progetto:
- **Datapath**
- **FSM (Finite State Machine)**
- **FSMD (Finite State Machine with Datapath)**

## Scopo
Il codice presente in questa cartella rappresenta una versione **non ottimizzata** del datapath, della FSM e della FSMD. Queste componenti sono state mantenute per scopi di confronto con le versioni ottimizzate che si trovano nella cartella `src/`.

## Come usarlo
Per eseguire o testare il codice legacy, segui le stesse istruzioni generali del progetto, ma tieni presente che le performance potrebbero essere inferiori rispetto alla versione ottimizzata.

### Limitazioni
- La versione **non ottimizzata** del datapath, FSM e FSMD potrebbe non essere efficiente in termini di risorse e prestazioni.
- Non include i miglioramenti apportati alla versione ottimizzata.
- Questo codice non è stato modificato per ottimizzare le risorse, ma solo per implementare le funzionalità di base necessarie.

## Note
Questo codice è utile per confrontare il comportamento tra la versione non ottimizzata e quella ottimizzata delle componenti principali, permettendo di valutare i miglioramenti in termini di prestazioni e efficienza.
