# Site Web Gîtes Provence - Template Astro

Bienvenue sur le template de base pour le site web des Gîtes en Provence. Ce projet utilise [Astro](https://astro.build) pour créer un site statique rapide, optimisé pour le SEO, et facile à maintenir.

## ✨ Objectif du Projet

L'objectif est de développer un site web attrayant et convivial pour des gîtes et chambres d'hôte en Provence. Le site mettra en valeur les hébergements, une grande piscine, et un cadre naturel exceptionnel, dans le but d'encourager les réservations et les demandes d'information.

## 🚀 Démarrage Rapide

Suivez ces étapes pour lancer le projet localement :

1.  **Installer les dépendances :**
    Ouvrez un terminal à la racine du projet et exécutez :
    ```sh
    npm install
    ```

2.  **Lancer le serveur de développement :**
    Une fois les dépendances installées, démarrez le serveur de développement Astro :
    ```sh
    npm run dev
    ```
    Ceci lancera le site en mode développement, généralement accessible à l'adresse `http://localhost:4321`. Le serveur se rechargera automatiquement lors des modifications de fichiers.

## 📁 Structure du Projet

Le projet suit la structure standard d'Astro :

```text
/
â”œâ”€â”€ public/                  # Fichiers statiques (images, favicon, etc.)
â”‚   â””â”€â”€ favicon.svg
â”‚   â””â”€â”€ images/               # Dossier pour les images du site
â”œâ”€â”€ src/
â”‚   â”œâ”€â”€ components/           # Composants Astro réutilisables (Header, Footer, Card, etc.)
â”‚   â”œâ”€â”€ layouts/              # Mises en page globales (MainLayout.astro)
â”‚   â”œâ”€â”€ pages/                # Fichiers .astro qui deviennent les routes/pages du site
â”‚   â”‚   â”œâ”€â”€ index.astro         # Page d'accueil
â”‚   â”‚   â”œâ”€â”€ hebergements.astro
â”‚   â”‚   â”œâ”€â”€ piscine-nature.astro
â”‚   â”‚   â”œâ”€â”€ reservation-contact.astro
â”‚   â”‚   â”œâ”€â”€ mentions-legales.astro
â”‚   â”‚   â””â”€â”€ politique-confidentialite.astro
â”‚   â””â”€â”€ styles/               # Styles globaux (global.css)
â”œâ”€â”€ astro.config.mjs          # Fichier de configuration Astro
â”œâ”€â”€ package.json              # Dépendances et scripts du projet
â””â”€â”€ tsconfig.json             # Configuration TypeScript (utilisée par Astro pour l'intellisense)
```

-   **`public/`**: Contient tous les actifs statiques qui seront copiés tels quels dans le build final. Placez ici vos images, polices, etc.
-   **`src/components/`**: Les composants Astro (`.astro`) sont des blocs de construction réutilisables pour votre interface utilisateur.
-   **`src/layouts/`**: Les layouts Astro (`.astro`) définissent la structure commune des pages (par exemple, en incluant le header, le footer, et les balises `<head>` globales).
-   **`src/pages/`**: Chaque fichier `.astro` ou `.md` dans ce répertoire devient une page sur votre site. Le nom du fichier détermine l'URL.
-   **`src/styles/`**: Contient les fichiers CSS globaux ou les variables de style.

## 🛠️ Scripts Disponibles

Dans le `package.json`, les scripts suivants sont disponibles :

| Commande              | Action                                                                 |
| :-------------------- | :--------------------------------------------------------------------- |
| `npm install`         | Installe les dépendances du projet.                                    |
| `npm run dev`         | Démarre le serveur de développement local avec rechargement à chaud.     |
| `npm run start`       | Alias pour `npm run dev`.                                              |
| `npm run build`       | Construit le site pour la production dans le répertoire `./dist/`.       |
| `npm run preview`     | Permet de prévisualiser localement le build de production.             |
| `npm run astro ...`   | Exécute des commandes CLI Astro (ex: `astro add`, `astro check`).      |

##🎨 Thème et Design

Le design s'inspirera de la Provence, avec une palette de couleurs chaudes (ocres, terre de Sienne), du bleu lavande et du vert olive. L'ambiance recherchée est élégante, moderne, tout en restant authentique et accueillante.

## 💡 Prochaines Étapes (Exemples)

-   Remplir le contenu de chaque page.
-   Intégrer des images professionnelles des gîtes et de l'environnement.
-   Développer les sections spécifiques (hébergements, piscine, activités).
-   Mettre en place un formulaire de contact/réservation.
-   Optimiser le SEO et les performances.

N'hésitez pas à consulter la [documentation officielle d'Astro](https://docs.astro.build) pour plus d'informations sur le développement avec Astro.
