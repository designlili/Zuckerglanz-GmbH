<!DOCTYPE html>
<html lang="de">

<head>
  <meta charset="UTF-8">

  <meta
    name="viewport"
    content="width=device-width, initial-scale=1.0">

  <title>Zuckerglanz GmbH – Power BI Dashboard</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 30px;
      font-family: Arial, Helvetica, sans-serif;
      background:
        linear-gradient(
          135deg,
          #fff4fa 0%,
          #fbe7f5 50%,
          #eef9ff 100%
        );
      color: #3f2940;
    }

    .container {
      width: 100%;
      max-width: 1450px;
      margin: 0 auto;
      text-align: center;
    }

    h1 {
      margin: 0 0 10px;
      font-size: 42px;
      color: #93278f;
    }

    .subtitle {
      margin: 0 0 25px;
      font-size: 18px;
      line-height: 1.6;
    }

    .dashboard-box {
      width: 100%;
      padding: 12px;
      background: #ffffff;
      border: 2px solid #f2b4de;
      border-radius: 20px;
      box-shadow: 0 10px 35px rgba(105, 44, 92, 0.18);
    }

    .dashboard-box iframe {
      display: block;
      width: 100%;
      height: 790px;
      border: 0;
      border-radius: 14px;
      background: #ffffff;
    }

    .hinweis {
      margin-top: 18px;
      font-size: 14px;
      color: #6b5969;
    }

    .github-link {
      display: inline-block;
      margin-top: 10px;
      color: #93278f;
      font-weight: bold;
      text-decoration: none;
    }

    .github-link:hover {
      text-decoration: underline;
    }

    @media (max-width: 900px) {
      body {
        padding: 12px;
      }

      h1 {
        font-size: 30px;
      }

      .subtitle {
        font-size: 16px;
      }

      .dashboard-box iframe {
        height: 650px;
      }
    }
  </style>
</head>

<body>

  <main class="container">

    <h1>🍬 Zuckerglanz GmbH</h1>

    <p class="subtitle">
      Interaktives Power-BI-Praxisprojekt zur Analyse von
      Umsatz, Gewinn, Kunden, Produkten, Qualität und Regionen.
    </p>

    <div class="dashboard-box">

      <iframe
        title="Zuckerglanz GmbH – Power BI Dashboard"
        src="https://app.powerbi.com/reportEmbed?reportId=3a7b8a08-9fb3-4831-80c4-6dc7113e72e6&amp;autoAuth=true&amp;ctid=0dd47679-b4a9-46d9-a858-6819737af921"
        allowfullscreen="true">
      </iframe>

    </div>

    <p class="hinweis">
      Nutze die Filter, Schaltflächen, Tooltips und Drilldowns direkt im Dashboard.
    </p>

    <a
      class="github-link"
      href="https://github.com/designlili/Zuckerglanz-GmbH">
      ← Zurück zur Projektdokumentation auf GitHub
    </a>

  </main>

</body>

</html>
