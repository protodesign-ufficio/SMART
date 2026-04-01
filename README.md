# SMART
Repository di coordinamento del progetto SMART

## Repository collegate

- [DSS](https://github.com/protodesign-ufficio/SMART-DSS)  
  Include la logica di gestione del db e i servizi:
  - **TRAVELMAR**: api-gateway (app), anagrafica_service, alerting_service, operativo_service, percorsi_service, telemetry_service, weather_service  
  - **CREATECK**: forecast_service, routing_service, scheduling_service, simulator_service, replanning_service  

- [KAFKA-TELEGRAF](https://github.com/protodesign-ufficio/SMART-KAFKA-TELEGRAF)  
  Include le configurazioni di Kafka e Telegraf per l'ingestione dei dati:
  - **JUSTWEB**  

- [DATABASE](https://github.com/protodesign-ufficio/SMART-KAFKA-TELEGRAF)  
  Include la creazione del DB:
  - **JUSTWEB**  

- [KAFKA-SERVICES](https://github.com/protodesign-ufficio/SMART-KAFKA-SERVICES)  
  Include i servizi consumer dei topic Kafka:
  - **CREATECK**: parte logica  
  - **DIGIPLUS**: sviluppo dei servizi  

- [LIVING-MAP](https://github.com/protodesign-ufficio/SMART-LIVINGMAP)  
  Include l'intero frontend, Living Map e dashboard analytics:
  - **ANALYST**: Living Map (livingmap)  
  - **DIGIPLUS**: dashboard analytics (file.html, file2.html), Gantt
  

## Documentazione

La documentazione degli specifici moduli è presente nella cartella `docs/` del repository associato.
