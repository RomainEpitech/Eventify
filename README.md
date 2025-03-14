# Documentation Technique d'Eventify

## Présentation du Projet

Eventify est une application web permettant aux utilisateurs de découvrir, créer et rejoindre des événements près de chez eux. L'application combine les données d'une base de données personnalisée avec des informations provenant d'APIs externes comme OpenAgenda pour offrir un service complet de référencement d'événements.

## Choix Technologiques

### Frontend

**Angular** a été choisi comme framework frontend pour les raisons suivantes :
- Architecture robuste basée sur les composants
- Typage fort grâce à TypeScript
- Écosystème mature avec des outils de développement avancés
- Facilité de maintenance pour les applications d'entreprise

**Tailwind CSS** a été adopté comme framework CSS pour :
- Son approche utility-first permettant un développement rapide
- Sa flexibilité et sa personnalisation facile
- Son optimisation pour la production (purge CSS)
- Sa compatibilité avec les applications SPA

### Backend

**Laravel** a été sélectionné comme framework backend pour :
- Sa syntaxe élégante et intuitive
- Son système d'ORM Eloquent facilement configurable
- Sa sécurité intégrée contre les vulnérabilités courantes
- Sa documentation exhaustive et sa communauté active

### Authentification

Le système d'authentification utilise **OAuth2** via les services tiers (Google) pour :
- Simplifier le processus d'inscription
- Améliorer la sécurité des comptes utilisateurs
- Réduire les frictions lors de l'onboarding

### APIs Externes

L'application s'intègre avec plusieurs APIs externes :
- **OpenAgenda** : pour enrichir le catalogue d'événements
- **WeatherAPI** : pour fournir des informations météorologiques liées aux événements
- **OpenStreetMap** : pour la géolocalisation et l'affichage cartographique

## Direction du Projet

Eventify a été conçu selon une approche centrée sur l'utilisateur avec plusieurs objectifs clés :

1. **Simplicité d'utilisation** : Une interface intuitive permettant de trouver ou créer des événements en quelques clics

2. **Aspect social** : Fonctionnalités de groupes et de messagerie pour faciliter les interactions entre participants

3. **Personnalisation** : Recommandations basées sur la localisation et les préférences des utilisateurs

4. **Multi-plateformes** : Conception responsive adaptée aux appareils mobiles et desktop

5. **Évolutivité** : Architecture modulaire permettant d'ajouter facilement de nouvelles fonctionnalités

L'architecture technique a été pensée pour permettre une maintenance aisée et des évolutions futures, notamment :
- L'ajout de fonctionnalités de recommandation personnalisées
- L'intégration avec d'autres sources d'événements
- Le développement potentiel d'applications mobiles natives

Cette approche technique équilibrée offre à la fois performance, scalabilité et facilité de développement, tout en permettant une expérience utilisateur fluide et engageante.