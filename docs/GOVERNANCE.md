# TaskFlow — Gouvernance du projet

## 1. Principe général

Les agents BMAD assistent l'équipe dans l'analyse, la conception, le développement et la validation. Ils ne remplacent pas les décisions des responsables humains.

Aucune phase importante ne passe à l'étape suivante sans validation du responsable concerné.

## 2. Product Owner

**Agents supervisés :** Analyst, Product Manager.

**Responsabilités :**

- Valider le brainstorming et le Product Brief.
- Valider le PRD et les épiques.
- Arbitrer les priorités fonctionnelles.
- Maintenir le backlog.
- Vérifier la cohérence avec les objectifs du produit.

**Livrables à valider :** Product Brief, PRD, épiques et backlog.

## 3. Architecte

**Agents supervisés :** Architecte, UX.

**Responsabilités :**

- Définir et valider l'architecture logicielle.
- Valider les choix technologiques.
- Garantir la cohérence entre les modules.
- Vérifier les interfaces et les responsabilités des composants.

**Livrables à valider :** architecture, décisions techniques et conception UX.

## 4. Responsable qualité

**Agents supervisés :** QA, revue de code.

**Responsabilités :**

- Valider les critères d'acceptation.
- Maintenir les tests automatisés Cucumber.
- Examiner les résultats des tests.
- Surveiller les indicateurs SonarQube.
- Signaler les défauts et suivre leur correction.

**Livrables à valider :** critères d'acceptation, scénarios de test, rapports qualité et revues de code.

## 5. Responsable DevOps et sécurité

**Agent supervisé :** Développeur chargé du déploiement.

**Responsabilités :**

- Gérer la CI/CD.
- Configurer et contrôler Docker.
- Configurer et sécuriser Keycloak.
- Auditer les dépendances et les extensions installées.
- Contrôler les secrets, les permissions et les conditions de déploiement.

**Livrables à valider :** pipelines CI/CD, configuration Docker, configuration de sécurité et rapports d'audit.

## 6. Règles de validation

1. Le Product Owner valide les exigences avant la conception détaillée.
2. L'Architecte valide les choix d'architecture avant l'implémentation.
3. Le Responsable qualité vérifie les critères d'acceptation et les tests.
4. Le Responsable DevOps et sécurité valide les contrôles techniques avant le déploiement.
5. Toute modification importante doit être examinée par le responsable concerné.
6. Les agents BMAD ne déclarent jamais une validation humaine acquise sans confirmation explicite.
