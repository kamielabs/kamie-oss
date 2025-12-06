# Kamie OSS — Vitrine Officielle du Projet Kamie (WIP)

Ce dépôt est la **vitrine institutionnelle** du projet **Kamie OSS**.

Il ne contient **aucun code technique**, aucun workspace, aucun module, et
ne doit jamais être utilisé comme environnement de développement.

Son rôle unique est d’héberger :

- la présentation officielle du projet
- la documentation publique générale
- les informations légales
- les guides contributeurs
- les instructions pour installer et utiliser les outils Kamie **une fois publiés**
- les liens vers les dépôts techniques (wsc, shared-core-cli, kamielabs, etc.)

---

## ⚠️ État du projet : Work In Progress

Les outils principaux du projet Kamie sont actuellement en cours de développement.
En particulier, l’outil maître `wsc` (Workspace CLI) n’est **pas encore** en version publique.

Tant que `wsc` n’est pas stabilisé :

- ce dépôt reste volontairement **minimal**
- aucune structure de workspace n’est fournie ici
- aucune installation “KamieLabs” n’est disponible
- les développeurs qui rejoignent le projet passent d’abord par la documentation et un échange direct

---

## 🎯 Rôle de ce dépôt

`kamie-oss` sert de **point central d’information**, pas de workspace.

Il fournit :

### ✔️ Vision globale
Architecture, philosophie, objectifs à long terme.

### ✔️ Documentation publique
Docs généralistes, concepts, explications haut niveau.

### ✔️ Cadre légal
Licences, NDA externes, éléments juridiques.

### ✔️ Guide pour contribuer
Comment rejoindre le projet, comment participer à KamieLabs une fois WSC prêt,
comment installer une version packagée ou en développement de la suite Kamie.

### ✔️ Liens vers les dépôts techniques
Liste claire et mise à jour lorsque WSC, shared-core-cli, KamieLabs
et autres repos deviennent publics.

---

## 🚫 Ce que ce dépôt **n'est pas**

- ❌ un workspace KamieLabs  
- ❌ un projet Node / Python / TypeScript  
- ❌ un environnement de développement  
- ❌ un dépôt contenant du code généré  
- ❌ une copie du runtime Kamie  

Aucun outil Kamie ne doit être développé dans ce repo.
Tout se passera dans les dépôts techniques dédiés, et/ou généré automatiquement par `wsc`.

---

## 🚧 Dépôts techniques (non inclus ici)

Ces repos seront documentés ici lorsque les versions publiques seront prêtes :

- **wsc** — Workspace CLI (l’outil maître qui génère et gère les workspaces)
- **shared-core-cli** — librairie commune aux outils Kamie
- **kamielabs** — workspace officiel généré par WSC (ne vit pas dans ce repo)
- **autres outils** — listés ultérieurement

---

## 📦 Installation & Dev (à venir)

Lorsque `wsc` sera publié, ce dépôt fournira :

- un **HowTo simple** pour installer une version packagée  
- un **HowTo dev** pour ceux qui veulent contribuer à KamieLabs  
- les **prérequis système**  
- la procédure pour installer la **version dev** de `wsc` localement  
- les commandes pour générer son premier workspace KamieLabs  

---

## 📚 Documentation

La documentation publique est disponible dans `./docs/`.  
Elle sera enrichie progressivement :

- architecture générale
- fonctionnement conceptuel
- guides contributeurs
- documentation légale

---

## 🤝 Participer

Pour le moment, la contribution technique se fait **sur invitation**  
(le socle WSC n’étant pas encore figé).

Ce dépôt reste cependant ouvert aux discussions, feedbacks,
et propositions portant sur :

- la vision du projet  
- la documentation  
- la structure globale Kamie OSS  

---

## 📜 Licence

En cours de rédaction.
