<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Portal klasy 5a - SP23 Koszalin</title>
  <link rel="icon" type="image/png" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAABFUlEQVRIDbXBAQEAAAABIP6PzgpVAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD8DZwJAAE2qEMcAAAAAElFTkSuQmCC">
  <style>
    body {
      font-family: system-ui, Arial, sans-serif;
      background-color: #f8fafc;
      margin: 0;
      padding: 0;
      color: #333;
    }

    header {
      background-color: #ffffff;
      color: #202124;
      padding: 20px;
      text-align: center;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      font-weight: 500;
      font-family: "Google Sans", sans-serif;
    }

    header p {
      margin-top: 4px;
      font-size: 1em;
      color: #5f6368;
    }

    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      align-items: center;
      background-color: #ffffff;
      margin: 0;
      border-top: 1px solid #e0e0e0;
      border-bottom: 1px solid #e0e0e0;
    }

    nav li {
      margin: 0;
    }

    nav li:last-child {
      margin-left: auto;
    }

    nav a {
      display: block;
      padding: 15px 20px;
      color: #1a73e8;
      text-decoration: none;
      font-weight: 500;
    }

    nav a:hover {
      background-color: #f1f3f4;
    }

    main {
      padding: 20px;
      max-width: 1200px;
      margin: auto;
    }

    section {
      margin-bottom: 40px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background-color: white;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
      border-radius: 6px;
      overflow: hidden;
    }

    th, td {
      border: 1px solid #e0e0e0;
      padding: 12px;
      text-align: center;
      vertical-align: middle;
    }

    th {
      background-color: #e8f0fe;
      color: #202124;
      font-weight: bold;
    }

    tr:hover {
      background-color: #f1f3f4;
    }

    .pusta-komorka {
      background-color: #f0f0f0;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #e0e0e0;
      color: #555;
    }

    @media (max-width: 768px) {
      nav ul {
        flex-direction: column;
      }

      table, thead, tbody, th, td, tr {
        display: block;
      }

      thead {
        display: none;
      }

      tr {
        margin-bottom: 15px;
        background: white;
        border-radius: 6px;
        overflow: hidden;
      }

      td {
        padding-left: 50%;
        position: relative;
        border: none;
        border-bottom: 1px solid #ddd;
        text-align: left;
      }

      td::before {
        content: attr(data-label);
        position: absolute;
        left: 12px;
        top: 12px;
        font-weight: bold;
        color: #555;
        white-space: nowrap;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Portal Klasy 5a</h1>
    <p>Szkoła Podstawowa nr 23 im. Lotników Polskich w Koszalinie</p>
  </header>

  <nav>
    <ul>
      <li><a href="#">Strona główna</a></li>
      <li><a href="#plan-lekcji">Plan lekcji</a></li>
      <li><a href="#nauczyciele">Nauczyciele</a></li>
      <li><a href="#ogloszenia">Ogłoszenia</a></li>
      <li><a href="#kontakt">Kontakt</a></li>
      <li><a href="https://sp23.eduportal.koszalin.pl/Account/LoginSSO" target="_blank" style="color: #ffffff; background-color: #1a73e8; border-radius: 4px; padding: 10px 16px; margin: 8px; font-weight: 600;">Zaloguj się</a></li>
    </ul>
  </nav>

  <main>
    <section id="powitanie">
      <h2>Witaj na portalu klasy 5a!</h2>
      <p>Znajdziesz tu najważniejsze informacje o naszej klasie – plan lekcji, ogłoszenia, nauczycieli i wiele więcej.</p>
    </section>

    <section id="ogloszenia">
      <h2>📢 Ogłoszenia</h2>
      <ul>
        <li>📅 Zebranie z rodzicami – 14 maja (wtorek) o 17:00</li>
        <li>🎒 Wycieczka do muzeum – 23 maja (czwartek)</li>
        <li>📝 Sprawdzian z matematyki – 9 maja (czwartek)</li>
      </ul>
    </section>

    <section id="plan-lekcji">
      <h2>📅 Plan lekcji</h2>
      <table>
        <thead>
          <tr>
            <th>Godzina</th>
            <th>Poniedziałek</th>
            <th>Wtorek</th>
            <th>Środa</th>
            <th>Czwartek</th>
            <th>Piątek</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>08:00 - 08:45</td>
            <td class="pusta-komorka"></td>
            <td>Wychowanie fizyczne <br> s.gim/balon <br> Kaniewski Mikołaj/Buc Dorota</td>
            <td>Zajęcia z wychowawcą <br> 31 <br> Skok Ewa</td>
            <td class="pusta-komorka"></td>
            <td class="pusta-komorka"></td>
          </tr>
          <tr>
            <td>08:55 - 09:40</td>
            <td class="pusta-komorka"></td>
            <td>Wychowanie fizyczne <br> balon/s.gim <br> Kaniewski Mikołaj/Buc Dorota</td>
            <td>Matematyka <br> 31 <br> Skok Ewa</td>
            <td class="pusta-komorka"></td>
            <td>Język polski <br> 23 <br> Pera Agnieszka</td>
          </tr>
          <tr>
            <td>09:50 - 10:35</td>
            <td class="pusta-komorka"></td>
            <td>Język polski <br> 28 <br> Pera Agnieszka</td>
            <td>Biologia <br> 33 <br> Suchowierska Monika</td>
            <td class="pusta-komorka"></td>
            <td>Język angielski <br> 26/24 <br> Chrupała Katarzyna/Karolczuk Paulina</td>
          </tr>
          <tr>
            <td>10:45 - 11:30</td>
            <td class="pusta-komorka"></td>
            <td>Matematyka <br> 32 <br> Skok Ewa</td>
            <td>Język polski <br> 28 <br> Pera Agnieszka</td>
            <td class="pusta-komorka"></td>
            <td>Historia <br> 22 <br> Podpirko Adrian</td>
          </tr>
          <tr>
            <td>11:40 - 12:25</td>
            <td>Język polski <br> 30 <br> Pera Agnieszka</td>
            <td>Historia <br> 24 <br> Podpirko Adrian</td>
            <td>Wychowanie fizyczne <br> HJ <br> Kaniewski Mikołaj/Buc Dorota</td>
            <td>Geografia <br> 32 <br> Marcisz Elwira</td>
            <td>Matematyka <br> 31 <br> Skok Ewa</td>
          </tr>
          <tr>
            <td>12:40 - 13:25</td>
            <td>Język angielski [G1] / Informatyka [G2]  <br> 26/25 <br> Chrupała Katarzyna/Skuza Agnieszka</td>
            <td>Muzyka <br> 23 <br> Kowalska Magdalena</td>
            <td>Wychowanie fizyczne <br> HJ <br> Kaniewski Mikołaj/Buc Dorota</td>
            <td>Język angielski <br> 26/24 <br> Chrupała Katarzyna/Karolczuk Paulina</td>
            <td>Wychowanie do życia w rodzinie [WDŻ] <br> 23 <br> Janecka Aleksandra</td>
          </tr>
          <tr>
            <td>13:40 - 14:25</td>
            <td>Język angielski [G2] / Informatyka [G1]  <br> 24/25 <br> Karolczuk Paulina/Skuza Agnieszka</td>
            <td>Religia <br> 24 <br> Szablińska Małgorzata</td>
            <td>Religia <br> 24 <br> Szablińska Małgorzata</td>
            <td>Język polski <br> 27 <br> Pera Agnieszka</td>
            <td class="pusta-komorka"></td>
          </tr>
          <tr>
            <td>14:35 - 15:20</td>
            <td>Matematyka <br> 31 <br> Skok Ewa</td>
            <td class="pusta-komorka"></td>
            <td class="pusta-komorka"></td>
            <td>Plastyka <br> 32 <br> Buryło-Sikora Katarzyna</td>
            <td class="pusta-komorka"></td>
          </tr>
          <tr>
            <td>15:30 - 16:15</td>
            <td>Technika <br> 22 <br> Anna Pusz</td>
            <td class="pusta-komorka"></td>
            <td class="pusta-komorka"></td>
            <td class="pusta-komorka"></td>
            <td class="pusta-komorka"></td>
          </tr>
        </tbody>
      </table>
    </section>

    <section id="nauczyciele">
      <h2>🧑‍🏫 Nauczyciele</h2>
      <ul>
        <li><strong>Język polski:</strong> Pera Agnieszka</li>
        <li><strong>Matematyka:</strong> Skok Ewa</li>
        <li><strong>Historia:</strong> Podpirko Adrian</li>
        <li><strong>Biologia:</strong> Suchowierska Monika</li>
        <li><strong>Geografia:</strong> Marcisz Elwira</li>
        <li><strong>Wychowanie fizyczne:</strong> Kaniewski Mikołaj, Buc Dorota</li>
        <li><strong>Język angielski:</strong> Chrupała Katarzyna, Karolczuk Paulina</li>
        <li><strong>Muzyka:</strong> Kowalska Magdalena</li>
        <li><strong>Plastyka:</strong> Buryło-Sikora Katarzyna</li>
        <li><strong>Religia:</strong> Szablińska Małgorzata</li>
        <li><strong>Technika:</strong> Anna Pusz</li>
        <li><strong>Informatyka:</strong> Skuza Agnieszka</li>
        <li><strong>WDŻ:</strong> Janecka Aleksandra</li>
      </ul>
    </section>
  </main>
  <footer>
    <p>&copy; 2025 Klasa 5a – Szkoła Podstawowa nr 23 im. Lotników Polskich w Koszalinie</p>
    <p>ul. Sportowa 19, 75-503 Koszalin | tel./fax: 94 345 11 54 | e-mail: sp23koszalin@op.pl</p>
  </footer>

</body>
</html>
