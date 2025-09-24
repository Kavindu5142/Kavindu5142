<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Kavindu Dinethma — Profile</title>

  <!-- Google font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --bg: #0b1220;
      --card: #0f1724;
      --muted: #94a3b8;
      --accent: #ffd166;
      --primary: #60a5fa;
      --glass: rgba(255,255,255,0.04);
      --radius: 12px;
    }
    *{box-sizing:border-box;font-family:Inter,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial;}
    body{
      margin:0;
      background:linear-gradient(180deg,#071021 0%, #071122 100%);
      color:#e6eef8;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      padding:36px;
    }

    .container{
      max-width:980px;
      margin:0 auto;
    }

    .header{
      display:flex;
      gap:20px;
      align-items:center;
      padding:28px;
      background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:var(--radius);
      box-shadow: 0 6px 20px rgba(2,6,23,0.6);
    }

    .avatar{
      width:110px;
      height:110px;
      border-radius:20px;
      background:linear-gradient(135deg,#60a5fa,#7c3aed);
      display:flex;
      align-items:center;
      justify-content:center;
      font-weight:700;
      font-size:36px;
      color:#fff;
      box-shadow: 0 8px 30px rgba(12,18,32,0.6);
      flex:0 0 110px;
    }

    .title{
      flex:1;
    }
    .title h1{margin:0;font-size:26px;letter-spacing:0.2px}
    .title p{margin:8px 0 0;color:var(--muted);font-size:14px}

    .badges{margin-top:12px;display:flex;gap:8px;flex-wrap:wrap}
    .badge{
      background:var(--glass);
      padding:6px 10px;border-radius:999px;
      font-size:13px;color:var(--muted);
    }

    .grid{
      display:grid;
      grid-template-columns: 1fr 360px;
      gap:20px;
      margin-top:20px;
    }

    /* left column */
    .card{
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:12px;
      padding:18px;
      box-shadow: 0 6px 18px rgba(2,6,23,0.5);
    }

    .about p{color:var(--muted);margin:0 0 10px;font-size:14px}
    .list{display:flex;flex-direction:column;gap:8px;margin-top:8px}
    .list .item{display:flex;gap:10px;align-items:center;color:var(--muted);font-size:14px}
    .list .item strong{color:#fff;font-weight:600}

    /* stats */
    .stats{display:flex;gap:12px;margin-top:14px;flex-wrap:wrap}
    .stat{
      background:rgba(255,255,255,0.02);
      padding:12px;border-radius:10px;flex:1;min-width:140px;
      text-align:center;
    }
    .stat h3{margin:0;font-size:20px}
    .stat p{margin:6px 0 0;color:var(--muted);font-size:13px}

    /* language bars */
    .langs{margin-top:12px}
    .lang{
      margin-bottom:10px;
    }
    .lang .label{display:flex;justify-content:space-between;font-size:13px;color:var(--muted)}
    .bar{
      height:10px;border-radius:8px;background:rgba(255,255,255,0.04);margin-top:6px;overflow:hidden;
    }
    .bar > span{display:block;height:100%;border-radius:8px;background:linear-gradient(90deg,var(--accent),#ff8a65);}

    /* right column */
    .right .card{padding:14px}
    .center-img{display:flex;align-items:center;justify-content:center;margin-top:6px}
    .center-img img{max-width:100%;border-radius:8px;box-shadow:0 6px 16px rgba(0,0,0,0.6)}

    .contact{display:flex;gap:8px;flex-wrap:wrap;justify-content:center;margin-top:12px}
    .contact a img{height:36px;display:block;border-radius:8px;border:1px solid rgba(255,255,255,0.03);background:rgba(255,255,255,0.02);}

    footer{margin-top:22px;color:var(--muted);font-size:13px;text-align:center}
    /* responsive */
    @media (max-width:920px){
      .grid{grid-template-columns:1fr; }
      .right{order:2}
    }
  </style>
</head>
<body>
  <div class="container">
    <header class="header">
      <div class="avatar">KD</div>

  </div>
</body>
</html>
