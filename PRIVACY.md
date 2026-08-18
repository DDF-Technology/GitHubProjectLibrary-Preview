# Privacy della Demo

La versione Demo si collega alle API GitHub soltanto quando l'utente configura volontariamente il proprio account.

- memorizza il token GitHub cifrato tramite Windows DPAPI per l'utente Windows corrente;
- invia il token esclusivamente alle API HTTPS ufficiali di GitHub per leggere i dati autorizzati dall'utente;
- non legge repository o cartelle di progetto dell'utente;
- non raccoglie telemetria o dati personali;
- crea una cache SQLite locale dei metadati GitHub e salva localmente le preferenze dell'interfaccia;
- consente di eliminare la credenziale memorizzata tramite il comando Disconnetti GitHub.

Il sistema operativo e gli eventuali strumenti di sicurezza installati sul dispositivo possono registrare autonomamente informazioni sull'esecuzione secondo le rispettive configurazioni e informative.
