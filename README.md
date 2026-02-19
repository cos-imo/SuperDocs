# 📚 SuperDocs

[![Static Badge](https://img.shields.io/badge/Licence-MIT-blue?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLXphei0tPgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgaGVpZ2h0PSIxNjYiIHdpZHRoPSIzMjEiPgo8ZyBzdHJva2Utd2lkdGg9IjM1IiBzdHJva2U9IiNBMzFGMzQiPgo8cGF0aCBkPSJtMTcuNSwwdjE2Nm01Ny0xNjZ2MTEzbTU3LTExM3YxNjZtNTctMTY2djMzbTU4LDIwdjExMyIvPgo8cGF0aCBkPSJtMTg4LjUsNTN2MTEzIiBzdHJva2U9IiM4QThCOEMiLz4KPHBhdGggZD0ibTIyOSwxNi41aDkyIiBzdHJva2Utd2lkdGg9IjMzIi8+CjwvZz4KPC9zdmc+Cg==)](https://choosealicense.com/licenses/mit/)
[![Static Badge](https://img.shields.io/badge/-Markdown-000000?logo=markdown)](https://www.markdownguide.org/)
[![Static Badge](https://img.shields.io/badge/-mdbooks-orange?logo=mdbook)](https://rust-lang.github.io/mdBook/)   

[![Accès au site SuperDocs](https://img.shields.io/badge/📚_SuperDocs-Visiter%20le%20site-blue?style=for-the-badge)](https://superdocs.cosimoungaro.fr/Accueil.html)

---

## Sommaire

1. [Présentation](#présentation)
2. [Objectif et usage](#objectif-et-usage)
3. [Installation](#installation)
4. [Organisation des contenus](#organisation-des-contenus)
5. [Note de prudence](#note-de-prudence)
6. [Contribuer](#contribuer)

---

## Présentation

**SuperDocs** est une **base de connaissances personnelle** centrée sur la cybersécurité, mais extensible à d’autres domaines.  
L’objectif est de **centraliser, organiser et conserver des ressources en ligne** dans un format structuré et durable, plus exploitable qu’un simple système de favoris de navigateur.

SuperDocs fonctionne sous forme de fichiers Markdown et peut être consulté avec n’importe quel lecteur Markdown ou via GitHub Pages.

---

## Usage

Chaque section est organisée de façon hiérarchique et respecte les domaines suivants :

- Cyber (Blue Team)
- Dev & DevOps
- Low Level / Reverse Engineering
- Malware Analysis
- Networking
- Pentest (avec Docs, Labs, Lists, Tools, Playbooks, Cheatsheets)

---

## Installation

### Téléchargement

###### Par SSH
```bash
git clone git@github.com:cos-imo/SuperDocs.git
````

###### Par HTTPS

```bash
git clone https://github.com/cos-imo/SuperDocs.git
```

### Utilisation

SuperDocs est un **dépôt Markdown**, aucune installation complexe n’est nécessaire : il suffit d’ouvrir les fichiers avec votre éditeur préféré ou via GitHub Pages.

Pour utiliser le mdbook en local (mdbook doit être péréalablement installé):
```sh
mdbook serve
```

---

## Organisation des contenus

La base est structurée par dossiers et fichiers :

- `Accueil.md` – page d’accueil
- `dev/` – documentation et outils pour le développement
- `devops/` – documentation DevOps
- `forensics/` – analyse forensique
- `low level/` – programmation bas-niveau, assembly, reverse
- `malware/` – outils et analyses de malware
- `networking/` – documentation réseau
- `pentest/` – documentation et outils pentest, labs, playbooks, write-ups, listes

Chaque sous-dossier contient des fichiers **Markdown** pour les documents, outils et ressources correspondantes.  

---

## Note de prudence


> [!NOTE]  
> SuperDocs est un produit **personnel**, je ne garantis ni la fiabilité, ni l’actualité, ni la complétude des liens et ressources listées.  
> Utilisez les contenus avec discernement, dans un cadre légal et dans un environnement sécurisé.

---

## Contribuer

Vous pouvez proposer des améliorations ou extensions :

1. Fork le dépôt
2. Créez une branche pour vos modifications
3. Ajoutez ou corrigez des fichiers Markdown
4. Soumettez une Pull Request

---

**Bonne lecture !**

---
