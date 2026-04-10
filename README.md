# Raphelec41 — Site vitrine

Site web statique pour **Raphelec41**, électricien à Naveil (41).

## Tester en local

```bash
cd ~/Work/pro/raphelec41
python3 -m http.server 8080
```

Puis ouvrir http://localhost:8080

## Structure

```
index.html              Page principale (one-page)
mentions-legales.html   Mentions légales
assets/
  logo.svg              Logo (remplaçable)
  favicon.svg           Favicon
  images/               Photos de chantier (à ajouter)
```

## Héberger

### Option 1 — Cloudflare Pages (gratuit)

1. Créer un repo GitHub et pousser le code
2. Aller sur [pages.cloudflare.com](https://pages.cloudflare.com)
3. Connecter le repo → déploiement automatique
4. Ajouter le domaine `raphelec41.fr` dans les paramètres

### Option 2 — Netlify (gratuit)

1. Aller sur [app.netlify.com](https://app.netlify.com)
2. Glisser-déposer le dossier du projet
3. Configurer le domaine personnalisé

### Option 3 — OVH (si domaine déjà chez OVH)

1. Se connecter à l'espace client OVH
2. Activer l'hébergement web (~2-3€/mois)
3. Uploader les fichiers via FTP

## Formulaire de contact

Le formulaire utilise [Formspree](https://formspree.io). Pour l'activer :

1. Créer un compte sur formspree.io
2. Créer un nouveau formulaire
3. Remplacer `raphelec41` dans l'attribut `action` du formulaire par l'ID Formspree

Alternative : remplacer l'action par `mailto:raphelec41@gmail.com` pour un envoi par email direct.

## Personnalisation

- **Logo** : remplacer `assets/logo.svg` par le vrai logo
- **Photos** : ajouter les photos dans `assets/images/` et mettre à jour la section Réalisations
- **Couleurs** : modifier les variables CSS dans le `<style>` de `index.html`
- **Textes** : éditer directement le HTML
