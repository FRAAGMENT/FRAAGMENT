<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>🏛️ FRAGMENT Elite Foundation</title>

  <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg:#0b0b0d;
      --card:#0f1113;
      --muted:#9aa0a6;
      --accent:#ffb86b;
      --accent-2:#7afcff;
      --glass: rgba(255,255,255,0.03);
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: "Vazirmatn", sans-serif;
      background: linear-gradient(180deg, var(--bg) 0%, #070708 100%);
      color:#e6e6e6;
      padding:24px;
      line-height:1.7;
    }

    .container{max-width:920px;margin:0 auto}

    header{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:16px;
      margin-bottom:20px;
      flex-wrap:wrap;
    }

    .brand{
      display:flex;
      gap:12px;
      align-items:center;
    }

    .logo{
      width:56px;height:56px;
      background:linear-gradient(135deg,var(--accent),#ff7ab6);
      border-radius:12px;
      display:flex;align-items:center;justify-content:center;
      font-weight:700;font-size:20px;color:#0b0b0d;
      box-shadow:0 6px 20px rgba(0,0,0,0.6);
    }

    .card{
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border:1px solid rgba(255,255,255,0.03);
      padding:22px;border-radius:14px;
      box-shadow:0 6px 30px rgba(10,10,10,0.6);
    }

    .section-title{
      display:flex;align-items:center;gap:10px;margin-bottom:12px;
    }

    .section-title h2{margin:0;font-size:17px}

    .section-title .tag{
      background:var(--glass);
      padding:6px 10px;border-radius:8px;
      color:var(--muted);font-size:13px;
    }

    .content p{margin:8px 0;color:var(--muted)}
    .content ul li, ol li{margin:6px 0}

    .reward{
      background: linear-gradient(90deg, rgba(122,252,255,0.06), rgba(255,184,107,0.04));
      border:1px solid rgba(122,252,255,0.06);
      padding:14px;border-radius:10px;
      color:#eafcff;display:flex;gap:12px;flex-wrap:wrap;
      justify-content:space-between;
    }

    .btn{
      display:inline-block;
      padding:12px 18px;
      border-radius:10px;
      text-decoration:none;
      font-weight:600;
      background:linear-gradient(90deg,#10b981,#06b6d4);
      color:#071014;
      box-shadow:0 8px 30px rgba(2,6,23,0.6);
    }

    .btn.secondary{
      background:transparent;
      border:1px solid rgba(255,255,255,0.06);
      color:var(--muted);
    }

    footer{
      margin-top:22px;color:var(--muted);
      font-size:13px;text-align:center;
    }
  </style>
</head>

<body>
  <div class="container">

    <header>
      <div class="brand">
        <div class="logo">FE</div>
        <div>
          <h1>🏛️ FRAGMENT Elite Foundation</h1>
          <p style="margin:0;color:var(--muted)">Auction Rules & Participation Guide</p>
        </div>
      </div>
    </header>

    <main class="card content">

      <!-- Intro -->
      <div class="section-title">
        <div class="tag">🔥</div>
        <h2>Auction Participation & Reward Rules</h2>
      </div>

      <p>
        To introduce more users to Fragment and its marketplace for premium usernames, numbers, and special digital assets, we are hosting a public auction that anyone can join.
      </p>

      <br>

      <!-- Reward -->
      <div class="section-title">
        <div class="tag">🎁</div>
        <h2>Participation Reward</h2>
      </div>

      <div class="reward">
        <div>
          <strong style="font-size:17px">Every participant receives 99 TON instantly</strong>
          <p style="margin:4px 0;color:var(--muted)">
            All users who join the auction — whether they win or lose — will instantly receive 99 TON in their wallet. ⚡💸
          </p>
        </div>
        <div style="min-width:140px;text-align:center">
          <strong style="font-size:20px;color:var(--accent-2)">+99 TON</strong>
          <div style="font-size:12px;color:var(--muted)">Instant reward</div>
        </div>
      </div>

      <br>

      <!-- Rules -->
      <div class="section-title">
        <div class="tag">📌</div>
        <h2>Rules for Joining</h2>
      </div>

      <ul>
        <li>Each person may participate only once.</li>
        <li>Fake accounts or cheating attempts lead to permanent blocking.</li>
        <li>Your wallet must contain enough TON to match the current auction entry price.</li>
      </ul>

      <br>

      <!-- How to Join -->
      <div class="section-title">
        <div class="tag">🔍</div>
        <h2>How to Join the Auction</h2>
      </div>

      <ol>
        <li>Visit the Fragment website.</li>
        <li>Search for the ID: <strong>relmie</strong>.</li>
        <li>Select the item and participate in the auction.</li>
      </ol>

      <br>

      <!-- Direct Auction Link -->
      <p style="font-size:16px;color:#fff;margin-top:20px">
        🔥 To join the auction instantly, click the button below:
      </p>

      <a class="btn"
         href="https://fragment.com/username/relmie"
         target="_blank">
        Enter Auction for “relmie”
      </a>

    </main>

    <footer>
      © FRAGMENT Elite Foundation — Terms and rules may update over time.
    </footer>

  </div>
</body>
</html>
