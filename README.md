# 🌐 ANEY Ehouman Ange Céleste — Portfolio Network Engineer

Portfolio ultra-moderne pour étudiant en Administration Système, Sécurité et Réseaux Informatiques.

---

## 📁 Structure des fichiers

```
portfolio/
├── index.html     → Le portfolio vitrine (public)
├── admin.html     → Panneau d'administration (privé)
└── README.md      → Ce guide
```

---

## 🚀 Démarrage rapide

### Option 1 — En local (le plus simple)
1. Place les 2 fichiers dans le même dossier
2. Double-clique sur `index.html` → s'ouvre dans le navigateur
3. C'est tout. Aucune installation requise.

### Option 2 — Hébergement gratuit (recommandé)

#### GitHub Pages (gratuit, permanent)
```bash
# 1. Crée un compte sur github.com
# 2. Nouveau dépôt : "ton-username.github.io"
# 3. Upload index.html et admin.html
# 4. Activer Pages : Settings > Pages > Deploy from branch main
# 5. URL : https://ton-username.github.io
```

#### Netlify (le plus simple, drag & drop)
1. Va sur netlify.com → créer un compte gratuit
2. Glisse-dépose ton dossier `portfolio/` dans l'interface
3. URL automatique en 30 secondes (ex: `aney-portfolio.netlify.app`)
4. Tu peux aussi choisir un nom personnalisé gratuitement

#### Vercel
```bash
npm install -g vercel
cd portfolio/
vercel
# Suit les instructions → URL générée automatiquement
```

---

## 🔧 Personnalisations à faire

### Dans `index.html`
Cherche et remplace ces valeurs :

| Texte à chercher | Remplacer par |
|---|---|
| `aney.ehouman@email.com` | Ton vrai email |
| `github.com/aney-ange` | Ton vrai GitHub |
| `https://linkedin.com` | Ton URL LinkedIn |

### Mot de passe Admin
Dans `admin.html`, ligne ~180 :
```javascript
const ADMIN_PW = 'admin2024';
// Remplace par ton propre mot de passe
```

---

## ➕ Ajouter un Lab

1. Ouvre `admin.html` dans ton navigateur
2. Entre le mot de passe (`admin2024` par défaut)
3. Remplis le formulaire :
   - **Titre** : ex. "Configuration VLAN & Inter-VLAN Routing"
   - **Catégorie** : Cisco / Linux / Windows / Sécurité
   - **Difficulté** : Easy / Medium / Hard
   - **Description** : Ce que couvre le lab
   - **Date & Durée**
   - **Fichier .pkt** : Upload ton fichier Packet Tracer → bouton téléchargeable auto sur le portfolio
   - **Rapport PDF** : Upload la doc du lab (optionnel)
4. Clique "Enregistrer le Lab"
5. Retourne sur `index.html` → le lab apparaît instantanément

> ⚠️ Les données sont stockées dans le `localStorage` du navigateur.
> Si tu changes d'ordinateur, utilise le bouton **Export JSON** dans l'admin pour sauvegarder,
> puis tu pourras réimporter via le code si besoin.

---

## ✨ Fonctionnalités intégrées

| Fonctionnalité | Description |
|---|---|
| 🖥️ Boot screen | Séquence de démarrage terminal au chargement |
| ⌨️ Typewriter | Ton nom s'écrit lettre par lettre |
| ⚡ Glitch effect | Effet signal instable sur "ANEY" |
| 🌐 Network canvas | Graphe réseau animé en fond (nœuds + paquets OSPF/ARP...) |
| 📊 Compteurs | Chiffres qui s'incrémentent au scroll |
| 🎮 3D Tilt | Cards qui se penchent en 3D au survol |
| 📏 Scroll bar | Barre de progression cyan en haut de page |
| 🔔 Toast | Notifications style terminal au téléchargement |
| 🌍 Bilingue | Bascule FR/EN instantanée |
| 📱 Responsive | Adapté mobile/tablette/desktop |
| 🔒 Admin protégé | Panneau admin avec mot de passe |

---

## 📈 Roadmap suggérée

- [ ] Ajouter tes vrais contacts (email, LinkedIn, GitHub)
- [ ] Uploader ton premier lab Cisco Packet Tracer
- [ ] Mettre à jour les barres de compétences au fil du temps
- [ ] Ajouter ta photo de profil (section À propos)
- [ ] Héberger sur GitHub Pages ou Netlify
- [ ] Mettre l'URL sur ton CV

---

## 💡 Conseils pour les labs

Pour chaque lab que tu réalises, documente :
1. **L'objectif** : que voulais-tu apprendre/configurer ?
2. **La topologie** : quels équipements, quelle architecture ?
3. **Les commandes clés** : les 3-5 commandes essentielles
4. **Les difficultés rencontrées** : c'est ce qui impressionne les recruteurs
5. **Le résultat** : est-ce que ça marche ? ping OK ?

---

*Portfolio créé avec Claude — ANEY Ehouman Ange Céleste, 2025*
