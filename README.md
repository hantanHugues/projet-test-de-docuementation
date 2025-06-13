# TEKBOT Docs

Documentation officielle du TEKBOT ROBOTICS CHALLENGE 2025.

## Prérequis

- Ruby (version 2.5.0 ou supérieure)
- Bundler
- Git

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/votre-username/2025-Team-IFRI-Docs.git
   cd 2025-Team-IFRI-Docs
   ```

2. Installez les dépendances :
   ```bash
   gem install bundler
   bundle install
   ```

## Développement local

Pour lancer le serveur de développement local :

```bash
bundle exec jekyll serve
```

Le site sera accessible à l'adresse : `http://localhost:4000`

## Structure du projet

```
.
├── _config.yml          # Configuration Jekyll
├── _layouts/           # Templates de mise en page
├── _includes/          # Composants réutilisables
├── docs/              # Documentation organisée par semaines
├── static/            # Fichiers statiques (images)
├── media/             # Médias et ressources
└── assets/            # CSS, JavaScript et autres assets
```

## Déploiement

Le site est automatiquement déployé sur GitHub Pages à chaque push sur la branche `main`.

## Contribution

1. Créez une branche pour votre modification
2. Faites vos changements
3. Soumettez une pull request

## Licence

Tous droits réservés - TEKBOT ROBOTICS CHALLENGE 2025
