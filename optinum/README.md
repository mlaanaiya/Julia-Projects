# Optinum

## Mise à jour des tests unitaires

Afin de tester vos codes il faut faire une mise à jour d'optinum. 

- Déplacer les fichiers de `src` que vous avez modifiés (`Algorithme_De_Newton.jl`, ...)

- Dans votre répertoire `optinum` tapez :
 
`> git pull`

- Remettre les fichiers déplacés dans `src`

Vous obtiendrez alors dans le répertoire test un fichier `new_runtests.jl` qu'il suffira de lancer.


## récupération d'Optinum
Pour récupérer Optinum, il faut cloner ce dépot git : 

`> git clone https://gitlab.irit.fr/toc/mathn7/optimisation-numerique/optinum.git`

Ensuite, pour accéder au sujet du TP ouvrir

`optinum/docs/build/index.html`

optinum/src contient le corps (à compléter) des algorithmes d'optimisation vus en cours d'Optimisation Numérique.


#### Fichiers à ne pas modifier : 
   * `src/Optinum.jl`
   * `test/runtests.jl`
   * `Project.toml`
   * `Manifest.toml`
   * `docs/Project.toml`
   * `docs/Manifest.toml`
   * `docs/assets/`
