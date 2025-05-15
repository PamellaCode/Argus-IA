# ArgusAI - Estimation Automatisée de Véhicules

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub release](https://img.shields.io/github/release/PamellaCode/argus-ia.svg)](https://github.com/PamellaCode/argus-ia/releases)
[![Documentation](https://img.shields.io/badge/docs-latest-blue.svg)](https://github.com/PamellaCode/argus-ia/tree/main/docs)
[![GitHub issues](https://img.shields.io/github/issues/PamellaCode/argus-ia.svg)](https://github.com/PamellaCode/argus-ia/issues)
[![GitHub stars](https://img.shields.io/github/stars/PamellaCode/argus-ia.svg)](https://github.com/PamellaCode/argus-ia/stargazers)

ArgusAI est une application web moderne qui permet d'estimer automatiquement la valeur d'un véhicule à partir de sa plaque d'immatriculation. Ce projet a été développé dans le cadre d'un stage.

## 🚀 Fonctionnalités

- Estimation intelligente basée sur l'analyse d'annonces en temps réel
- Interface utilisateur moderne et responsive
- Intégration avec l'API SIV
- Utilisation de GPT-4 pour l'analyse des données
- Automatisation via n8n
- Tableau de bord complet avec statistiques

## 🛠️ Technologies Utilisées

- Frontend : React, TypeScript, Tailwind CSS, Shadcn UI
- Backend : API SIV, GPT-4, n8n
- Base de données : Supabase
- Autres : React Router, Tanstack React Query

## 📋 Prérequis

- Node.js (version LTS recommandée)
- npm ou yarn
- Compte Supabase
- Accès à l'API SIV
- Clé API GPT-4

## 🔧 Installation

1. Cloner le repository :
```bash
git clone https://github.com/votre-username/argus-ia.git
cd argus-ia
```

2. Installer les dépendances :
```bash
npm install
# ou
yarn install
```

3. Configurer les variables d'environnement :
```bash
cp .env.example .env
# Remplir les variables dans .env
```

4. Lancer l'application en mode développement :
```bash
npm run dev
# ou
yarn dev
```

## 📝 Structure du Projet

```
argus-ia/
├── src/
│   ├── components/    # Composants React
│   ├── pages/        # Pages de l'application
│   ├── styles/       # Fichiers CSS
│   ├── utils/        # Utilitaires
│   └── api/          # Services API
├── public/           # Fichiers statiques
└── ...
```

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
1. Fork le projet
2. Créer une branche pour votre fonctionnalité
3. Commiter vos changements
4. Pousser vers la branche
5. Ouvrir une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👤 Contact

Pamella Defrend - defrendpamella@gmail.com

## 🙏 Remerciements

- Tous les contributeurs qui ont participé au projet
- Les outils open source utilisés
- La communauté de développeurs 