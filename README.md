# My CV Website – Interactive Web Developer Portfolio
Personal end-of-training project – OpenClassrooms
Objective: Create an interactive showcase website to present my background, projects, skills, and personality in an original and professional way.

# Context

For this project, I designed a complete CV website using Next.js (React framework) with an integrated back-end for secure email sending.

The website showcases my profile as a junior full-stack developer through:

A modern, animated interface

An original “Tale of the Tape” section inspired by boxing

A skills carousel

A project gallery with descriptions

A functional, secure contact form

Optimized performance and accessibility

Technologies Used

Next.js (React + API routes)

TypeScript

Sass (SCSS)

Framer Motion (animations)

Keen Slider (carousel)

i18next (multi-language support)

Nodemailer (back-end email sending)

Helmet, CORS, rate-limiter-flexible (security)

Vercel + Render (deployment)


Fonctionnalités principales
- Application Next.js avec rendering optimisé
- Navigation fluide et responsive
- Mode sombre/clair avec animation
- Carrousel horizontal pour les compétences techniques
- Section "Tale of the Tape" (soft skills présentés de manière originale)

Formulaire de contact avec :
- Validation des champs
- Envoi via API route sécurisée
- Nodemailer pour transmettre le message
- Protection contre les bots / flood
- Traduction FR/EN avec i18n et switch de langue

Sécurité renforcée :
- Headers sécurisés avec Helmet
- Limitation du spam avec rate-limiter-flexible
- Protection CORS

Performances et optimisations
- Accessibilité, SEO et performances web maîtrisées
- Objectif Lighthouse

  LIGHTHOUSE MOBILE & DESKTOP <img width="305" height="101" alt="image" src="https://github.com/user-attachments/assets/4a0a5356-4061-43a9-8201-2f6a4788409f" />
  WAVE <img width="263" height="82" alt="image" src="https://github.com/user-attachments/assets/2ab7d5d7-0c4b-4aa3-af97-e82a30cee97f" />



Lancer le projet en local
```bash

git clone https://github.com/solzarr/Portfolio-developer_MERN.git
cd FRONT
npm install
npm run dev

cd BACK
npm install
node server
``` 
Ce que j’ai appris
- Développement complet avec Next.js (frontend + backend)
- Gestion du routage, du SSR et des API routes avec Next
- Intégration et sécurisation d’un formulaire de contact avec Nodemailer
- Intégration i18n pour le multilingue
- Optimisation des performances Lighthouse
- Utilisation d’animations CSS (SCSS)
- Création d’UI dynamiques avec Sass et composants React
- Sécurisation de l’API avec Helmet, CORS, et anti-spam
- Déploiement professionnel sur Vercel et Render
- Nom de domaine (OVH)
