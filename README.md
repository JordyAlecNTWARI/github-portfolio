# Jordy Alec — Portfolio Développeur

BTS SIO option SLAM · Développeur Full-Stack · Passionné par TypeScript et l'architecture logicielle

Portfolio en ligne : [jordyalecntwari.github.io/github-porfolio](https://jordyalecntwari.github.io/github-porfolio/)

---

## À propos

Étudiant en BTS SIO option SLAM, je suis passionné par le développement logiciel, la programmation orientée objet et les bonnes pratiques d'architecture. Ce portfolio regroupe mes projets réalisés en stage et en formation.

---

## Projets

### KYC Module — cbkl-labs-monorepo (`/projects/cbkl-labs-monorepo`)

Module KYC (Know Your Customer) développé en Proof of Concept lors de mon stage en 2026.

**Stack technique :**
- TypeScript, Bun, Hono
- NX Monorepo (`@cbkl/kyc`, `@cbkl/common`)
- Tesseract.js (OCR)
- Clean Architecture (Domain / Application / Infrastructure / Adapters)

**Réalisations :**
- Structuration d'un monorepo NX en packages indépendants
- API REST `POST /kyc/upload` avec upload de documents
- Entités métier comportementales : `KycRequest`, `OcrData`, `ScoringResult`
- Pipeline OCR pour extraction de données sur documents d'identité
- Workflow Git professionnel : branches `feature/`, commits conventionnels, PRs

**Architecture du projet :**
```
cbkl-labs-monorepo/
├── apps/
│   └── kyc/
│       └── api-rest/           # Serveur Hono — point d'entrée HTTP
├── packages/
│   ├── kyc/
│   │   └── src/
│   │       ├── domain/         # Entités métier (KycRequest, ScoringResult)
│   │       ├── application/    # Use cases (SubmitKycUseCase)
│   │       ├── infrastructure/ # Repositories, base de données
│   │       └── adapters/       # Contrôleurs HTTP
│   └── common/                 # Code partagé entre packages
└── configs/                    # Configuration TypeScript partagée
```

---

### MediaTek86 (`/mediatek`)

Application web de gestion de médiathèque développée dans le cadre de la formation BTS SIO.

**Stack technique :**
- PHP / Symfony (API REST backend)
- HTML, CSS, JavaScript (frontend)
- MySQL

**Fonctionnalités :**
- Catalogue de livres avec statut de disponibilité
- Ajout, emprunt et retour de livres
- Interface de démonstration avec données simulées

Voir la démo : [jordyalecntwari.github.io/github-porfolio/mediatek](https://jordyalecntwari.github.io/github-porfolio/mediatek/)

---

## Compétences

| Domaine | Technologies |
|---|---|
| Langages | TypeScript, JavaScript, PHP |
| Backend | Bun, Hono, Symfony, API REST |
| Architecture | Clean Architecture, SOLID, POO |
| Outils | NX Monorepo, Git, GitHub, Linux |
| Base de données | MySQL |

---

## Contact

- [jordyalecntwari@gmail.com](mailto:jordyalecntwari@gmail.com)
- [jordyalec00@gmail.com](mailto:jordyalec00@gmail.com)
- [github.com/JordyAlecNTWARI](https://github.com/JordyAlecNTWARI)
