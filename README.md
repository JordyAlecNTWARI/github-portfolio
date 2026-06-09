# Jordy Alec — Portfolio Developpeur

BTS SIO option SLAM · Developpeur Full-Stack · Passionne par TypeScript, PHP/Symfony, React et le developpement 3D

Portfolio en ligne : [jordyalecntwari.github.io/github-portfolio](https://jordyalecntwari.github.io/github-portfolio/)

---

## A propos

Etudiant en BTS SIO option SLAM, passionne par le developpement logiciel, l'architecture applicative et les experiences web immersives. Ce portfolio regroupe mes projets realises en stage, en formation et en personnel.

---

## Projets

### AlecOne — Boutique 3D E-commerce (Projet personnel 2026)

Boutique e-commerce full-stack avec experiences 3D interactives. Chaque produit est visualisable en trois dimensions avant l'achat.

**Stack technique :**
- PHP 8.2 / Symfony 7 — API REST JSON securisee par JWT
- React 18 + TypeScript — Frontend SPA
- Three.js + React Three Fiber + Drei — Experiences 3D interactives
- MySQL / Doctrine ORM
- Stripe — Paiement par carte bancaire (Payment Intent)
- Vite 5 + React Router

**Realisations :**
- Boutique avec mini viewer 3D par produit (modele selon categorie)
- Page detail produit avec viewer 3D interactif a 360 degres
- Systeme de panier avec compteur temps reel dans la navbar
- Checkout avec recapitulatif et paiement Stripe Elements
- Authentification JWT securisee avec intercepteur Axios automatique
- Historique des commandes
- Catalogue de ressources educatives (videos, articles)
- Page 404 personnalisee avec elements 3D
- Pipeline CI/CD GitHub Actions — SonarLint 0 issues bloquantes

Voir la demo : [jordyalecntwari.github.io/github-portfolio/alecone](https://jordyalecntwari.github.io/github-portfolio/alecone/)

**Architecture du projet :**
```
AlecOne/
├── src/
│   ├── Controller/Api/    # Controllers REST (Product, Cart, Order, Payment, Auth...)
│   ├── Entity/            # Entites Doctrine (User, Product, Category, Cart, CartItem, Order, OrderItem...)
│   ├── Repository/        # Repositories avec requetes personnalisees
│   └── DataFixtures/      # Donnees de test (8 produits, 8 ressources)
├── frontend/
│   ├── src/
│   │   ├── pages/         # Pages React (Shop, ProductDetail, Cart, Checkout, Orders, Catalogue...)
│   │   ├── context/       # AuthContext (JWT), CartContext (panier temps reel)
│   │   └── api/           # Client Axios avec intercepteur JWT
│   └── vite.config.ts     # Proxy vers Symfony + config Three.js
├── migrations/            # Migrations Doctrine
├── tests/                 # Tests PHPUnit
└── .github/workflows/     # Pipeline CI/CD GitHub Actions
```

---

### KYC Module — cbkl-labs (Stage 2026)

Module KYC (Know Your Customer) developpe lors de mon stage chez CUBIKL S.A.S a Paris.

**Stack technique :**
- TypeScript, Bun, Hono
- NX Monorepo (`@cbkl/kyc`, `@cbkl/common`)
- Clean Architecture (Domain / Application / Infrastructure / Adapters)

**Realisations :**
- Structuration d'un monorepo NX en packages independants
- API REST avec pipeline OCR pour verification de documents d'identite
- Entites metier : `KycRequest`, `OcrData`, `ScoringResult`
- Moteur de scoring automatique sur les demandes KYC
- Workflow Git professionnel : branches `feature/`, commits conventionnels, PRs avec review

Repo prive (code confidentiel entreprise)

---

### MediaTek86 (Projet scolaire BTS SIO)

Application web de gestion de mediatheque developpee dans le cadre de la formation BTS SIO.

**Stack technique :**
- PHP / Symfony (API REST backend)
- HTML, CSS, JavaScript (frontend)
- MySQL

**Fonctionnalites :**
- Catalogue de livres avec statut de disponibilite
- Ajout, emprunt et retour de livres
- Interface de demonstration avec donnees simulees

Voir la demo : [jordyalecntwari.github.io/github-portfolio/mediatek](https://jordyalecntwari.github.io/github-portfolio/mediatek/)

Voir le repo : [github.com/JordyAlecNTWARI/github-portfolio/tree/main/mediatek](https://github.com/JordyAlecNTWARI/github-portfolio/tree/main/mediatek)

---

## Competences

| Domaine | Technologies |
|---|---|
| Langages | TypeScript, JavaScript, PHP, Python, C# |
| Frontend | React 18, HTML / CSS, Vite |
| 3D | Three.js, React Three Fiber, Drei |
| Backend | Symfony 7, Bun, Hono, API REST, JWT |
| Paiement | Stripe (Payment Intent, Elements) |
| Architecture | Clean Architecture, SOLID, POO, MVC |
| Base de donnees | MySQL, Doctrine ORM |
| Tests | PHPUnit (unitaires + integration) |
| Outils | NX Monorepo, Git, GitHub, WebStorm, SonarLint |
| CI/CD | GitHub Actions |

---

## Contact

- [jordyalecntwari@gmail.com](mailto:jordyalecntwari@gmail.com)
- [jordyalec00@gmail.com](mailto:jordyalec00@gmail.com)
- [github.com/JordyAlecNTWARI](https://github.com/JordyAlecNTWARI)
