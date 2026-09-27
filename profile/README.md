# BT CORE

## Processus de développement

La branche `main` est la branche de production. Elle doit rester stable et
déployable à tout moment.

> [!IMPORTANT]
> Aucun commit, push ou force-push direct n'est autorisé sur `main`. Toute
> modification doit passer par une branche dédiée et une Pull Request (PR),
> aussi appelée Merge Request (MR).

### Workflow

1. Mettre à jour sa branche locale `main` depuis le dépôt distant.
2. Créer une branche dédiée à partir de `main`.
3. Développer et tester la modification sur cette branche.
4. Pousser la branche et ouvrir une PR vers `main`.
5. Faire relire et valider la PR.
6. Fusionner uniquement lorsque tous les contrôles sont validés.
7. Supprimer la branche de travail après la fusion.

### Nommage des branches

- `feature/<description>` pour une nouvelle fonctionnalité ;
- `fix/<description>` pour une correction ;
- `hotfix/<description>` pour une correction urgente en production ;
- `refactor/<description>` pour une restructuration sans changement fonctionnel ;
- `docs/<description>` pour la documentation ;
- `chore/<description>` pour la maintenance technique.

Utiliser des noms courts, explicites et en minuscules, séparés par des tirets.

### Contenu attendu d'une PR

Chaque PR doit préciser :

- le contexte et l'objectif du changement ;
- les principales modifications réalisées ;
- la manière dont le changement a été testé ;
- les impacts, risques ou migrations éventuels ;
- les tickets ou sujets associés, le cas échéant.

### Conditions de validation

Une PR peut être fusionnée uniquement lorsque :

- les tests et contrôles automatiques réussissent ;
- au moins une personne autre que l'auteur l'a approuvée ;
- toutes les discussions bloquantes sont résolues ;
- la branche est à jour avec `main` ;
- la documentation a été adaptée si nécessaire.

Les correctifs urgents suivent le même processus. Une urgence peut accélérer
la revue, mais ne justifie jamais une modification directe de `main`.

### Mise en production

Les déploiements de production sont réalisés uniquement depuis `main`, après
fusion d'une PR validée. Une version publiée doit être identifiable par un tag
ou une release lorsque le projet utilise un versionnement.
