# 📄 Cahier des charges – Projet AsMind

## 🧠 Nom du projet : AsMind

**AsMind** est un assistant de recherche intelligent, neuro-inclusif, conçu pour aider les utilisateurs — notamment **neurodivergents** (TDAH, TSA, dyslexie…) — à naviguer dans l’information de façon intuitive, claire et sans surcharge cognitive.

Il permet d’interroger plusieurs types de sources (PDF, texte brut, pages web…) via une interface douce, structurée et personnalisée.

---

## 🎯 Objectifs du projet

- 📄 Permettre à l’utilisateur de **téléverser et interroger des documents** (PDF, texte, liens…).
- 🔍 Utiliser **Algolia MCP** pour indexer les contenus de manière fine.
- 🧠 Intégrer **OpenAI GPT** pour répondre de façon naturelle, contextuelle et claire.
- 🌈 Offrir une interface **neuro-inclusive** avec personnalisation de la présentation (résumés, visuel, audio…).
- 💬 Mémoriser les échanges, faciliter la relecture et la compréhension.

---

## 💡 Cas d’usage clés

- Étudiant.e neurodivergent.e préparant un exposé en interrogeant plusieurs documents.
- Lecteur avec troubles de l’attention qui a besoin d’un **résumé simplifié** d’un rapport.
- Utilisateur qui veut retrouver ses **questions passées** liées à un sujet donné.
- Coach scolaire ou aidant souhaitant revoir les échanges avec un jeune.

---

## 👩‍💻 Stack technique

| Composant            | Technologie choisie           |
|----------------------|-------------------------------|
| Frontend             | React.js                      |
| Backend              | Node.js + Express             |
| Recherche sémantique | Algolia MCP Server            |
| IA conversationnelle | OpenAI GPT (API)              |
| Extraction PDF       | `pdf-parse` ou `pdf.js`       |
| Auth / stockage      | Firebase (optionnel)          |
| Hébergement Front    | Vercel                        |
| Hébergement Backend  | Render / Railway / Cyclic     |
| Versioning           | Git + GitHub                  |

---

## 🧩 Fonctionnalités principales

- ✅ Téléversement de plusieurs documents
- ✅ Extraction + découpage intelligent
- ✅ Indexation Algolia MCP
- ✅ Requête GPT via contexte Algolia
- ✅ UI adaptée (claire, apaisée)
- ✅ Résumé / format simplifié
- ✅ Historique des échanges
- ✅ Mode personnalisé selon profil cognitif
- 🔄 Possibilité de reprendre les conversations

---

```plaintext
👤 Utilisateur
↓
🎨 Interface Web (React)
↓
🔧 Backend (Express)
├── 📄 Extraction multi-source (PDF, texte, URL…)
├── 📦 Indexation Algolia MCP
├── 🤖 Requêtes OpenAI GPT (avec contexte)
└── 🧾 Historique + Personnalisation
```
