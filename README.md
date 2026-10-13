# EPICODE Bootcamp

Esercizi, progetti e capstone del mio bootcamp EPICODE in sviluppo web full stack. Include anche esercizi complementari svolti su freeCodeCamp.

## Progetti

| Cartella | Contenuto | Tecnologie |
| --- | --- | --- |
| [front-stack](front-stack/) | Esercizi e progetti del percorso frontend EPICODE: HTML, CSS, JavaScript, TypeScript e Angular. | HTML, CSS, Sass, JavaScript, TypeScript, Angular |
| [back-stack](back-stack/) | Lezioni ed esercizi del percorso backend EPICODE, dalle basi di Java alle applicazioni Spring. | Java, Spring Boot, PostgreSQL, Hibernate |
| [weather-angular-app](weather-angular-app/) | Applicazione Angular per consultare il meteo tramite API esterne. | Angular 16, TypeScript, Sass, Bootstrap |
| [build-energy-services](build-energy-services/) | Progetto full stack per la gestione di una società di servizi energetici. | Angular 16, Java 17, Spring Boot, PostgreSQL |
| [capstone-hodle](capstone-hodle/) | Applicazione full stack per gestire portafogli e seguire investimenti, movimenti e andamento degli asset. | Angular 16, NgRx, Java 17, Spring Boot, PostgreSQL |
| [translate-angular-app](translate-angular-app/) | Applicazione Angular per tradurre testi tramite un servizio di traduzione esterno. | Angular 16, TypeScript, Sass, Bootstrap |
| [build-week-back](build-week-back/) | Progetto di gruppo per la gestione di un’agenzia di trasporto pubblico, con backend Java e frontend Angular. | Java 17, Hibernate, PostgreSQL, Angular 16 |
| [free-code-camp](free-code-camp/) | Esercizi personali di Responsive Web Design svolti su freeCodeCamp, raccolti insieme ai materiali del bootcamp. | HTML, CSS |
| [linktree-clone](linktree-clone/) | Pagina personale di collegamenti ispirata a Linktree. | HTML, CSS, JavaScript |

## Utilizzo

```sh
git clone https://github.com/andbardii/epicode-bootcamp.git
cd epicode-bootcamp
```

Ogni progetto mantiene la propria struttura e le proprie dipendenze. Consulta il README della cartella scelta per i percorsi di avvio; non esiste una build comune alla raccolta. Le versioni dei framework sono quelle dei progetti didattici originali.

## Cronologia e licenze

Le repository originali sono state importate con `git subtree`, senza squash: commit, autori, date e identificativi originali restano nella cronologia. I tag `migration/<nome-progetto>` identificano il punto di importazione. I riferimenti e i comandi di consultazione sono riportati sotto, nella sezione [Provenienza e cronologia](#provenienza-e-cronologia).

Ogni progetto conserva il proprio file `LICENSE` e le relative attribuzioni.

## Provenienza e cronologia

Migrazione del 13 ottobre 2026. Importazioni tramite `git subtree add`, senza `--squash` e senza riscrivere la cronologia. Gli hash originali restano invariati.

| Progetto | Repository originale | Branch | Commit importato | Tag |
| --- | --- | --- | --- | --- |
| [front-stack](front-stack/) | `andbardii/front-stack` | `master` | `a4af3ad08bcbb9a47835f3ecb6ac9d91595cb4c9` | `migration/front-stack` |
| [back-stack](back-stack/) | `andbardii/back-stack` | `main` | `ae83f786559a92be071f37515b1540bde366b5a7` | `migration/back-stack` |
| [weather-angular-app](weather-angular-app/) | `andbardii/weather-angular-app` | `main` | `9c81515ce1b3782fd2700688a287d5841001b6c1` | `migration/weather-angular-app` |
| [build-energy-services](build-energy-services/) | `andbardii/build-energy-services` | `main` | `065e640ef150c61e8c7ec2ce81de45f47001fc0d` | `migration/build-energy-services` |
| [capstone-hodle](capstone-hodle/) | `andbardii/capstone-hodle` | `main` | `4b0bab2c132dbe21654cb2f2a043dcfea7598330` | `migration/capstone-hodle` |
| [translate-angular-app](translate-angular-app/) | `andbardii/translate-angular-app` | `main` | `b6ce6d84515f8b9f922cfcee6ccfe14f14f73bd4` | `migration/translate-angular-app` |
| [build-week-back](build-week-back/) | `andbardii/build-week-back` | `main` | `3cca118990ed4d5c622157230545ddac97e1aa59` | `migration/build-week-back` |
| [free-code-camp](free-code-camp/) | `andbardii/free-code-camp` | `main` | `b4f2eaf225f820cd82879fa56b394ff9ca4ddab5` | `migration/free-code-camp` |
| [linktree-clone](linktree-clone/) | `andbardii/linktree-clone` | `main` | `cedb904a44204eba8b4281aa262bbbe7591682ee` | `migration/linktree-clone` |

### Consultare i commit originali

```sh
# Cronologia completa della raccolta e dei progetti importati
git log --all --graph --oneline

# Cronologia originale di un progetto, prima della migrazione
git log migration/front-stack

# Modifiche alla cartella dopo l’importazione
git log -- front-stack/
```

Prima dell’importazione i file erano nella radice delle singole repository: un filtro sul nuovo percorso non mostra da solo tutti i commit precedenti. Usa il tag di migrazione per consultarli con i percorsi originali.

Le repository sorgenti sono state eliminate dopo la verifica dell’importazione. Un’importazione Git conserva commit e file, ma non trasferisce issue, pull request e release su GitHub. Le licenze di ciascun progetto sono conservate.
