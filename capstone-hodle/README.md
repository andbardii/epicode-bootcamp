# HODLE — Capstone EPICODE

Applicazione full stack per gestire portafogli e seguire investimenti, movimenti e andamento degli asset.

Parte di [**EPICODE Bootcamp**](../README.md), nella cartella `capstone-hodle/`.

## Tecnologie

Angular 16, NgRx, Java 17, Spring Boot, PostgreSQL.

## Struttura e utilizzo

Frontend: [`hodle/`](hodle/). Backend: [`hodleservice/`](hodleservice/). Richieste di esempio: [`postman_collection.json`](postman_collection.json).

Dalla radice della raccolta, in due terminali:

```sh
cd capstone-hodle/hodleservice
sh mvnw spring-boot:run
```

```sh
cd capstone-hodle/hodle
npm ci
npm start
```

Configura PostgreSQL e le API esterne nel tuo ambiente. Per il primo avvio, prepara i ruoli previsti da `AuthRunner` su un database di sviluppo dedicato. Crea il tuo account; i vecchi dati dimostrativi non sono necessari.

Servizi utilizzati: [Twelve Data](https://rapidapi.com/twelvedata/api/twelve-data1), [Seeking Alpha](https://rapidapi.com/apidojo/api/seeking-alpha), [Alpha Vantage](https://rapidapi.com/alphavantage/api/alpha-vantage).

## Licenza

Vedi la [licenza del progetto](LICENSE).
