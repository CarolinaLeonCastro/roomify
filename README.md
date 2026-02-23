# Welcome to Roomify!
Roomify est une application SaaS de visualisation architecturale propulsée par l’IA, construite avec **React**, **TypeScript** et **Puter**.

Elle permet de transformer des plans 2D en rendus 3D photoréalistes, avec :

- hébergement permanent des fichiers et des rendus,
- métadonnées persistantes,
- historique de projets,
- et un flux communautaire global.

Les modèles d’IA utilisés incluent **Claude** et **Gemini**, pour gérer la transformation architecturale et la génération d’images.



## Features

👉 **Visualisation 2D → 3D**  
Transformation instantanée de plans 2D en modèles 3D photoréalistes grâce à l’IA.

👉 **Hébergement persistant des médias**  
Stockage permanent des fichiers avec URL publique pour chaque upload et chaque rendu.

👉 **Galerie de projets dynamique**  
Espace de travail personnel avec historique des visualisations, chargement instantané et métadonnées persistantes.

👉 **Comparaison côte à côte**  
Outils interactifs pour comparer directement le croquis architectural d’origine et son rendu généré par IA.

👉 **Flux communautaire global**  
Mur communautaire public où les utilisateurs partagent leurs projets architecturaux en un clic.

👉 **Contrôles de confidentialité**  
Gestion fine du mode public/privé pour chaque projet.

👉 **Gestion de la propriété**  
Système de métadonnées propre pour suivre les projets, utilisateurs et identifiants sur toute la plateforme.

👉 **Export moderne**  
Outils performants pour exporter les rendus et les intégrer dans des présentations ou workflows réels.

Et bien plus encore (architecture du code, réutilisabilité, bonnes pratiques, etc.).


## Getting Started

### Installation

Install the dependencies:

```bash
npm install
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```

## Deployment

### Docker Deployment

To build and run using Docker:

```bash
docker build -t my-app .

# Run the container
docker run -p 3000:3000 my-app
```

The containerized application can be deployed to any platform that supports Docker, including:

- AWS ECS
- Google Cloud Run
- Azure Container Apps
- Digital Ocean App Platform
- Fly.io
- Railway

### DIY Deployment

If you're familiar with deploying Node applications, the built-in app server is production-ready.

Make sure to deploy the output of `npm run build`

```
├── package.json
├── package-lock.json (or pnpm-lock.yaml, or bun.lockb)
├── build/
│   ├── client/    # Static assets
│   └── server/    # Server-side code
```



---

