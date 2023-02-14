# Projet de stylométrie de Richy et Fanny

Le but de ce projet est de faire des sous-corpus du corpus des Mazarinades (https://github.com/Antonomaz/Corpus/tree/main/Mazarinades), en s'intéressant notamment à la proportion en vers et en proses puis aux types de vers selon leur métrique.

## Organisation de l'arborescence

- main.ipynb : parsing des XML, séparation prose/vers (avec stats), stockage des textes en vers dans un JSON externe

- index.xqm : script XQUERY de Xavier Laurent Salvador (https://github.com/humanitesnumeriques/outilDeSyllabation), finalement pas exploité

- french-syllabification/ : dossier cloné de https://github.com/ian-nai/french-syllabification MAIS contenant aussi nos adaptations de scripts (notamment, le plus important, **main_syllabation2.ipynb**)

- output/ : dossier contenant les fichiers JSON générés par main.ipynb et main_syllabation2.ipynb (dictionnaire avec tous les vers, dictionnaires avec les découpes en syllabes, dictionnaires avec les comptages de syllabes par vers)

- Mazarinades/ : notre corpus, cloné de https://github.com/Antonomaz/Corpus/tree/main/Mazarinades

