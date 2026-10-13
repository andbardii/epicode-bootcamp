# Migrazione in epicode-bootcamp

Migrazione del 13 ottobre 2026. Importazioni tramite `git subtree add`, senza `--squash` e senza riscrivere la cronologia. Gli hash originali restano invariati.

| Progetto | Repository originale | Branch | Commit importato | Tag |
| --- | --- | --- | --- | --- |
| [front-stack](front-stack/) | [andbardii/front-stack](https://github.com/andbardii/front-stack) | `master` | `a4af3ad08bcbb9a47835f3ecb6ac9d91595cb4c9` | `migration/front-stack` |
| [back-stack](back-stack/) | [andbardii/back-stack](https://github.com/andbardii/back-stack) | `main` | `ae83f786559a92be071f37515b1540bde366b5a7` | `migration/back-stack` |
| [weather-angular-app](weather-angular-app/) | [andbardii/weather-angular-app](https://github.com/andbardii/weather-angular-app) | `main` | `9c81515ce1b3782fd2700688a287d5841001b6c1` | `migration/weather-angular-app` |
| [build-energy-services](build-energy-services/) | [andbardii/build-energy-services](https://github.com/andbardii/build-energy-services) | `main` | `065e640ef150c61e8c7ec2ce81de45f47001fc0d` | `migration/build-energy-services` |
| [capstone-hodle](capstone-hodle/) | [andbardii/capstone-hodle](https://github.com/andbardii/capstone-hodle) | `main` | `4b0bab2c132dbe21654cb2f2a043dcfea7598330` | `migration/capstone-hodle` |
| [translate-angular-app](translate-angular-app/) | [andbardii/translate-angular-app](https://github.com/andbardii/translate-angular-app) | `main` | `b6ce6d84515f8b9f922cfcee6ccfe14f14f73bd4` | `migration/translate-angular-app` |
| [build-week-back](build-week-back/) | [andbardii/build-week-back](https://github.com/andbardii/build-week-back) | `main` | `3cca118990ed4d5c622157230545ddac97e1aa59` | `migration/build-week-back` |
| [free-code-camp](free-code-camp/) | [andbardii/free-code-camp](https://github.com/andbardii/free-code-camp) | `main` | `b4f2eaf225f820cd82879fa56b394ff9ca4ddab5` | `migration/free-code-camp` |
| [linktree-clone](linktree-clone/) | [andbardii/linktree-clone](https://github.com/andbardii/linktree-clone) | `main` | `cedb904a44204eba8b4281aa262bbbe7591682ee` | `migration/linktree-clone` |

## Consultare i commit originali

```sh
# Cronologia completa della raccolta e dei progetti importati
git log --all --graph --oneline

# Cronologia originale di un progetto, prima della migrazione
git log migration/front-stack

# Modifiche alla cartella dopo l’importazione
git log -- front-stack/
```

Prima dell’importazione i file erano nella radice delle singole repository: un filtro sul nuovo percorso non mostra da solo tutti i commit precedenti. Usa il tag di migrazione per consultarli con i percorsi originali.

Le repository sorgenti vengono conservate come archivi con un collegamento alla nuova posizione. Issue, pull request e release storiche rimangono nelle repository originali; non sono trasferite da un’importazione Git. Le licenze di ciascun progetto sono conservate.
