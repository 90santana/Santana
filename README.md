# Santana
Prova
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>I Miei Podcast</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: white;
      padding: 1em 0;
      text-align: center;
    }
    .container {
      padding: 2em;
    }
    .episode {
      background-color: white;
      margin-bottom: 1.5em;
      padding: 1em;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .episode h2 {
      margin-top: 0;
    }
    .player {
      margin-top: 1em;
    }
  </style>
</head>
<body>

<header>
  <h1>I Miei Podcast</h1>
  <p>Benvenuto nel mio spazio dedicato ai podcast!</p>
</header>

<div class="container">
  <div class="episode">
    <h2>Episodio 1: Introduzione</h2>
    <p>In questo episodio introduttivo, parlo di cosa tratterà il mio podcast.</p>
    <div class="player">
      <audio controls>
        <source src="https://www.tuosito.com/audio/episodio1.mp3" type="audio/mpeg">
        Il tuo browser non supporta l'elemento audio.
      </audio>
    </div>
  </div>

  <div class="episode">
    <h2>Episodio 2: Intervista con l'Esperto</h2>
    <p>Una conversazione approfondita con un esperto del settore.</p>
    <div class="player">
      <audio controls>
        <source src="https://www.tuosito.com/audio/episodio2.mp3" type="audio/mpeg">
        Il tuo browser non supporta l'elemento audio.
      </audio>
    </div>
  </div>

  <!-- Aggiungi altri episodi qui -->

</div>

</body>
</html>