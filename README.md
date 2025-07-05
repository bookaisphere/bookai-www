# bookai-www
Strona internetowa aplikacji BookAi
```html
<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BookAI – Twoje streszczenia i quizy</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>📘 BookAI</h1>
    <p>Twórz streszczenia książek i pytania quizowe automatycznie!</p>
  </header>

  <section class="features">
    <h2>Dlaczego BookAI?</h2>
    <ul>
      <li>📄 Szybkie streszczenia całych książek PDF</li>
      <li>🤖 Generowanie pytań otwartych i testowych</li>
      <li>🌍 Obsługa wielu języków (PL, EN, DE, ES, FR)</li>
      <li>📱 Wersja mobilna – instaluj na Androidzie</li>
    </ul>
  </section>

  <section class="download">
    <h2>📥 Pobierz aplikację</h2>
    <p>Już wkrótce w Google Play. Na razie możesz pobrać plik APK:</p>
    <a href="#" class="btn">Pobierz APK</a>
  </section>

  <section class="screenshots">
    <h2>📸 Zrzuty ekranu</h2>
    <img src="screenshot1.png" alt="Zrzut ekranu aplikacji" />
    <img src="screenshot2.png" alt="Zrzut ekranu quizu" />
  </section>

  <footer>
    <p>Kontakt: <a href="mailto:bookai.aplikacja@gmail.com">bookai.aplikacja@gmail.com</a></p>
    <a href="privacy-policy.html">Polityka prywatności</a>
  </footer>
</body>
</html>
```

🎨 **style.css** (prosty wygląd strony):
```css
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background: #f8f9fa;
  color: #333;
}
header {
  background: #1e3a8a;
  color: white;
  padding: 2rem;
  text-align: center;
}
.features, .download, .screenshots {
  padding: 2rem;
}
.features ul {
  list-style: none;
  padding: 0;
}
.features li {
  margin-bottom: 0.5rem;
  padding-left: 1rem;
  position: relative;
}
.features li::before {
  content: "✔️";
  position: absolute;
  left: 0;
}
.btn {
  display: inline-block;
  padding: 0.7rem 1.5rem;
  background: #1e3a8a;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  margin-top: 1rem;
}
footer {
  background: #e2e8f0;
  padding: 1rem;
  text-align: center;
  font-size: 0.9rem;
  margin-top: 2rem;
}
```

📜 **privacy-policy.html** (wersja uproszczona, gotowa do podlinkowania):
```html
<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <title>Polityka prywatności – BookAI</title>
</head>
<body>
  <h1>Polityka prywatności – BookAI</h1>
  <p>BookAI nie przechowuje żadnych danych osobowych użytkownika.</p>
  <p>Korzystamy wyłącznie z plików PDF przesyłanych lokalnie oraz kluczy API wprowadzonych ręcznie.</p>
  <p>W razie pytań, skontaktuj się: <a href="mailto:bookai.aplikacja@gmail.com">bookai.aplikacja@gmail.com</a></p>
</body>
</html>
```
