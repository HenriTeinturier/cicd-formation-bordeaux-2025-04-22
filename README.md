# Formation CI/CD - Lyon 31/03/2025

## Support de cours

- [Support de cours complet](https://docs.google.com/presentation/d/1ovxs_jptS9gzd22K882PcSbmva6_p8T2/edit#slide=id.g34650bd1af6_0_3)

## Sommaire des exercices

1. [Exercice 1.4 - YAML](documents/exercices/1.4%20Yaml/1.4-exercice-yaml.md)
2. [Exercice 2.5 - Premier Workflow](documents/exercices/2.5%20Premiere%20workflow/2.5-exercice-premier-workflow.md)
3. [Exercice 3.6 - Premier Workflow CI/CD](documents/exercices/3.6%20Premiere%20workflow%20CICD/3.6-exercice-1er-workflow-ci.md)
4. [Exercice 3.8 - Enquête policière](documents/exercices/3.8%20Enquête%20policière/3.8-exercice-enquete.md)
5. [Exercice 3.9.5 - Zoo](documents/exercices/3.9.5_zoo/3.9.5_zoo.md)
6. [Exercice 4.2.5 - Exploration spatiale](documents/exercices/4.2.5_exploration_spatiale/4.2.5_exploration_spatiale.md)
7. [Exercice 4.2.5 bonus - Matrix](documents/exercices/4.2.5.bonus_matrix/4.2.5.bonus_matrix.md)
8. [Exercice 4.5 - Pizzeria](documents/exercices/4.5%20Pizzeria/4.5-pizzeria.md)
9. [Exercice 4.8 - Mini application](documents/exercices/4.8%20Mini%20application/4.8-exercice-synthese.md)
10. [Exercice 5.3 - Container Docker PostgreSQL](documents/exercices/5.3%20Container%20Docker%20PostgreSql/5.3-exercice-container-PostgreSQL.md)
11. [Exercice 8.1 - Workflow Réutilisable](documents/exercices/8.1_Workflow_reutilisable/8.1-workflow-reutilisablr.md)
12. [Exercice 8.3 - Action Réutilisable](documents/exercices/8.3_action_reutilisation/8.3_action_reutilisable.md)

## Application de support

Pour l'exercice 4.8 (Mini application), vous pouvez utiliser cette [application TodoList](https://github.com/HenriTeinturier/todolist-github-action-starter/tree/main) comme support si vous avez besoin d'aide pour créer rapidement une application. Cette application React est déjà configurée avec :

- Tests unitaires (Vitest + React Testing Library)
- Configuration ESLint
- Structure de projet complète

Voici le lien de la correction du support pour notre session de formation:
[cicd-formation-bordeaux-2025-04-todolist](https://github.com/HenriTeinturier/cicd-formation-bordeaux-2025-04-todolist)

### Projet avancé CI/CD

Pour les chapitres avancés du cours, nous utiliserons une application complète avec différentes configurations :

#### Base de départ

[Projet1-cicd](https://github.com/HenriTeinturier/Projet1-cicd) : Application Vue.js avec :

- Frontend : Vue.js + Vitest (tests unitaires) + Cypress (tests E2E)
- Backend : Node.js + Express + MongoDB
- Déploiement sur VPS

#### Solutions finales

1. [Projet1-cicd-final](https://github.com/HenriTeinturier/cicd-formation-bordeaux-2025-04-projet-final-1) : Version avec déploiement simple sur VPS
2. [Projet2-cicd-final](https://github.com/HenriTeinturier/projet2-cicd-final) : Version avancée avec :
   - Nginx en reverse proxy
   - Configuration Docker
   - Déploiement conteneurisé

## Ressources supplémentaires

### Documentation GitHub Actions

- [Documentation officielle GitHub Actions (FR)](https://docs.github.com/fr/actions)
- [Workflow syntaxe GitHub Actions (FR)](https://docs.github.com/fr/actions/using-workflows/workflow-syntax-for-github-actions)
- [Variables d'environnement GitHub Actions (FR)](https://docs.github.com/fr/actions/using-workflows/environment-variables)

### YAML

- [Cheatsheet YAML](https://quickref.me/yaml.html)

### DevOps et CI/CD

- [Blog de Stéphane Robert](https://blog.stephane-robert.info/)
- [Créer un pipeline CI/CD avec GitHub Actions](https://digital.ai/fr/catalyst-blog/github-cicd/)
- [Guide DevOps Microsoft (FR)](https://learn.microsoft.com/fr-fr/devops/)
- [Introduction au CI/CD (FR)](https://www.redhat.com/fr/topics/devops/what-is-ci-cd)
- [Bonnes pratiques CI/CD (FR)](https://www.ovhcloud.com/fr/blog/bonnes-pratiques-ci-cd/)
