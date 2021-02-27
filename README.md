# Justify-API
### API REST justify text with Node js
- API REST avec NodeJS et MySQL, déployer Avec Heroku.
### Pour tester ce API il faut avoir Postmane installé
- Aller dans Postmane et taper l'URL `https://justify-api-najah.herokuapp.com/api/token` et changer le GET en POSTE.
- Ensuite Appuyer sur params et ajouter email comme clé et tapez `test@test.com` (c'est l'émail que j'ai ajouté manuellement à la BD pour tester) puis appuyer sur send et vous aurez comme réponse le token qui vous permettra de justifier le texte.
- Ouvrez une nouvelle fenêtre Postmane tapez l'URL `https://justify-api-najah.herokuapp.com/api/justify` et allez dans Headers et ajouter authorization comme clé et insérer le token que vous avez reçu lors de la réponse du premier request,
Après allez dans body puis Raw et insérer votre texte que vous voulez justifié et appuyer sur SEND et Voilà !.

