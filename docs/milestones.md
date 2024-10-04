# Milestones

## [M0] Milestone 0: Modelazione e pianificazione del problema

- **Obiettivo:** Analizzare le storie utente e definire i requisiti chiave del dominio del problema da affrontare nello sviluppo del MVP. Organizzare i concetti chiave secondo le esigenze del business, utilizzando Domain-Driven Design (DDD) come metodologia.
- **Entregabile:** Una modellazione iniziale del dominio del problema con i concetti chiave e le loro relazioni. Definire le entità e gli aggregati necessari per sviluppare l'MVP, basato sulle storie utente.
- **Viabilità:** Il milestone è completato quando la modellazione e la pianificazione del problema sono validate dal revisore e comprensibili per il team di sviluppo. Le storie utente devono essere correttamente allineate con i concetti chiave del dominio.
- **HU associate:** [HU001], [HU002], [HU003].

## [M1] Milestone 1: Acquisizione dei ticket elettronici

- **Obiettivo:** Implementare la funzionalità che consente all'utente di caricare un ticket elettronico e estrarre automaticamente i dati dei medicinali.
- **Entregabile:** Codice che permette di caricare un ticket elettronico e ottenere informazioni come nome del medicinale, quantità e data di acquisto.
- **Viabilità:** Il milestone è completato quando il sistema è in grado di caricare con successo diversi formati di ticket elettronici e estrarre correttamente le informazioni richieste.
- **HU associate:** [HU001].

## [M2] Milestone 2: Aggiornamento automatico dell'inventario

- **Obiettivo:** Implementare la funzionalità che aggiorna automaticamente l'inventario dei medicinali ogni volta che viene caricato un ticket elettronico.
- **Entregabile:** Codice che consente l'aggiornamento automatico dell'inventario in base ai dati estratti dai ticket elettronici.
- **Viabilità:** Il milestone è completato quando il sistema aggiorna correttamente l'inventario con le informazioni estratte e può essere verificato attraverso test di accettazione.
- **HU associate:** [HU002].

## [M3] Milestone 3: Sistema di notifiche intelligenti

- **Obiettivo:** Implementare un sistema di notifiche che avvisi l'utente quando le scorte di un medicinale stanno per finire o quando è necessario acquistare un nuovo lotto di medicinali.
- **Entregabile:** Codice che permette l'invio di notifiche intelligenti all'utente.
- **Viabilità:** Il milestone è completato quando il sistema invia correttamente notifiche basate sul livello delle scorte dei medicinali presenti in inventario.
- **HU associate:** [HU003].

## [M4] Milestone 4: Interfaccia di visualizzazione dell'inventario

- **Obiettivo:** Implementare una dashboard che permetta all'utente di visualizzare l'inventario aggiornato dei medicinali, inclusi nome, quantità e data di acquisto.
- **Entregabile:** Codice che consente la visualizzazione dell'inventario in un'interfaccia facile da usare.
- **Viabilità:** Il milestone è completato quando l'inventario è visualizzabile in un formato chiaro e facile da interpretare per l'utente.
- **HU associate:** [HU004].
