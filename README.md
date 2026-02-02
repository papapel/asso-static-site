# asso-static-site

Template de site web statique pour associations et clubs, avec **CI/CD automatisée** :
- génération du site statique
- mise à jour automatique des contenus (articles, photos)
- déploiement sur **GitHub Pages**
- build nocturne (cron GitHub Actions)

## Objectif

Permettre à une association de disposer d’un site web moderne **sans backend**,
hébergé gratuitement, facile à maintenir et personnalisable, avec possibilité
d’utiliser un nom de domaine personnalisé (ex: www.monasso.fr).

## Fonctionnalités

- Site 100% statique (hébergement gratuit)
- Déploiement automatique sur GitHub Pages
- Build planifié tous les jours à minuit
- Gestion simple des pages et articles (Markdown)
- Compatible domaine personnalisé
- Template facilement duplicable (Use this template)

## Technologies

- Générateur de site statique : *(à préciser : Hugo / Jekyll / Eleventy / autre)*
- GitHub Actions (CI/CD)
- GitHub Pages

## Structure du projet

```text
.
├── content/        # Pages et articles (Markdown)
├── static/         # Images, fichiers statiques
├── layouts/        # Templates HTML
├── .github/
│   └── workflows/  # CI/CD GitHub Actions
└── README.md
