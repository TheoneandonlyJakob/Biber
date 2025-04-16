# Biber
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Meine erste Website</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Willkommen auf meiner Website!</h1>
    <nav>
      <a href="#">Startseite</a>
      <a href="#">Über mich</a>
      <a href="#">Kontakt</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Über mich</h2>
      <p>Hi! Ich bin Max und das ist meine erste eigene Website. Ich liebe Technik und Webdesign.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Max Mustermann</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
  color: #333;
}

header {
  background-color: #0055aa;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

main {
  padding: 20px;
}

footer {
  background-color: #eee;
  text-align: center;
  padding: 10px;
  font-size: 0.9em;
}