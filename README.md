# **KamieLabs – Open Source Workspace (kamie-oss)**

Ce dépôt contient le **workspace racine obligatoire** pour tous les projets open-source de KamieLabs :

* WSC — Workspace CLI
* WSO — Workspace Orchestrator
* Kloud OSS tools
* Shared libraries
* Configurations globales
* Documentation interne

Tous les projets OSS KamieLabs **dépendent structurellement de ce workspace**.

---

# 📦 1. Installation du Workspace

### Prérequis

* Node 20+
* pnpm 9+
* Linux / macOS recommandés

### Installation

```bash
git clone git@github.com:kamielabs/kamie-oss.git
cd kamie-oss
pnpm install
```

---

# 🧱 2. Structure

```
kamie-oss/
 ├── projects/         # projets OSS clonés ici (wsc, wso, etc.)
 ├── shared/           # libs transversales
 ├── docs/             # documentation interne + légale
 ├── tsconfig.base.json
 ├── tsconfig.node.json
 └── pnpm-workspace.yaml
```

---

# 🚀 3. Ajouter un projet OSS (ex: WSC)

Depuis la racine :

```bash
cd projects
git clone git@github.com:kamielabs/wsc.git
```

Le projet devient automatiquement intégré au workspace.

---

# 🧪 4. Scripts généraux

```bash
pnpm build     # build multi-projet
pnpm test      # tests globaux
pnpm lint      # lint workspace
```

Les projets individuels peuvent avoir leurs propres scripts.

---

# 🔒 5. Légalité : NDA + CLA

Toute contribution nécessite :

* **NDA** (confidentialité) → docs/legal/NDA_fr.md
* **CLA** (cession de droits) → docs/legal/CLA_fr.md

Aucune PR ne sera acceptée sans ces documents.

---

# 📚 6. Documents importants

* **CONTRIBUTING.md** → règles de contribution
* **docs/** → documentation interne
* **shared/** → librairies transversales
* **projects/** → dossiers projets (vides avant clonage)

---

# 🙌 7. Vision

KamieLabs développe :

* un écosystème souverain
* un workflow complet (CLI → API → SaaS)
* une base de code unifiée
* des outils de productivité pour devs
* des solutions cloud modernes

Ce workspace est la fondation de tout l’écosystème.

---