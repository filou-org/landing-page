# Filou - Landing Page

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🌟 **Filou** - La plateforme collaborative pour les sorties des enfants

![filou-logo](public/filou-logo.png)

## 🎯 À propos de Filou

Filou est un projet open source porté par les parents, pour mieux repérer, partager et organiser les événements culturels et ludiques destinés aux enfants et aux familles.

### ✨ Fonctionnalités principales

- **Contribution citoyenne** : Chaque parent peut partager et enrichir la base d'événements
- **Accès aux événements** : Découvrez facilement tous les événements culturels et ludiques près de chez vous
- **Open source** : Un projet transparent et collaboratif, développé par et pour la communauté des parents

## 🚀 Structure du projet

```text
/
├── public/
│   ├── favicon.ico
│   └── filou-logo.png
├── src/
│   ├── assets/
│   ├── layouts/
│   │   └── Landing.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── deploy-ftp.sh
└── package.json
```

## 🛠️ Technologies utilisées

- **Astro** - Framework web moderne pour des sites statiques performants
- **Tailwind CSS** - Framework CSS utilitaire pour un design moderne et responsive
- **TypeScript** - Typage statique pour un développement plus robuste

## 🧞 Commandes

Toutes les commandes sont exécutées depuis la racine du projet :

| Commande                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installe les dépendances                         |
| `npm run dev`             | Démarre le serveur de développement sur `localhost:4321` |
| `npm run build`           | Construit le site de production dans `./dist/`   |
| `npm run preview`         | Prévisualise le build localement avant déploiement |
| `npm run astro ...`       | Exécute les commandes CLI Astro comme `astro add`, `astro check` |
| `npm run astro -- --help` | Affiche l'aide pour l'utilisation du CLI Astro   |

## 🚀 Déploiement

Le projet utilise un script de déploiement FTP personnalisé :

```bash
# Construire le projet
npm run build

# Déployer via FTP
./deploy-ftp.sh
```

## 🤝 Contribuer

Filou est un projet open source et nous accueillons toutes les contributions !

### Comment contribuer

1. **Fork** le projet
2. Créez une **branche** pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3. **Commit** vos changements (`git commit -m 'Add some AmazingFeature'`)
4. **Push** vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une **Pull Request**

### Contact

- **Email** : contact@filou.org
- **GitHub** : [filou-org](https://github.com/filou-org)

## 📄 Licence

Ce projet est sous licence libre. Voir le fichier `LICENSE` pour plus de détails.

## 🙏 Remerciements

Fait avec ♡ par des parents, pour des parents.

---

**Filou** - La plateforme collaborative pour les sorties des enfants
