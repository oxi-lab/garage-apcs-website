# Garage A.P.C.S — Site Web

Site One-Page statique pour le Garage A.P.C.S (Auto-Moto), Chailly-en-Brie.

## 📁 Structure des fichiers

```
/
├── index.html              ← Site principal (HTML + CSS + JS tout-en-un)
├── netlify.toml            ← Config de déploiement Netlify
├── admin/
│   ├── index.html          ← Interface d'administration Decap CMS
│   └── config.yml          ← Configuration des collections CMS
└── images/
    └── galerie/            ← Dossier pour les photos (uploadées via CMS)
```

## 🚀 Déploiement sur Netlify

1. Crée un compte sur [netlify.com](https://netlify.com)
2. Connecte ton dépôt GitHub (ou glisse le dossier dans Netlify Drop)
3. Active **Netlify Identity** dans Site Settings → Identity
4. Active **Git Gateway** dans Identity → Services → Git Gateway
5. Invite le client par email depuis Identity → Invite Users
6. Le CMS sera accessible sur `https://ton-site.netlify.app/admin`

## ✏️ Ce que le client peut modifier via le CMS (`/admin`)

| Section | Champs modifiables |
|---|---|
| ⚙️ Infos du garage | Nom, texte d'accueil, téléphone, adresse, mentions légales |
| 🕐 Horaires | Tous les jours de la semaine, horaires matin/après-midi, ouvert/fermé |
| 🔧 Services | Titre, description, icône de chaque service |
| 📷 Galerie | Ajouter / supprimer / réordonner les photos |

## 🔧 Modifier les données sans CMS

Toutes les données sont dans l'objet `SITE_DATA` au bas du fichier `index.html`.
Modifie directement cet objet pour changer le contenu.

## 📞 Contact

Garage A.P.C.S — 07 61 13 72 52 — Ferme de la Florianne, 77120 Chailly-en-Brie
