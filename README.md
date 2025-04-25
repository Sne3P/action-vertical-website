# Action Verticale Club - Web Platform


https://github.com/user-attachments/assets/8b8a09b9-d06f-4529-a727-c6a46f260107



Bienvenue dans le dépôt du site web **Action Verticale Club**, une plateforme web moderne développée avec **Next.js**, **TypeScript**, **Tailwind CSS** et **Prisma**. Cette application est conçue pour offrir une expérience fluide, interactive et fonctionnelle pour la gestion, la communication et l’engagement communautaire autour des activités du club.

## 🔧 Stack technique

- **Framework principal** : Next.js 15
- **Langage** : TypeScript
- **Base de données** : Prisma (SQLite en dev)
- **Styling** : Tailwind CSS 3
- **Authentification** : Kinde Auth + NextAuth
- **Stockage & Upload** : Uploadthing, @vercel/blob, Multer
- **UI & Animation** : Framer Motion, Flowbite, HeadlessUI
- **3D & Visualisation** : @react-three/fiber, drei, @google/model-viewer
- **PDF & Éditeur** : React PDF, Froala WYSIWYG, React Quill
- **Autres outils** : Axios, Lodash, React Hook Form, Recharts, React Select

## 📁 Structure du projet

```
action-vertical-website-main/
├── prisma/                  # Fichiers de base de données Prisma (dev.db, schema.prisma)
├── public/                  # Ressources statiques
├── src/
│   ├── app/                 # Pages (architecture app directory Next.js)
│   ├── components/          # Composants UI
│   ├── lib/                 # Fonctions utilitaires, logique métier
│   ├── styles/              # Fichiers CSS/Tailwind
│   ├── types/               # Déclarations de types TS
│   ├── hooks/               # Custom React Hooks
│   └── ...
├── .eslintrc.json           # Configuration ESLint
├── tailwind.config.ts       # Configuration Tailwind
├── next.config.mjs          # Configuration Next.js
├── tsconfig.json            # Configuration TypeScript
├── package.json             # Dépendances et scripts
```

## 🚀 Démarrage rapide

### Prérequis
- Node.js 18+
- Yarn ou npm

### Installation
```bash
git clone https://github.com/USERNAME/action-vertical-website.git
cd action-vertical-website
yarn install
```

### Lancer en dev
```bash
yarn dev
```

### Build de production
```bash
yarn build
yarn start
```

### Base de données (Prisma)
```bash
yarn prisma generate
yarn prisma migrate dev
```

## 🔐 Authentification
Le projet intègre deux systèmes d’authentification :
- **Kinde Auth** pour une solution OAuth centralisée
- **NextAuth** pour des cas d’usage personnalisés

## 📦 Fonctionnalités clés
- Système d’authentification sécurisé
- Gestion d’utilisateurs et de rôles
- Upload et traitement de fichiers (PDF, images, vidéos)
- Visualisation 3D d’objets (fibres, modèles .glb)
- Éditeurs de texte riche
- Dashboard avec graphiques, tableaux et KPIs
- Composants UI interactifs et responsifs

## 🤝 Contribution
> Projet privé / interne — les contributions externes ne sont pas activement recherchées pour le moment.

## 🛠 À venir
- Intégration de tests automatisés (Jest, Cypress)
- Documentation technique API + endpoints
- Internationalisation (i18n)

## 📄 Licence
Ce projet est sous licence privée. Toute reproduction ou utilisation non autorisée est interdite.

---
Développé par [Ton Nom / Équipe Dev Action Verticale]

