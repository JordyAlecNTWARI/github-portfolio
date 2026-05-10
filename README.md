# Jordy Alec — Portfolio Developpeur

BTS SIO option SLAM · Developpeur Full-Stack · Passionne par TypeScript, PHP/Symfony et React

Portfolio en ligne : [jordyalecntwari.github.io/github-porfolio](https://jordyalecntwari.github.io/github-porfolio/)

---

## A propos

Etudiant en BTS SIO option SLAM, je suis passionne par le developpement logiciel, la programmation orientee objet et les bonnes pratiques d'architecture. Ce portfolio regroupe mes projets realises en stage, en formation et en personnel.

---

## Projets

### AlecOne ([github.com/JordyAlecNTWARI/AlecOne](https://github.com/JordyAlecNTWARI/AlecOne))

Plateforme full-stack de gestion de ressources educatives developpee en projet personnel 2026.

**Stack technique :**
- PHP 8.2 / Symfony 7.4 — API REST JSON
- React 18 + TypeScript — Frontend moderne
- MySQL / Doctrine ORM
- JWT (LexikJWTAuthenticationBundle)
- Vite + React Router

**Realisations :**
- API REST complete : ressources, playlists, categories, emprunts, avis et notes
- Authentification JWT securisee avec roles (ROLE_USER, ROLE_ADMIN)
- Frontend React avec routing, context authentification et pages admin
- Back office : tableau de bord avec statistiques, CRUD ressources, gestion des emprunts
- Systeme d'emprunt avec limite de 3 emprunts simultanees et echeance J+14
- 6 tests PHPUnit (unitaires + integration)
- Pipeline CI/CD GitHub Actions — SonarLint 0 issues

Voir la demo : [jordyalecntwari.github.io/github-porfolio/alecone](https://jordyalecntwari.github.io/github-porfolio/alecone/)

**Architecture du projet :**
```
AlecOne/
├── src/
│   ├── Controller/Api/    # Controllers REST (Resource, Playlist, Category, Borrow, Review)
│   ├── Entity/            # Entites Doctrine (User, Resource, Playlist, Category, Borrow, Review)
│   ├── Repository/        # Repositories avec requetes personnalisees
│   └── Command/           # Commandes Symfony (PromoteUserCommand)
├── frontend/
│   ├── src/
│   │   ├── pages/         # Pages React (Catalogue, Detail, Login, Register, Profile, Admin)
│   │   ├── context/       # AuthContext (JWT token management)
│   │   └── api/           # Client Axios configure
│   └── vite.config.ts     # Proxy vers Symfony
├── tests/
│   ├── Unit/              # Tests unitaires PHPUnit
│   └── Integration/       # Tests d'integration PHPUnit
└── .github/workflows/     # Pipeline CI/CD GitHub Actions
```

---

### KYC Module — cbkl-labs (Stage 2026)

Module KYC (Know Your Customer) developpe en Proof of Concept lors de mon stage.

**Stack technique :**
- TypeScript, Bun, Hono
- NX Monorepo (`@cbkl/kyc`, `@cbkl/common`)
- Clean Architecture (Domain / Application / Infrastructure / Adapters)

**Realisations :**
- Structuration d'un monorepo NX en packages independants
- API REST `POST /kyc/upload` avec upload de documents d'identite
- Entites metier comportementales : `KycRequest`, `OcrData`, `ScoringResult`
- Scoring de risque automatique sur les demandes KYC
- Workflow Git professionnel : branches `feature/`, commits conventionnels, PRs

Repo prive (entreprise)

---

### MediaTek86 (`/mediatek`)

Application web de gestion de mediatheque developpee dans le cadre de la formation BTS SIO.

**Stack technique :**
- PHP / Symfony (API REST backend)
- HTML, CSS, JavaScript (frontend)
- MySQL

**Fonctionnalites :**
- Catalogue de livres avec statut de disponibilite
- Ajout, emprunt et retour de livres
- Interface de demonstration avec donnees simulees

Voir la demo : [jordyalecntwari.github.io/github-porfolio/mediatek](https://jordyalecntwari.github.io/github-porfolio/mediatek/)

Voir le repo : [github.com/JordyAlecNTWARI/github-porfolio/tree/main/mediatek](https://github.com/JordyAlecNTWARI/github-porfolio/tree/main/mediatek)

---

## Competences

| Domaine | Technologies |
|---|---|
| Langages | TypeScript, JavaScript, PHP |
| Frontend | React, HTML / CSS |
| Backend | Symfony 7, Bun, Hono, API REST, JWT |
| Architecture | Clean Architecture, SOLID, POO |
| Base de donnees | MySQL, Doctrine ORM |
| Tests | PHPUnit (unitaires + integration) |
| Outils | NX Monorepo, Git, GitHub, Linux, WebStorm, SonarLint |
| CI/CD | GitHub Actions |

---

## Contact

- [jordyalecntwari@gmail.com](mailto:jordyalecntwari@gmail.com)
- [jordyalec00@gmail.com](mailto:jordyalec00@gmail.com)
- [github.com/JordyAlecNTWARI](https://github.com/JordyAlecNTWARI)
