# SMART
Repository di coordinamento del progetto SMART



## Glossario

| Termine        | Descrizione                                                                 |
|----------------|-----------------------------------------------------------------------------|
| DSS            | Decision Support System: sistema per il supporto alle decisioni operative   |
| Microservizi   | Architettura software composta da servizi indipendenti e scalabili          |
| API            | Application Programming Interface: interfaccia che permette la comunicazione tra sistemi software |
| API REST       | API basate su architettura REST che utilizzano HTTP per operazioni su risorse (GET, POST, PUT, DELETE) |
| API Gateway    | Punto di accesso unico per l’esposizione e gestione delle API               |
| Data ingestion | Processo di acquisizione e integrazione dei dati da diverse sorgenti        |
| Streaming dati | Trasmissione continua di dati in tempo reale                                |
| Kafka          | Piattaforma distribuita per lo streaming e la gestione dei dati             |
| Telegraf       | Agente per la raccolta e l’invio di metriche e dati                         |
| DBMS           | Sistema di gestione di database                                             |
| PostGIS        | Estensione spaziale di PostgreSQL per dati georeferenziati                  |
| Routing        | Calcolo dei percorsi ottimali                                               |
| Scheduling     | Pianificazione delle attività nel tempo                                     |
| Forecasting    | Previsione di eventi futuri basata su dati storici                          |
| Simulazione    | Riproduzione virtuale di scenari per analisi e test                         |
| Replanning     | Ricalcolo dinamico dei piani in base a nuove condizioni                     |
| Data Visualization | Rappresentazione grafica dei dati                                       |
| Living Map     | Mappa interattiva con dati aggiornati in tempo reale                        |
| Gantt          | Strumento di pianificazione temporale delle attività                        |

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

 
    *Competenze*: sviluppo backend, microservizi, integrazione sistemi, gestione dati real-time  
    *Tecnologie*: Python, REST API, database relazionali, servizi telemetry e meteo  

  - **CREATECK**  
    Servizi per previsione, simulazione, pianificazione e ottimizzazione dei processi.  
    - [forecast_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/forecast_service)  
    - [routing_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/routing_service)  
    - [scheduling_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/scheduling_service)  
    - [simulator_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/simulator_service)  
    - [replanning_service](https://github.com/protodesign-ufficio/SMART-DSS-MICROSERVICES/tree/main/SMART_replanning_service)  


    *Competenze*: modellazione matematica, ottimizzazione, algoritmi decisionali, simulazione  
    *Tecnologie*: Python, librerie scientifiche, modelli previsionali  


- [KAFKA-TELEGRAF](https://github.com/protodesign-ufficio/SMART-KAFKA-TELEGRAF)  
  **Descrizione**: infrastruttura per l’ingestione e lo streaming dei dati tramite pipeline distribuite.  
  Include configurazioni per raccolta, trasformazione e inoltro dei dati.

  - **JUSTWEB**  
    *Competenze*: data ingestion, gestione pipeline dati, integrazione sistemi  
    *Tecnologie*: Apache Kafka, Telegraf  


- [DATABASE](http://87.26.178.190:8080/)  
  **Descrizione**: repository per la definizione, creazione e gestione delle strutture dati persistenti del sistema.

  - **JUSTWEB**  
    *Competenze*: progettazione database, modellazione dati  
    *Tecnologie*: SQL, database relazionali, PostgreSQL, PostGIS  


- [KAFKA-SERVICES](https://github.com/protodesign-ufficio/SMART-KAFKA-SERVICES)  
  **Descrizione**: servizi applicativi che consumano i topic Kafka e implementano la logica di elaborazione dei dati.

  - **DIGIPLUS**  
    Sviluppo e integrazione dei servizi.  
    *Competenze*: sviluppo backend, integrazione microservizi  
    *Tecnologie*: client Kafka, REST API, Python  

  - **CREATECK**  
    Definizione della logica analitica e degli algoritmi.  
    *Competenze*: analisi dati, algoritmi, modellazione  
    *Tecnologie*: Python, librerie di calcolo  


- [LIVING-MAP](https://github.com/protodesign-ufficio/SMART-LIVINGMAP)  
  **Descrizione**: frontend del sistema con componenti di visualizzazione dati, dashboard analytics e mappa interattiva.

  - **ANALIST**  
    - [Living Map](https://github.com/protodesign-ufficio/SMART-LIVINGMAP)


    *Competenze*: visualizzazione dati geospaziali, UI interattive  
    *Tecnologie*: JavaScript, librerie di mapping  

  - **DIGIPLUS**  
    - [dashboard analytics](https://github.com/protodesign-ufficio/SMART-LIVINGMAP/tree/main/static/dashboard),  
    - [Gantt](https://github.com/protodesign-ufficio/SMART-LIVINGMAP/tree/main/static/gantt)
 
      
    *Competenze*: sviluppo frontend, data visualization  
    *Tecnologie*: HTML, CSS, JavaScript  


## Riepilogo partner

| Partner   | Ambito principale                                                                 |
|-----------|------------------------------------------------------------------------------------|
| TRAVELMAR | servizi operativi del DSS, backend a microservizi, monitoraggio e integrazione dati real-time |
| JUSTWEB   | data ingestion, streaming/pipeline dati e progettazione database                   |
| CREATECK  | forecasting, simulazione, routing, scheduling, replanning e algoritmi decisionali |
| DIGIPLUS  | integrazione servizi backend Kafka-based e sviluppo frontend dashboard/Gantt       |
| ANALIST   | visualizzazione dati geospaziali e sviluppo della Living Map                       |
