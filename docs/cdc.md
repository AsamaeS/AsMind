# 📄 Cahier des charges – Projet AsMind

## 🧠 Nom du projet : AsMind

**AsMind** est un assistant intelligent capable de lire, comprendre et répondre à des documents PDF (ex. : notes de cours, articles, rapports), en combinant les technologies **Algolia MCP** et **OpenAI GPT**.

---

## 🎯 Objectif du projet

Créer une application web permettant à un utilisateur de :
- Uploader un document PDF
- Indexer son contenu grâce à **Algolia MCP**
- Poser des questions en langage naturel
- Recevoir des réponses précises grâce à **OpenAI GPT**, basées sur le contenu du PDF

---

## 👩‍💻 Stack technique

- **Backend** : Node.js + Express
- **Moteur de recherche** : Algolia MCP Server
- **IA** : OpenAI GPT (API)
- **Frontend** : React.js (à venir)
- **Extraction PDF** : pdf.js ou pdf-parse
- **Hébergement** : GitHub + Vercel (ou Render)

---

## 🧩 Fonctionnalités principales

- [x] Interface simple d'upload de PDF
- [x] Extraction et découpage du contenu
- [x] Indexation des chunks via Algolia MCP
- [x] Recherche intelligente via GPT
- [ ] Historique des échanges (bonus)
- [ ] Mode nuit (UX bonus)

---

## 📐 Architecture prévue

