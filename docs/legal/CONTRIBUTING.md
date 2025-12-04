# **CONTRIBUTING.md – KamieLabs Open Source Projects**

Bienvenue dans l’écosystème open-source **KamieLabs**.
Avant toute contribution, merci de lire attentivement ce document.

KamieLabs suit une architecture **workspace-first**, où tous les projets OSS (WSC, WSO, Kloud-OSS, etc.) dépendent du workspace racine :

👉 **[https://github.com/kamielabs/kamie-oss](https://github.com/kamielabs/kamie-oss)**

---

# 🔒 1. NDA & CLA obligatoires (avant toute contribution)

### **1) NDA (Confidentialité)**

Toute discussion technique *non encore publiée* nécessite un NDA signé.
Sans NDA → aucun détail sur la vision interne, la roadmap, ou les concepts non publiés.

### **2) CLA (Contributor License Agreement)**

Toute contribution nécessite la signature du CLA :

➡️ `docs/legal/CLA_fr.md`

Sans CLA → la contribution ne pourra pas être acceptée.

---

# 🧱 2. Structure générale

Toutes les contributions se font **dans un environnement workspace**.

```
kamie-oss/
 ├── projects/
 │    ├── wsc/
 │    ├── wso/
 │    └── ...
 ├── shared/
 ├── docs/
 ├── tsconfig.base.json
 ├── tsconfig.node.json
 └── ...
```

Chaque projet OSS est un **repo indépendant** mais dépend **du workspace KamieLabs** pour :

* la config TypeScript
* les conventions
* les scripts
* les shared libs
* les docs internes
* la cohérence globale

---

# 🛠️ 3. Comment contribuer

## **3.1 Fork + feature branch**

Toujours créer une branche à partir de `main` :

```
git checkout -b feature/<nom_de_la_feature>
```

Exemples :

* `feature/runtime-improvements`
* `fix/watcher-macos`
* `docs/update-cli-readme`

Les branches doivent être :

* courtes
* orientées résultat
* isolées (une feature à la fois)

---

## **3.2 Règles de code**

* TypeScript obligatoire
* Code 100% typé (no `any`)
* Zod pour toute validation
* Pas d'import relatifs hors dossier (use tsconfig paths)
* Log propre via LogManager
* Aucun secret / clé / endpoint stocké en dur
* Tests unitaires si la feature modifie du core

---

## **3.3 Commits**

Format recommandé :

```
[type] Message clair en anglais
```

Types possibles :

* feat
* fix
* refactor
* docs
* test
* chore

Exemples :

```
feat: add runtime panic handler
fix: stabilize watcher events on Linux
docs: update workspace installation guide
```

---

## **3.4 Pull Requests**

Une PR doit contenir :

* un titre clair
* une description courte
* la liste des changements
* les impacts éventuels
* les tests
* le lien vers l’issue si applicable

Les PR sont **review obligatoire** avant merge.

---

# 🧪 4. Tests

* Tests unitaires dans `projects/<app>/ts/tests/`
* Tests reproductibles : pas de dépendance réseau
* `pnpm test` doit passer avant PR

---

# ⚠️ 5. Interdictions formelles

❌ pas de code propriétaire d’entreprise tierce
❌ pas de dépendances non validées
❌ pas de publication de roadmap interne
❌ pas de reverse engineering des binaires KamieLabs
❌ pas de copie/portage du design ou des concepts en externe

---

# 🙌 6. Merci

Merci de contribuer à l’écosystème KamieLabs.
Votre participation fait progresser un projet orienté :

* souveraineté
* qualité
* long terme
* simplicité
* transparence

Pour toute question : ouvrir une discussion ou contacter un maintainer.

---
