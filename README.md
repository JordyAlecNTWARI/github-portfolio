# Jordy Alec — Portfolio Développeur

Développeur full-stack junior — TypeScript, Symfony, React. Diplômé BTS SIO, je poursuis en Bachelor Développement Full-Stack à l'EPSI Nantes en alternance dès septembre 2026.

Portfolio en ligne : [jordyalecntwari.github.io/github-portfolio](https://jordyalecntwari.github.io/github-portfolio/)

---

## A propos

Développeur passionné par le développement logiciel, l'architecture applicative et les expériences web immersives. Ce portfolio regroupe mes projets réalisés en stage, en formation et en personnel.

---

## Projets

### AlecOne — Boutique 3D E-commerce (Projet personnel 2026)

Boutique e-commerce full-stack avec experiences 3D intéractives. Chaque produit est visualisable en trois dimensions avant l'achat.

**Stack technique :**
- PHP 8.2 / Symfony 7 — API REST JSON securisee par JWT
- React 18 + TypeScript — Frontend SPA
- Three.js + React Three Fiber + Drei — Experiences 3D intéractives
- MySQL / Doctrine ORM
- Stripe — Paiement par carte bancaire (Payment Intent)
- Vite 5 + React Router

**Réalisations :**
- Boutique avec mini viewer 3D par produit (modèle selon catégorie)
- Page détail produit avec viewer 3D intéractif a 360 degrés
- Système de panier avec compteur temps réel dans la navbar
- Checkout avec récapitulatif et paiement Stripe Eléments
- Authentification JWT sécurisée avec intercepteur Axios automatique
- Historique des commandes
- Catalogue de ressources éducatives (videos, articles)
- Page 404 personnalisée avec eléments 3D
- Pipeline CI/CD GitHub Actions — SonarLint 0 issues bloquantes

Voir la démo : [jordyalecntwari.github.io/github-portfolio/alecone](https://jordyalecntwari.github.io/github-portfolio/alecone/)

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

Module KYC (Know Your Customer) développé lors de mon stage chez CUBIKL S.A.S à Paris.

**Stack technique :**
- TypeScript, Bun, Hono
- NX Monorepo (`@cbkl/kyc`, `@cbkl/common`)
- Clean Architecture (Domain / Application / Infrastructure / Adapters)

**Réalisations :**
- Structuration d'un monorepo NX en packages indépendants
- API REST avec pipeline OCR pour vérification de documents d'identité
- Entités métier : `KycRequest`, `OcrData`, `ScoringResult`
- Moteur de scoring automatique sur les demandes KYC
- Workflow Git professionnel : branches `feature/`, commits conventionnels, PRs avec review

Repo privé (code confidentiel entreprise)

---

### MediaTek86 (Projet scolaire BTS SIO)

Application web de gestion de médiathèque developpee dans le cadre de la formation BTS SIO.

**Stack technique :**
- PHP / Symfony (API REST backend)
- HTML, CSS, JavaScript (frontend)
- MySQL

**Fonctionnalités :**
- Catalogue de livres avec statut de disponibilité
- Ajout, emprunt et retour de livres
- Interface de dmonstration avec données simulées

Voir la démo : [jordyalecntwari.github.io/github-portfolio/mediatek](https://jordyalecntwari.github.io/github-portfolio/mediatek/)

Voir le repo : [github.com/JordyAlecNTWARI/Mediatek86](https://github.com/JordyAlecNTWARI/Mediatek86)

---

## Compétences

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
