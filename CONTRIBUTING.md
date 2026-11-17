# Contribuer à VIEWZ Type

Merci de l'intérêt que tu portes au projet. VIEWZ Type est une première version : chaque retour, même court, aide à la faire avancer.

*English: feedback, bug reports and pull requests are welcome, in French or in English.*

## Tu n'es pas développeur

Aucun compte GitHub n'est nécessaire. Tu peux :

- écrire à contact@viewz-studio.com ;
- envoyer un message sur Instagram à @viewz.lab.

Dis simplement ce que tu as essayé, ce que tu attendais et ce qui s'est passé. Une capture d'écran aide beaucoup.

## Signaler un défaut

Ouvre une « issue » avec le modèle **Signaler un défaut**. Les informations les plus utiles :

- l'onglet concerné (Rechercher, Reproduire ou Créer) ;
- les étapes pour reproduire le problème ;
- ce que tu attendais et ce que tu as obtenu ;
- ton appareil et ton navigateur ;
- si possible, l'image utilisée et une capture d'écran.

Avant d'ouvrir une issue, regarde si le défaut n'a pas déjà été signalé.

## Proposer une idée

Ouvre une issue avec le modèle **Proposer une amélioration**. Décris d'abord le besoin (ce que tu cherches à faire), puis la solution que tu imagines.

## Proposer une modification du code

1. Crée une copie du dépôt (« fork ») et une branche pour ta modification.
2. Lance l'application en local :

   ```
   python3 -m http.server 8000
   ```

   puis ouvre `http://localhost:8000`.
3. Fais une modification ciblée : une « pull request » par sujet.
4. Vérifie les trois onglets dans le navigateur, sans erreur dans la console.
5. Ouvre la pull request en expliquant ce qui change et pourquoi.

### Principes du projet

- **Tout dans le navigateur.** Pas de serveur, pas d'étape de compilation, pas d'installation pour l'utilisateur.
- **Le calcul avant l'IA.** Le détourage, la recherche, la reconstruction et l'export fonctionnent sans clé d'API. L'IA reste une option, jamais une condition.
- **Aucune clé dans le code.** Ne publie jamais de clé d'API, ni dans le code ni dans une issue.
- **Des polices libres uniquement.** Toute police ajoutée dans `lib/` doit être sous licence SIL Open Font License 1.1 et créditée dans `CREDITS-POLICES.md`.
- **Une interface en français clair**, compréhensible par quelqu'un qui n'est pas technicien.

## Licence des contributions

En proposant une modification, tu acceptes qu'elle soit publiée sous la licence MIT du projet (voir `LICENSE`). Les polices restent sous licence OFL 1.1.

## Contact

Ivan Loewinski, VIEWZ Studio (Toulon, France) : contact@viewz-studio.com, Instagram @viewz.lab.
