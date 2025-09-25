# Mélissa Formation - Plateforme de Formation Vidéo

Une plateforme moderne de formation vidéo construite avec React, TypeScript, et Express.js.

## 🚀 Fonctionnalités

- **Interface utilisateur moderne** avec React et TypeScript
- **Design responsive** optimisé pour tous les appareils
- **Système de modules** avec progression des cours
- **Lecteur vidéo intégré** avec modal de lecture
- **Dashboard complet** avec statistiques de progression
- **Système de ressources** pour les documents complémentaires
- **Authentification** avec session management
- **Base de données** avec Drizzle ORM

## 🛠️ Technologies Utilisées

### Frontend
- **React 18** avec TypeScript
- **Vite** pour le build et le développement
- **React Router** pour la navigation
- **Tailwind CSS** pour le styling
- **Radix UI** pour les composants
- **Framer Motion** pour les animations
- **React Query** pour la gestion des données

### Backend
- **Express.js** avec TypeScript
- **Drizzle ORM** pour la base de données
- **Passport.js** pour l'authentification
- **WebSocket** pour les fonctionnalités temps réel

### Base de Données
- **PostgreSQL** avec Neon
- **Drizzle Kit** pour les migrations

## 📦 Installation

1. **Cloner le dépôt**
   ```bash
   git clone https://github.com/MorganGIT3/M-lissaForma.git
   cd M-lissaForma
   ```

2. **Installer les dépendances**
   ```bash
   npm install
   ```

3. **Configuration de l'environnement**
   ```bash
   # Créer un fichier .env.local
   cp .env.example .env.local
   ```

4. **Configurer la base de données**
   ```bash
   npm run db:push
   ```

5. **Lancer le développement**
   ```bash
   npm run dev
   ```

## 🚀 Déploiement sur Vercel

### Configuration automatique
Le projet est configuré pour un déploiement automatique sur Vercel :

1. **Connecter le dépôt GitHub** à Vercel
2. **Configurer les variables d'environnement** dans Vercel
3. **Déployer** automatiquement

### Variables d'environnement requises
```env
DATABASE_URL=your_database_url
SESSION_SECRET=your_session_secret
NODE_ENV=production
```

## 📁 Structure du Projet

```
├── client/                 # Application React frontend
│   ├── src/
│   │   ├── components/     # Composants réutilisables
│   │   ├── pages/         # Pages de l'application
│   │   ├── hooks/         # Hooks personnalisés
│   │   └── lib/           # Utilitaires et configuration
├── server/                # API Express backend
│   ├── routes.ts          # Routes API
│   └── index.ts           # Point d'entrée serveur
├── shared/                # Code partagé
│   ├── types.ts           # Types TypeScript
│   ├── schema.ts          # Schémas de base de données
│   └── mockData.ts        # Données de test
└── attached_assets/       # Assets et images
```

## 🎨 Design System

Le projet utilise un design system cohérent avec :
- **Couleurs** : Palette moderne et professionnelle
- **Typographie** : Hiérarchie claire et lisible
- **Composants** : Bibliothèque de composants réutilisables
- **Animations** : Transitions fluides et engageantes

## 📱 Pages Principales

- **Landing Page** : Page d'accueil avec présentation
- **Dashboard** : Tableau de bord utilisateur
- **Modules** : Liste des modules de formation
- **Module Detail** : Détail d'un module avec vidéos
- **Resources** : Ressources complémentaires
- **Profile** : Profil utilisateur

## 🔧 Scripts Disponibles

```bash
npm run dev          # Lancer en mode développement
npm run build        # Build de production
npm run start        # Lancer en mode production
npm run check        # Vérification TypeScript
npm run db:push      # Synchroniser la base de données
```

## 🤝 Contribution

1. Fork le projet
2. Créer une branche feature (`git checkout -b feature/AmazingFeature`)
3. Commit les changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 📞 Contact

Morgan - [@MorganGIT3](https://github.com/MorganGIT3)

Lien du projet : [https://github.com/MorganGIT3/M-lissaForma](https://github.com/MorganGIT3/M-lissaForma)
