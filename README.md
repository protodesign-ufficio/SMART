# SMART
Repository di coordinamento del progetto SMART

## Repository collegate

- [DSS](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES)  
  **Descrizione**: piattaforma a microservizi per la gestione operativa, l’elaborazione dei dati e il supporto decisionale (DSS).  
  Include la logica di gestione dei database e i servizi applicativi.

  - **TRAVELMAR**  
    Servizi per la gestione operativa, monitoraggio e integrazione dati in tempo reale.  
    - [api-gateway](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/app)  
    - [anagrafica_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/anagrafica_service)  
    - [alerting_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/alerting_service)  
    - [operativo_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/operativo_service)  
    - [percorsi_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/percorsi_service)  
    - [telemetry_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/telemetry_service)  
    - [weather_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/weather_service)  

    **Partner**: JUSTWEB  
    - *Competenze*: sviluppo backend, microservizi, integrazione sistemi, gestione dati real-time  
    - *Tecnologie*: REST API, database relazionali, servizi telemetry e meteo  

  - **CREATECK**  
    Servizi per previsione, simulazione, pianificazione e ottimizzazione dei processi.  
    - [forecast_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/forecast_service)  
    - [routing_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/routing_service)  
    - [scheduling_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/scheduling_service)  
    - [simulator_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/simulator_service)  
    - [replanning_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/SMART_replanning_service)  

    **Partner**: CREATECK  
    - *Competenze*: modellazione matematica, ottimizzazione, algoritmi decisionali, simulazione  
    - *Tecnologie*: Python, librerie scientifiche, modelli previsionali  


- [KAFKA-TELEGRAF](https://github.com/protodesign-ufficio/SMART-KAFKA-TELEGRAF)  
  **Descrizione**: infrastruttura per l’ingestione e lo streaming dei dati tramite pipeline distribuite.  
  Include configurazioni per raccolta, trasformazione e inoltro dei dati.

  - **JUSTWEB**  
    - *Competenze*: data ingestion, gestione pipeline dati, integrazione sistemi  
    - *Tecnologie*: Apache Kafka, Telegraf  


- [DATABASE](https://github.com/protodesign-ufficio/DBs)  
  **Descrizione**: repository per la definizione, creazione e gestione delle strutture dati persistenti del sistema.

  - **JUSTWEB**  
    - *Competenze*: progettazione database, modellazione dati  
    - *Tecnologie*: SQL, database relazionali  


- [KAFKA-SERVICES](https://github.com/protodesign-ufficio/SMART-KAFKA-SERVICES)  
  **Descrizione**: servizi applicativi che consumano i topic Kafka e implementano la logica di elaborazione dei dati.

  - **DIGIPLUS**  
    Sviluppo e integrazione dei servizi applicativi.  
    - *Competenze*: sviluppo backend, integrazione microservizi  
    - *Tecnologie*: client Kafka, REST API  

  - **CREATECK**  
    Definizione della logica analitica e degli algoritmi.  
    - *Competenze*: analisi dati, algoritmi, modellazione  
    - *Tecnologie*: Python, librerie di calcolo  


- [LIVING-MAP](https://github.com/protodesign-ufficio/SMART-LIVINGMAP)  
  **Descrizione**: frontend del sistema con componenti di visualizzazione dati, dashboard analytics e mappa interattiva.

  - **ANALYST**  
    [Living Map](https://github.com/protodesign-ufficio/SMART-LIVINGMAP)  
    - *Competenze*: visualizzazione dati geospaziali, UI interattive  
    - *Tecnologie*: JavaScript, librerie di mapping  

  - **DIGIPLUS**  
    [dashboard analytics](https://github.com/protodesign-ufficio/SMART-LIVINGMAP/tree/main/static/dashboard),  
    [Gantt](https://github.com/protodesign-ufficio/SMART-LIVINGMAP/tree/main/static/gantt)  
    - *Competenze*: sviluppo frontend, data visualization  
    - *Tecnologie*: HTML, CSS, JavaScript  


## Documentazione

La documentazione degli specifici moduli è disponibile nella cartella `docs/` del repository associato.
