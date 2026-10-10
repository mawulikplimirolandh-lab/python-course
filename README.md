# 🐍 Cours de Python — De l'Algorithmique à la POO

> Formation complète en français : **manuel de référence + cours intensif 24 heures**
> (12 séances de 2 h : 1 h de cours en diapositives + 1 h de pratique en Notebook Jupyter)

**Auteurs :** HOUNKPE Mawulikplimi Roland & DJABON Ounimborbitibou

---

## 📦 Contenu du dépôt

```
python-course/
│
├── manuel-tome-1/            Manuel complet (99 pages, PDF)
│   ├── Cours_Python_Tome_1_Algorithmique_vers_POO.pdf
│   └── couverture_Tome1_source.html
│
├── formation-24h/            Cours intensif 24 h (12 séances)
│   ├── 00_Planning_formation_24h.pdf   ← commencer ici
│   ├── slides/               12 présentations Beamer (PDF)
│   ├── slides-sources/       12 sources LaTeX (.tex)
│   ├── notebooks/            12 notebooks Jupyter (.ipynb)
│   └── videos/               Vidéos des séances (MP4 sous-titré)
│
└── packs/
    └── Pack_Complet_Python_24h.zip     Tout le pack en un seul fichier
```

---

## 📘 Le Manuel — Tome 1 (99 pages)

Un manuel progressif en 5 parties et 21 chapitres, avec 27 exercices corrigés :

| Partie | Contenu |
|--------|---------|
| **I. Penser comme une machine** | Algorithmes, boucles, premiers programmes |
| **II. Les fondamentaux** | Variables, types, conditions, boucles `for`/`while` |
| **III. Structures de données** | Listes, tuples, dictionnaires, sets, compréhensions |
| **IV. Fonctions & fichiers** | Fonctions, portée, closures, décorateurs, fichiers |
| **V. Programmation orientée objet** | Classes, encapsulation, héritage, MRO, méthodes spéciales |
| **VI. Erreurs, exceptions & débogage** | Gestion d'erreurs, `try/except`, débogage méthodique |

Points forts : sommaire cliquable, exercices progressifs avec solutions détaillées,
accent mis sur la **pensée algorithmique** avant la syntaxe.

---

## ⏱️ La Formation 24 h — 12 séances de 2 h

Chaque séance = **1 h de cours** (diapositives Beamer) + **1 h de pratique**
(notebook Jupyter avec 5 exercices : 2 basiques, 2 intermédiaires, 1 défi — corrigés en fin de notebook).

| # | Séance | Slides | Notebook |
|---|--------|:------:|:--------:|
| 01 | Penser comme une machine | ✅ | ✅ |
| 02 | Boucles et algorithmes | ✅ | ✅ |
| 03 | Variables et types | ✅ | ✅ |
| 04 | Conditions et boucles Python | ✅ | ✅ |
| 05 | Listes, tuples et compréhensions | ✅ | ✅ |
| 06 | Dictionnaires, sets et fonctions | ✅ | ✅ |
| 07 | Closures, décorateurs et fichiers | ✅ | ✅ |
| 08 | Classes et encapsulation | ✅ | ✅ |
| 09 | Héritage et méthodes spéciales | ✅ | ✅ |
| 10 | Mini-projet bancaire | ✅ | ✅ |
| 11 | Erreurs et exceptions | ✅ | ✅ |
| 12 | Débogage et synthèse | ✅ | ✅ |

🎥 **Vidéos** : les séances 01 et 02 sont disponibles en vidéo MP4 720 p
(narration française native, sous-titres incrustés, ~9 min chacune).
Chaque vidéo s'ouvre sur une carte « Likez + Abonnez-vous ».
Les suivantes suivront le même format, une par une.

---

## 🚀 Comment utiliser ce cours

1. **Découvrir** → ouvrir `formation-24h/00_Planning_formation_24h.pdf`
2. **Assister / réviser** → lire les slides PDF de la séance (ou regarder la vidéo)
3. **Pratiquer** → ouvrir le notebook correspondant :

```bash
pip install jupyter
jupyter notebook formation-24h/notebooks/Seance_01_penser_comme_une_machine.ipynb
```

4. **Approfondir** → consulter le chapitre lié dans le manuel Tome 1
5. **Auto-évaluer** → exécuter les cellules de test `assert` en fin de notebook

---

## 🛠️ Compilation des slides (optionnel)

Les sources LaTeX sont fournies pour personnaliser les présentations :

```bash
pdflatex formation-24h/slides-sources/Seance_01_penser_comme_une_machine.tex
```

---

## 📄 Licence & crédits

Cours original rédigé en français par **HOUNKPE Mawulikplimi Roland**
et **DJABON Ounimborbitibou**.
