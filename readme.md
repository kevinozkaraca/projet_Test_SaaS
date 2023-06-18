# Test SaaS

## Description du projet :

- Une collègue de la feature team “note de frais” a quitté l’entreprise avant d’avoir terminé l’application
- Il faut mettre en place des tests pour s’assurer que l’application fonctionne correctement

## Correction à éffectuer :

- Mettre en place la fonctionnalité "Note de frais" (voir le description dans les documents)
- Attention il y a deux types de parcours utilisateurs :
  - Un parcours pour les administrateurs RH
  - Un parcours pour les employés
- Le backe-end est déjà en place, il faut implémenter le front-end :
  - Parcours administrateur : il a été testé par Garance, il faut désormais le débugger.
  - Parcours employé : il faut entièrement le tester et le débugger.
- utiliser Chrome Debugger

/!\ Lire la documentation pour plus d'informations /!\

## Mise en place du projet :

- Installer et lancer le back-end :

  - `cd Billed-app-FR-Back`
  - `npm install`
  - `npm run run:dev` ou run:dev ?!

- Les utilisateurs par défaut :
  - ADMIN ---------
  - utilisateur : admin@test.tld
  - mot de passe : admin
  - EMPLOYEE ------
  - utilisateur : employee@test.tld
  - mot de passe : employee

Installer le front-end :

- `cd Billed-app-FR-Front`
- `npm install`

Lancer les tests :

- `npm run test`

installer jest-cli :

- `npm i -g jest-cli`
- `jest src/__tests__/your_test_file.js`

afficher la couverture de test :

- `http://127.0.0.1:8080/coverage/lcov-report/`
