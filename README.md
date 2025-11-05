<!doctype html>
<html lang="ja">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>SOD — プロフィール</title>
  <meta name="description" content="SOD のSNSリンクと簡単な自己紹介ページ。Instagram / X / YouTubeのリンクをまとめています。" />
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--accent:#06b6d4;--muted:#94a3b8;--glass:rgba(255,255,255,0.03)}
    *{box-sizing:border-box}
    html,body{height:100%}
    body{margin:0;font-family:Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; background:linear-gradient(180deg,#071026 0%, #07111a 60%); color:#e6eef6; -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale}
    .container{max-width:920px;margin:48px auto;padding:28px}
    header{display:flex;gap:18px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:18px;flex:0 0 96px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:grid;place-items:center;font-weight:700;font-size:22px;color:#051226}
    h1{margin:0;font-size:24px}
    p.lead{color:var(--muted);margin:6px 0 0}
    .card{background:var(--card);padding:20px;border-radius:14px;margin-top:22px;box-shadow:0 6px 24px rgba(3,7,18,0.6);backdrop-filter:blur(6px)}
    .links{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px}
    a.link{display:flex;align-items:center;gap:12px;padding:14px;border-radius:12px;text-decoration:none;color:inherit;background:var(--glass);transition:transform .14s ease,box-shadow .14s ease}
    a.link:hover{transform:translateY(-4px);box-shadow:0 8px 30px rgba(2,8,23,0.6)}
    .icon{width:44px;height:44px;border-radius:10px;display:grid;place-items:center;font-weight:700}
    .meta{font-size:14px;color:var(--muted)}
    footer{margin-top:20px;color:var(--muted);font-size:13px}
    @media (max-width:480px){.avatar{width:72px;height:72px;border-radius:12px}} 
  </style>
</head>
<body>
  <main class="container">
    <header>
      <div class="avatar">SOD</div>
      <div>
        <h1>SOD — ソーシャル / プロフィール</h1>
        <p class="lead">音楽・映像・日常のスナップを中心に投稿しています。下のリンクから気軽にフォローしてください。</p>
      </div>
    </header>

    <section class="card" aria-labelledby="links-title">
      <h2 id="links-title">SNSリンク</h2>
      <div class="links" style="margin-top:12px">

        <a class="link" href="https://www.instagram.com/sodpioneer/" target="_blank" rel="noopener noreferrer">
          <div class="icon" style="background:linear-gradient(135deg,#f58529,#dd2a7b);color:#051226">IG</div>
          <div>
            <div style="font-weight:600">Instagram — sodpioneer</div>
            <div class="meta">写真・短い動画を中心に投稿</div>
          </div>
        </a>

        <a class="link" href="https://x.com/sodicality" target="_blank" rel="noopener noreferrer">
          <div class="icon" style="background:linear-gradient(135deg,#1d9bf0,#0ea5e9);color:#051226">X</div>
          <div>
            <div style="font-weight:600">X（旧Twitter） — sodicality</div>
            <div class="meta">活動の短報、告知、日常の呟き</div>
          </div>
        </a>

        <a class="link" href="https://www.youtube.com/@sod-sod8" target="_blank" rel="noopener noreferrer">
          <div class="icon" style="background:linear-gradient(135deg,#ff0000,#ff6b6b);color:#051226">YT</div>
          <div>
            <div style="font-weight:600">YouTube — sod-sod8</div>
            <div class="meta">映像作品・ライブ・Vlogなどを公開</div>
          </div>
        </a>

      </div>

      <div style="margin-top:18px;color:var(--muted);font-size:14px">
        <strong>簡単な自己紹介</strong>
        <p style="margin:8px 0 0">こんにちは、SOD（活動名）です。音楽制作や映像制作をしながら、日常の風景や制作の裏側をSNSでシェアしています。興味があれば各アカウントを覗いてみてください。</p>
      </div>

    </section>

    <footer>
      このページはあくまでも公にしている範囲内です。個人的なご連絡は、nayutapio*gmail.com(クローラー除去のため*を＠にしてください)にお願いします。
    </footer>
  </main>
</body>
</html>
