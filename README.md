<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sondage Nombres d'élèves</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      background-image: url('B606E343-73AC-4D14-BA33-043AB0049FEE.jpeg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      font-family: Arial, sans-serif;
      color: white;
    }
    form {
      background-color: rgba(0, 0, 0, 0.6);
      padding: 20px;
      margin: 50px auto;
      width: 300px;
      border-radius: 10px;
    }
    label, input, button {
      display: block;
      width: 100%;
      margin-bottom: 15px;
    }
    input, button {
      padding: 8px;
      border: none;
      border-radius: 5px;
    }
    button {
      background-color: #3498db;
      color: white;
      cursor: pointer;
    }
    button:hover {
      background-color: #2980b9;
    }
    h2 {
      text-align: center;
      margin-top: 30px;
      text-shadow: 1px 1px 3px black;
    }
  </style>
</head>
<body>
  <h2>Sondage Nombres d'élèves</h2>
  <form action="https://formsubmit.co/dinomicka@outlook.fr" method="POST">
    <label for="prenom">Prénom :</label>
    <input type="text" id="prenom" name="Prénom" required />

    <label for="nom">Nom :</label>
    <input type="text" id="nom" name="Nom" required />

    <label for="adresse">Classe :</label>
    <input type="text" id="adresse" name="Classe" required />

    <label for="email">Adresse email (optionnel) :</label>
    <input type="email" id="email" name="Email" />

    <button type="submit">Envoyer</button>
  </form>
</body>
</html>