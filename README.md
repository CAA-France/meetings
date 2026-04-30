# Comptes-rendus de réunions du CAA-FR

Voir, en ligne : <https://caafrance.hypotheses.org/comptes-rendus-caa-fr>.

## Compilation en PDF

Installer pandoc : <https://pandoc.org/>.

Nommer le fichier Markdown selon le modèle : `CAA-FR_compte-rendu_AAAAMMJJ.md` (remplacer `AAAAMMJJ` par la date de la réunion).

Ajouter l'entête suivant au fichier Markdown (penser à changer la date) : 

``` yml
---
author: https://caafrance.hypotheses.org
date: AAAA-MM-JJ
lang: fr
mainfont: 'Linux Libertine O'
secnumdepth: 2
title: CAA-FR. Compte-rendu de la réunion des membres CAA, JJ MM AAAA
toc: "yes"
toc-depth: 2
toccolor: teal
urlcolor: teal
---
```

Il peut être necessaire d'installer au préalable la font Linux Libertine sur votre machine : <https://libertine-fonts.org/>.

Compiler au format PDF :

``` bash
pandoc CAA-FR_compte-rendu_AAAAMMJJ.md --pdf-engine=xelatex -o CAA-FR_compte-rendu_AAAAMMJJ.pdf
```

## TODO

Simon : expliquer comment utiliser le workflow en quelques lignes
