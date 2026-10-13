# Build Week — Trasporto pubblico

Progetto di gruppo per la gestione di un’agenzia di trasporto pubblico, con backend Java e frontend Angular.

Parte di [**EPICODE Bootcamp**](../README.md), nella cartella `build-week-back/`.

## Tecnologie

Java 17, Hibernate, PostgreSQL, Angular 16.

## Struttura e utilizzo

Backend: [`BuildWeekBE_1/`](BuildWeekBE_1/). Frontend: [`buildtest/`](buildtest/).

Il backend è un progetto Maven con un’applicazione Java, senza un comando Spring Boot nel suo `pom.xml`: importalo nell’IDE e configura PostgreSQL e la persistenza prima dell’esecuzione.

Per il frontend, dalla radice della raccolta:

```sh
cd build-week-back/buildtest
npm ci
npm start
```

## Cronologia e licenza

Progetto originariamente ospitato in `andbardii/build-week-back`, ora integrato in questa raccolta. La repository separata è stata eliminata dopo la migrazione. La cronologia originale è conservata nella raccolta; il tag `migration/build-week-back` identifica l’ultimo commit importato.

Vedi la [cronologia della raccolta](../README.md#provenienza-e-cronologia) e la [licenza del progetto](LICENSE).
