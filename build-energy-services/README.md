# Energy Services

Progetto full stack per la gestione di una società di servizi energetici.

Parte di [**EPICODE Bootcamp**](../README.md), nella cartella `build-energy-services/`.

## Tecnologie

Angular 16, Java 17, Spring Boot, PostgreSQL.

## Struttura e utilizzo

Backend: [`energy/`](energy/). Frontend: [`energyfront/`](energyfront/). La collection Postman è in [`EnergyServices.postman_collection.json`](EnergyServices.postman_collection.json).

Dalla radice della raccolta, in due terminali:

```sh
cd build-energy-services/energy
sh mvnw spring-boot:run
```

```sh
cd build-energy-services/energyfront
npm ci
npm start
```

Configura un database PostgreSQL locale e le impostazioni del backend prima dell’avvio.

## Cronologia e licenza

Progetto originariamente ospitato in `andbardii/build-energy-services`, ora integrato in questa raccolta. La repository separata è stata eliminata dopo la migrazione. La cronologia originale è conservata nella raccolta; il tag `migration/build-energy-services` identifica l’ultimo commit importato.

Vedi la [cronologia della raccolta](../README.md#provenienza-e-cronologia) e la [licenza del progetto](LICENSE).
