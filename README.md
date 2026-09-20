Oto prosty szablon po polsku. Skopiuj go do pliku index.html. Zaczyna się od podstawowej struktury HTML i prostego stylu. Możesz potem podmienić teksty na własne.
```html name=index.html
<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wspólnie tworzymy przyszłość</title>
  <style>
    :root {
      --primary: #2563eb;
      --dark: #172033;
      --light: #f5f7fb;
      --text: #334155;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: var(--text);
      background: var(--light);
    }

    header {
      padding: 80px 20px;
      text-align: center;
      color: white;
      background: linear-gradient(135deg, #2563eb, #7c3aed);
    }

    header h1 {
      margin-bottom: 16px;
      font-size: 2.8rem;
    }

    header p {
      font-size: 1.2rem;
    }

    main {
      width: min(100% - 40px, 1000px);
      margin: 40px auto;
    }

    section {
      margin-bottom: 32px;
      padding: 32px;
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.06);
    }

    h2 {
      margin-bottom: 16px;
      color: var(--dark);
    }

    ul {
      padding-left: 24px;
    }

    li {
      margin-bottom: 8px;
    }

    a {
      color: var(--primary);
      font-weight: bold;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    footer {
      padding: 24px;
      text-align: center;
      color: #64748b;
    }
  </style>
</head>
<body>
  <header>
    <h1>Nazwa Twojego projektu</h1>
    <p>Wspólnie tworzymy przyszłość.</p>
  </header>

  <main>
    <section id="o-projekcie">
      <h2>O projekcie</h2>
      <p>
        To miejsce poświęcone współpracy, wymianie pomysłów i tworzeniu
        rozwiązań, które mogą pozytywnie wpłynąć na przyszłość.
      </p>
      <p>
        Projekt łączy ludzi, wiedzę i technologie, aby wspólnie realizować
        wartościowe inicjatywy.
      </p>
    </section>

    <section id="funkcje">
      <h2>Funkcje</h2>
      <ul>
        <li>Prezentacja najważniejszych informacji o projekcie</li>
        <li>Dzielenie się aktualnościami i postępami prac</li>
        <li>Współpraca nad nowymi pomysłami</li>
        <li>Łatwy kontakt z zespołem</li>
      </ul>
    </section>

    <section id="aktualnosci">
      <h2>Ostatnie zmiany</h2>
      <p>
        Rozpoczęliśmy prace nad stroną główną projektu. Wkrótce pojawią się
        kolejne informacje, aktualności oraz szczegóły dotyczące rozwoju.
      </p>
    </section>

    <section id="kontakt">
      <h2>Kontakt</h2>
      <p>
        Masz pytania lub pomysł na współpracę?
        Napisz do nas:
        <a href="mailto:kontakt@example.com">kontakt@example.com</a>
      </p>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Nazwa Twojego projektu. Wszelkie prawa zastrzeżone.</p>
  </footer>
</body>
</html>
```
