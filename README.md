<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Formulaire de vérification</title>
</head>
<body>
  <h2>Sondage Nombres d'éléves</h2>
  <form action="https://formsubmit.co/TON_EMAIL" method="POST">
    <label for="prenom">Prénom :</label><br>
    <input type="text" id="prenom" name="Prénom" required><br><br>

    <label for="nom">Nom :</label><br>
    <input type="text" id="nom" name="Nom" required><br><br>

    <label for="adresse">Classe :</label><br>
    <input type="text" id="adresse" name="Adresse" required><br><br>

    <label for="email">Adresse email (optionnel) :</label><br>
    <input type="email" id="email" name="Email"><br><br>

    <button type="submit">Envoyer</button>
  </form>
</body>
</html>
