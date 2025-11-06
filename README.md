  <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Happy birthday my love</title>
  <style>
    :root{
      --bg1: linear-gradient(135deg,#fff0f6 0%, #fff8fb 50%, #fffdfb 100%);
      --accent: #ff4d7a;
      --muted: #6b6b6b;
      --card: rgba(255,255,255,0.75);
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family: "Poppins", system-ui, -apple-system, "Segoe UI", Roboto, Arial; background:var(--bg1); color:#222; -webkit-font-smoothing:antialiased;}
    .wrap{max-width:950px;margin:24px auto;padding:20px;}
    header{text-align:center;margin-bottom:14px}
    h1{font-size:2.2rem;margin:0;color:var(--accent);text-shadow:0 8px 30px rgba(255,77,122,0.12)}
    .sub{color:var(--muted);margin-top:6px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.8), rgba(255,255,255,0.7));padding:18px;border-radius:16px;box-shadow:0 8px 40px rgba(120,40,80,0.04)}
    .image-row{display:flex;gap:16px;flex-wrap:wrap;justify-content:center}
    .photo{flex:1 1 280px;min-width:240px;max-width:320px;border-radius:14px;overflow:hidden;position:relative;border:6px solid rgba(255,255,255,0.6)}
    .photo img{width:100%;height:100%;display:block;object-fit:cover;transition:transform .9s ease, filter .9s ease;filter:saturate(1.03) contrast(.98)}
    .photo:hover img{transform:scale(1.05)}
    .caption{padding:12px;text-align:center;background:linear-gradient(180deg, rgba(255,255,255,0.6), rgba(255,255,255,0.45));}
    .quote{font-weight:700;color:#3c2833;margin:0;line-height:1.3}
    .who{display:block;margin-top:8px;color:var(--muted);font-size:.9rem}
    .typing{text-align:center;margin:18px auto;font-weight:700;color:#3b2430;min-height:36px}
    .cursor{display:inline-block;width:2px;height:1.05em;background:var(--accent);margin-left:6px;animation:blink 1s steps(2) infinite;vertical-align:middle}
    @keyframes blink{50%{opacity:0}}
    .letter{margin-top:14px;background:linear-gradient(180deg, rgba(255,255,255,0.85), rgba(255,250,250,0.85));padding:16px;border-radius:12px;color:#3c2c3c;line-height:1.5}
    .center{text-align:center;margin-top:12px}
    .btn{background:linear-gradient(90deg,#ff6b8f,#ff3a6a);color:white;border:none;padding:12px 20px;border-radius:999px;font-weight:800;cursor:pointer;box-shadow:0 10px 30px rgba(255,80,130,0.18)}
    .footer-note{margin-top:10px;color:var(--muted)}
    .hearts{position:fixed;inset:0;pointer-events:none;overflow:hidden;z-index:5}
    .heart{position:absolute;width:18px;height:18px;transform:translateY(0) scale(1);animation:floatUp linear forwards;opacity:.9}
    .heart:before,.heart:after{content:"";position:absolute;width:18px;height:18px;background:var(--accent);border-radius:10px 10px 0 0}
    .heart:after{transform:rotate(45deg);left:0}
    @keyframes floatUp{0%{transform:translateY(10vh) scale(0.8);opacity:0}10%{opacity:1}100%{transform:translateY(-140vh) scale(1.4);opacity:0}}
    canvas#confettiCanvas{position:fixed;inset:0;pointer-events:none;z-index:9999}
    @media (max-width:560px){h1{font-size:1.6rem} .photo{min-width:100%;max-width:100%}}
  </style>
</head>
<body>
  <div class="hearts" id="hearts"></div>
  <div class="wrap">
    <header>
      <h1>Happy birthday my love</h1>
      <div class="sub">A special surprise for <strong style="color:var(--accent)">Sir Jii</strong></div>
    </header>
<div class="sub">A special surprise for <strong style="color:var(--accent)">Sir Jii</strong></div>
    </header>
<div class="sub">A special surprise for <strong style="color:var(--accent)">Sir Jii</strong></div>
    </header>

    <div class="card">
      <div class="typing" id="typingArea"><span id="typeText"></span><span class="cursor"></span></div>

      <div class="image-row">
        <figure class="photo">
          <img src="data:image/jpeg;base64,/9j/
