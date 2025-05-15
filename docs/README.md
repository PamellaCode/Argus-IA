# Documentation Technique ArgusAI

## 📚 Table des matières

1. [Architecture](#architecture)
2. [Installation](#installation)
3. [Configuration](#configuration)
4. [Utilisation](#utilisation)
5. [Déploiement](#déploiement)
6. [Maintenance](#maintenance)

## 🏗️ Architecture

### Frontend
- React avec TypeScript
- Tailwind CSS pour le style
- Shadcn UI pour les composants
- React Router pour la navigation
- Tanstack React Query pour la gestion des données

### Backend
- API SIV pour les données véhicules
- GPT-4 pour l'analyse des données
- n8n pour l'automatisation
- Supabase pour la base de données

### Flux de données
1. L'utilisateur entre une plaque d'immatriculation
2. L'API SIV récupère les informations du véhicule
3. GPT-4 analyse les données et les annonces similaires
4. n8n orchestre le processus d'estimation
5. Le résultat est affiché à l'utilisateur

## 🔧 Installation

### Prérequis
- Node.js 18+ LTS
- npm 8+ ou yarn 1.22+
- Git LFS
- Compte Supabase
- Accès API SIV
- Clé API OpenAI

### Étapes d'installation
1. Cloner le repository
2. Installer les dépendances
3. Configurer les variables d'environnement
4. Initialiser la base de données
5. Lancer l'application

## ⚙️ Configuration

### Variables d'environnement
```env
# Supabase
SUPABASE_URL=
SUPABASE_ANON_KEY=

# API SIV
SIV_API_KEY=

# OpenAI
OPENAI_API_KEY=

# n8n
N8N_WEBHOOK_URL=

# Application
NEXT_PUBLIC_APP_URL=
NODE_ENV=
```

### Base de données
- Tables Supabase nécessaires
- Schéma de données
- Indexes et relations

## 🚀 Utilisation

### Fonctionnalités principales
1. Estimation de véhicule
2. Tableau de bord
3. Historique des estimations
4. Statistiques
5. Assistant IA

### API Endpoints
- `/api/estimate` : Estimation de véhicule
- `/api/history` : Historique des estimations
- `/api/stats` : Statistiques
- `/api/assistant` : Assistant IA

## 🚢 Déploiement

### Environnements
- Développement
- Staging
- Production

### Procédure de déploiement
1. Build de l'application
2. Tests automatisés
3. Déploiement sur Vercel/Netlify
4. Vérification post-déploiement

## 🔄 Maintenance

### Mises à jour
- Procédure de mise à jour
- Gestion des dépendances
- Tests de régression

### Monitoring
- Logs
- Métriques
- Alertes

### Sauvegarde
- Base de données
- Fichiers statiques
- Configuration

## 📝 Notes de développement

### Bonnes pratiques
- Convention de nommage
- Structure des composants
- Gestion des erreurs
- Tests unitaires

### Workflow Git
- Branches
- Commits
- Pull requests
- Code review 