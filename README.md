<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marketing & Revenue Reports</title>

  <style>
    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", Arial, sans-serif;
      background-color: #f7f7f7;
      color: #111;
    }

    .container {
      max-width: 900px;
      margin: 80px auto;
      padding: 0 24px;
    }

    h1 {
      font-size: 42px;
      font-weight: 600;
      letter-spacing: -0.5px;
      margin-bottom: 10px;
    }

    .subtitle {
      font-size: 16px;
      color: #666;
      margin-bottom: 50px;
    }

    .section-title {
      font-size: 14px;
      letter-spacing: 1px;
      text-transform: uppercase;
      color: #888;
      margin-bottom: 20px;
    }

    .brand-list {
      display: grid;
      gap: 16px;
    }

    .brand-card {
      display: block;
      padding: 22px 24px;
      background: white;
      border-radius: 10px;
      text-decoration: none;
      color: #111;
      font-size: 18px;
      font-weight: 500;
      transition: all 0.2s ease;
      border: 1px solid #eee;
    }

    .brand-card:hover {
      transform: translateY(-2px);
      border-color: #ddd;
      box-shadow: 0 6px 18px rgba(0,0,0,0.05);
    }

    .brand-name {
      margin-bottom: 4px;
    }

    .brand-desc {
      font-size: 14px;
      color: #777;
      font-weight: 400;
    }

    .footer {
      margin-top: 80px;
      font-size: 12px;
      color: #aaa;
    }
  </style>
</head>

<body>
  <div class="container">

    <h1>Marketing & Revenue Reports</h1>
    <div class="subtitle">
      Internal reporting library for Method Co properties and campaigns
    </div>

    <div class="section-title">Brands</div>

    <div class="brand-list">

      <a href="/marketing-revenue-reports/pinch/" class="brand-card">
        <div class="brand-name">The Pinch</div>
        <div class="brand-desc">Charleston hotel + F&B marketing performance</div>
      </a>

      <a href="/marketing-revenue-reports/nickel/" class="brand-card">
        <div class="brand-name">The Nickel</div>
        <div class="brand-desc">Campaign reporting + revenue insights</div>
      </a>

      <a href="/marketing-revenue-reports/roost/" class="brand-card">
        <div class="brand-name">ROOST</div>
        <div class="brand-desc">Multi-market performance + campaigns</div>
      </a>

    </div>

    <div class="footer">
      Method Co — Marketing
    </div>

  </div>
</body>
</html>
