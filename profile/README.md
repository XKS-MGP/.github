# MONDIAL GP

## Sommaire

* [Introduction](#introduction)

  * [Contexte général](#contexte-général)
  * [Objectifs du cahier](#objectifs-du-cahier)
  * [Méthodologie de travail](#méthodologie-de-travail)
* [Analyse et Recherches](#analyse-et-recherches)

  * [Contexte du domaine](#contexte-du-domaine)
  * [Étude des besoins ou problématique](#étude-des-besoins-ou-problématique)
  * [État de l’art ou revue de littérature](#état-de-lart-ou-revue-de-littérature)
* [Spécifications Fonctionnelles](#spécifications-fonctionnelles)
* [Spécifications Techniques](#spécifications-techniques)

  * [Architecture du système ou du projet](#architecture-du-système-ou-du-projet)
  * [Technologies utilisées](#technologies-utilisées)
  * [Contraintes techniques](#contraintes-techniques)
* [Conception](#conception)

  * [Schémas techniques](#schémas-techniques)
  * [Développement des fonctionnalités](#développement-des-fonctionnalités)
  * [Planification du projet](#planification-du-projet)
* [Implémentation](#implémentation)

  * [Détails du développement ou de la réalisation](#détails-du-développement-ou-de-la-réalisation)
  * [Problèmes rencontrés et solutions apportées](#problèmes-rencontrés-et-solutions-apportées)
* [Tests et Validation](#tests-et-validation)

  * [Plan de tests](#plan-de-tests)
  * [Résultats des tests](#résultats-des-tests)
  * [Corrections et améliorations](#corrections-et-améliorations)
* [Déploiement](#déploiement)

  * [Stratégie de déploiement](#stratégie-de-déploiement)
  * [Infrastructure](#infrastructure)
  * [Mise en production](#mise-en-production)
* [Conclusion](#conclusion)

  * [Résumé des résultats](#résumé-des-résultats)
  * [Bilan du projet](#bilan-du-projet)
  * [Perspectives d’amélioration ou d’évolution](#perspectives-damélioration-ou-dévolution)
* [Annexes](#annexes)

---

## Introduction

### Contexte général

Le projet **Mondial GP** vise à répondre à un besoin fréquent dans le contexte africain : acheminer des colis entre l'Afrique et l'Europe...

### Objectifs du cahier

Le présent cahier des charges a pour objectif de définir les spécifications fonctionnelles, techniques et économiques du projet MondialGP...

### Méthodologie de travail

Pour mener à bien le développement du projet MondialGP, une approche méthodologique agile sera adoptée...

## Analyse et Recherches

### Contexte du domaine

Le projet MondialGP s'inscrit dans un contexte où les échanges de colis entre l'Afrique et l'Europe connaissent une demande croissante...

### Étude des besoins ou problématique

Cette section met en lumière les besoins spécifiques des utilisateurs ainsi que les défis...

### État de l’art ou revue de littérature

Cette revue de littérature permet d’identifier les meilleures pratiques, les concurrents directs ou indirects...

## Spécifications Fonctionnelles

Le projet MondialGP vise à fournir une plateforme numérique de mise en relation entre demandeurs et voyageurs...

## Spécifications Techniques

### Architecture du système ou du projet

L'architecture du projet MondialGP repose sur une structure modulaire, évolutive et sécurisée...

### Technologies utilisées

#### Frontend (Client)

* Nuxt.js
* TailwindCSS
* Pinia
* API REST, WebSocket

#### Backend (API & Microservices)

* Laravel
* Node.js, NestJS
* TypeORM, MySQL/MongoDB
* Socket.IO, JWT

#### Infrastructure Cloud

* Docker, Kubernetes, AWS

### Contraintes techniques

* Performance et scalabilité
* Sécurité des données et transactions
* Suivi en temps réel
* Compatibilité multiplateforme
* Intégration avec services tiers

## Conception

### Schémas techniques

Diagrammes d’architecture, modèle de données (à insérer)

### Développement des fonctionnalités

Planification par sprint (Scrum), coordination avec les designers et testeurs...

### Planification du projet

Feuille de route, milestones, backlog produit, roadmap agile

## Implémentation

### Détails du développement ou de la réalisation

Développement backend, API sécurisées, intégration frontend

### Problèmes rencontrés et solutions apportées

Problèmes techniques, choix technologiques, solutions mises en œuvre

## Tests et Validation

### Plan de tests

Tests fonctionnels, tests utilisateurs, tests de charge

### Résultats des tests

Bugs identifiés, correctifs appliqués, taux de réussite

### Corrections et améliorations

Amélioration UX, réduction du temps de chargement, fiabilité accrue

## Déploiement

### Stratégie de déploiement

Déploiement progressif, canary releases, rollback automatique

### Infrastructure

Serveurs cloud, base de données scalable, outils de monitoring

### Mise en production

CI/CD, validation finale, migration de données

## Conclusion

### Résumé des résultats

Objectifs atteints, feedback utilisateur positif, fonctionnalités livrées

### Bilan du projet

Difficultés rencontrées, enseignements tirés, ROI estimé

### Perspectives d’amélioration ou d’évolution

Nouvelles fonctionnalités, expansion à d’autres régions, intégration IA


# TERME DE REFERENCES

## MONDIAL GP

## Introduction

### Contexte général

Le projet **Mondial GP** vise à répondre à un besoin fréquent dans le contexte africain : acheminer des colis entre l'Afrique et l'Europe. L'idée est de mettre en relation des personnes souhaitant envoyer des colis (les demandeurs) avec des voyageurs (les GP) qui peuvent transporter ces colis moyennant une rémunération.

**Problématique :** Les envois de colis entre l'Afrique et l'Europe sont souvent coûteux et compliqués, nécessitant parfois la recherche d'une personne de confiance. Les services spécialisés sont souvent trop chers.

**Solution proposée :** Une plateforme mettant en relation les demandeurs avec :

* Des voyageurs indépendants (GP)
* Des porteurs certifiés, vérifiés par l'entreprise, pour plus de sécurité

**Modèle économique :**

* Commissions sur transactions
* Abonnements Standard et Premium (accès à des services et priorités)

**Utilisateurs :**

* Demandeur
* GP (Global Passenger)
* Livreur
* Administrateur

**Expansion mondiale :** Extension prévue au-delà de l’Afrique et l’Europe, tout en garantissant sécurité et fiabilité.

### Objectifs du cahier

* Définir les spécifications fonctionnelles, techniques et économiques
* Établir un modèle économique viable
* Spécifier les rôles et interactions utilisateur
* Assurer sécurité et fiabilité via les porteurs certifiés
* Présenter les évolutions futures et les extensions géographiques
* Définir les contraintes techniques (transactions, géoloc., stockage)
* Proposer une identité visuelle et une interface intuitive

### Méthodologie de travail

#### Phase de planification et d'analyse

* Recueil des besoins utilisateurs
* Étude de marché
* Backlog produit

#### Développement itératif (Agile/Scrum)

* Sprints de 2 semaines avec planif., dev, tests et rétrospective
* Collaboration équipes : devs, designers, testeurs, PO

#### Design et prototypage

* Maquettes + prototypes interactifs
* Tests utilisateurs sur prototypes

#### Développement technique

* Focus backend et sécurité
* Technologies modernes (scalabilité + perf.)
* Intégrations (paiement, géoloc., notifications)

#### Tests et validation

* Tests automatisés
* Tests utilisateurs (tracking, transactions, notifs)

#### Déploiement et suivi post-prod

* Déploiement progressif
* Monitoring et retours utilisateurs

#### Communication continue

* Daily stand-up
* Outils collaboratifs : Jira / Trello

## Analyse et Recherches

### Contexte du domaine

* Demande croissante colis Afrique-Europe (diaspora, PME, famille)
* Services actuels coûteux, peu flexibles
* Systèmes informels = manque de sécurité, traçabilité

**Opportunité :**

* Modèle Uber/Airbnb appliqué à la logistique (crowdshipping)
* Plateforme numérique sécurisée
* Marché africain = fort potentiel (zones rurales, e-commerce)

### Étude des besoins ou problématique

#### 1. Besoins des utilisateurs

**Demandeurs :**

* Prix abordables
* Sécurité + traçabilité
* Choix du GP (date, destination, prix)
* Interface simple
* Accès aux porteurs certifiés

**GP :**

* Monétiser bagage
* Paiement sécurisé
* Interface intuitive
* Assurance + sécurité

**Livreurs :**

* Interface claire pour les retraits/livraisons
* Paiement intégré

**Admin :**

* Supervision complète
* Gestion des réclamations
* Vérification des GP

#### 2. Problématiques principales

* Coût élevé (services classiques)
* Manque de traçabilité (systèmes informels)
* Manque de flexibilité (choix GP/date/lieu)
* Étendue géographique limitée (zones rurales)
* UX et satisfaction utilisateur

### État de l’art ou revue de littérature

#### Logistique participative

* Optimisation des ressources (bagages inutilisés)
* Exemples : PiggyBee, Nimber, Grabr

#### Limites logistique classique

* Coûts élevés, délais longs, peu de flexibilité

#### Innovations logistiques

* Tracking en temps réel
* Certification des porteurs

#### Révolution numérique

* Apps mobiles, paiements sécurisés
* Communication instantanée

#### Analyse concurrents

* MondialGP : seul positionné diaspora Afrique-Europe
* Différenciation : porteurs certifiés + suivi temps réel + sécurité

## Spécifications Fonctionnelles

### Description des fonctionnalités principales

#### 1. Enregistrement et gestion des utilisateurs

* Création de compte (Demandeur, GP, Porteur certifié)
* Connexion via email ou réseaux sociaux
* Vérification des identités pour les GP certifiés
* Gestion du profil, préférences et historique

#### 2. Recherche et mise en relation

* Moteur de recherche : destination, dates, capacité, prix
* Filtrage par certification
* Affichage des GP disponibles (profil, évaluations)
* Système de chat intégré

#### 3. Réservation et transaction

* Réservation de kilos disponibles
* Paiement sécurisé via Stripe/PayPal
* Notification GP + acceptation
* Confirmation de livraison + évaluation mutuelle

#### 4. Suivi des colis

* Suivi temps réel (mise à jour position par GP)
* Notifications push aux utilisateurs

#### 5. Porteurs certifiés

* Accès dédié pour les utilisateurs premium
* Certification rigoureuse (documents, antécédents)
* Badge visible sur profil GP

#### 6. Gestion des colis par livreurs

* Interface pour suivi de collecte et dépôt
* Notifications de chaque étape

#### 7. Réclamations et litiges

* Système de signalement intégré
* Interface d’administration pour résolution
* Support client par chat/email

#### 8. Notation et commentaires

* Notation GP/demandeurs après transaction
* Système de réputation valorisé sur la plateforme

#### 9. Tableau de bord administrateur

* Suivi global des activités, transactions, litiges
* Vérification et validation des GP certifiés

#### 10. Fonctionnalités futures

* Partenariats avec Uber ou services locaux
* Intégration d’un module e-commerce

### Besoins utilisateurs (récapitulatif)

* **Demandeurs** : coût réduit, sécurité, choix, traçabilité, interface simple
* **GP** : monétisation, sécurité, assurance, simplicité
* **Porteurs certifiés** : visibilité, reconnaissance, gestion simplifiée
* **Livreurs** : gestion des missions, coordination, rémunération
* **Administrateurs** : vérification, gestion, supervision

### Cas d’utilisation (exemples)

#### Demandeur :

* Recherche GP disponible
* Réservation de kilos
* Paiement + suivi colis
* Évaluation GP

#### GP :

* Création d’annonce (trajet, kilos, prix)
* Réception de demandes
* Acceptation + suivi
* Livraison + confirmation

#### Porteur certifié :

* Processus de certification
* Visibilité prioritaire

#### Livreur :

* Prise en charge colis
* Remise au GP

#### Administrateur :

* Gestion litiges
* Validation GP

## Spécifications Techniques

### Architecture du système ou du projet

L'architecture de MondialGP suit une structure modulaire et scalable reposant sur un modèle client-serveur basé sur les microservices.

#### 1. Architecture générale

* **Frontend** : application web (Nuxt.js) + mobile (Flutter)
* **Backend** : API RESTful en NestJS (Node.js)
* **Base de données** : SQL (MySQL) + NoSQL (MongoDB)
* **Infrastructure cloud** : AWS
* **Microservices** : utilisateurs, transactions, géolocalisation, notifications

#### 2. Détails des composants

**Frontend**

* Frameworks : Nuxt.js (Vue), TailwindCSS, Pinia
* Communication : REST API + WebSocket (Socket.IO)
* Applications mobiles cross-platform

**Backend**

* Framework : Laravel (PHP) & NestJS (Node.js)
* Sécurité : JWT pour auth, bcrypt pour les mots de passe
* Microservices découplés (users, colis, paiement, suivi)

**Base de données**

* MySQL : données structurées (utilisateurs, transactions)
* MongoDB : données non structurées (chat, logs)
* ORM : Eloquent, TypeORM

**Infrastructure Cloud**

* Docker pour la conteneurisation
* Kubernetes pour l’orchestration
* CI/CD : GitHub Actions, GitLab CI/CD, Jenkins
* Monitoring : Prometheus, Grafana

**Sécurité**

* TLS pour les communications sécurisées
* Authentification avec Oauth2 + autorisation JWT
* Conforme RGPD
* Sauvegardes automatiques + redondance

**Services tiers**

* Paiement : Stripe, PayPal
* Géolocalisation : Google Maps API, OpenStreetMap
* Notifications : Firebase Cloud Messaging, SendGrid, OneSignal

### Technologies utilisées

**Frontend :**

* Nuxt.js, TailwindCSS, Pinia, Vue 3
* Pusher ou Socket.IO pour le temps réel

**Backend :**

* NestJS, TypeORM
* REST API, JWT, bcrypt
* Microservices scalables

**Base de données :**

* PostgreSQL ou MySQL (relations)
* MongoDB (logs, chat)

**Infrastructure :**

* Docker, Kubernetes
* Cloud AWS ou GCP
* CI/CD (GitHub Actions, GitLab CI/CD)

**Services externes :**

* Stripe / PayPal, Google Maps, FCM, SendGrid

### Contraintes techniques

#### 1. Performance et scalabilité

* Gestion forte charge : scaling horizontal via Kubernetes
* Temps réel : Socket.IO / WebSocket performant

#### 2. Sécurité des données

* Authentification robuste (JWT)
* RGPD + PCI-DSS pour les paiements

#### 3. Suivi temps réel

* Synchronisation position colis
* Notifications instantanées

#### 4. Compatibilité multi-plateformes

* Responsive web
* Mobiles Android / iOS

#### 5. Résilience infrastructure

* Multi-AZ cloud
* Sauvegardes régulières

#### 6. Services tiers

* Dépendance à Stripe, Google Maps : nécessité de fallback

#### 7. Maintenance & versionning

* CI/CD automatisé
* Surveillance logs + alertes

#### 8. Analytics

* Intégration Google Analytics
* Caching (Redis) pour les données fréquentes

