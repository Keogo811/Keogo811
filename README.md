# Salut, moi c'est Hugo (Keogo/Heina) 👋

**Étudiant Junior en Intelligence Artificielle à Aivancity | Développeur Full-Stack & ML**

J'aime construire des systèmes qui résolvent des problèmes concrets. Ma philosophie de travail est simple : **une solution fiable et simple vaut mieux que 20 solutions complexes.** Je m'intéresse particulièrement à l'intégration de LLM, à la sécurité applicative et à la rigueur en Machine Learning.

---

## 🚀 Mes Projets Phares

### 🔬 [Student Lighthouse](https://github.com/Keogo811/student-lighthouse)
*L'ingénierie Machine Learning appliquée à un problème humain réel.*
*   **Le contexte :** Aider une université à identifier les 200 étudiants les plus à risque de décrochage avant la fin du premier semestre.
*   **Décision clé :** Suppression stricte de toutes les données du semestre 2 (*temporal leakage*) pour garantir la fiabilité en production. Utilisation de la métrique PR-AUC au lieu de l'accuracy pour gérer le déséquilibre des classes.
*   **Limite assumée :** Le modèle ne voit que des données quantitatives (pas de dépression ou de problèmes familiaux). L'outil est une aide à la décision, pas un verdict.

### 🏥 [Institut Rafael (Projet d'équipe)](https://github.com/alajemba-vik/rafael-patient-journey)
*Refonte UI/UX et développement du portail patient d'une application de santé.*
*   **Le contexte :** Environnement de production strict avec travail en équipe (Git, branches, Pull Requests).
*   **Décision clé :** Création d'un design system complet ("Warm UI") et implémentation de graphiques de données (Donut, Barres) en SVG pur et CSS, sans aucune librairie externe (pas de Chart.js).
*   **Limite assumée :** Dépendance forte à une CI/CD stricte (ESLint, Prettier, Playwright) qui a nécessité un temps d'adaptation, mais qui a garanti la qualité du code final.

### 🎓 [Gradeeting](https://github.com/Keogo811/gradeeting)
*Plateforme communautaire pour Aivancity.*
*   **Le contexte :** Zéro budget, sécurité maximale, et intégration dans le sous-dossier du serveur du BDE.
*   **Décision clé :** Refus des liens magiques (limites du Free Tier) au profit d'une authentification par token (UUID). Implémentation stricte de la Row Level Security (RLS) sur Supabase pour séparer les anonymes et les admins.
*   **Limite assumée :** Pas de rate limiting pour l'instant (acceptable pour un projet scolaire), et monitoring basique (console).

### 🧠 [AEGINS](https://github.com/Keogo811/AEGINS)
*Architecture d'une IA autonome basée sur une mémoire faillible.*
*   **Le contexte :** Explorer l'émergence de l'identité et de la mémoire dans les LLM, en local et à budget zéro.
*   **Décision clé :** Architecture à 3 couches de mémoire (Journal brut, Résumé de soi, Identité fondatrice) pour éviter la "cristallisation" de l'identité. Routage dynamique entre modèles locaux (Ollama) et distants (Groq) selon la tâche.
*   **Limite assumée :** Absence de base vectorielle (RAG) pour l'instant. La mémoire est basée sur un scoring d'importance et la récence, choisie pour garder le système inspectable et maîtrisable.

---

## 🛠️ Stack Technique
*   **Langages :** Python, JavaScript, TypeScript, SQL, HTML5, CSS3
*   **Frontend :** React, Vite, Vanilla JS, SVG natif
*   **Backend & BDD :** FastAPI, Node.js, PostgreSQL, Supabase, Neon, Firebase
*   **IA & Data :** scikit-learn, Pandas, Intégration LLM (DeepSeek, Qwen, Claude), Ollama, LM Studio
*   **Outils :** Git, GitHub, Vercel, Netlify, Linux, VSCode

📫 **Me contacter :** [www.linkedin.com/in/hugo-kingkeomanivong-151467296] | [hkingkeoman@gmail.com]
