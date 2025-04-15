<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Hot Music Picks</title>
  <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Outfit', sans-serif;
      background: #0f0f0f;
      color: #ffffff;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(to right, #ff512f, #dd2476);
      padding: 30px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
      font-weight: 800;
    }

    nav {
      background: #1a1a1a;
      padding: 15px 20px;
      text-align: center;
    }

    nav a {
      color: #ffffff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ff6f91;
    }

    .section {
      padding: 50px 20px;
      max-width: 800px;
      margin: 0 auto;
      border-bottom: 1px solid #333;
    }

    .section h3 {
      font-size: 1.8em;
      margin-bottom: 10px;
      color: #ff6f91;
    }

    .section a {
      font-size: 14px;
      color: #ccc;
      text-decoration: underline;
    }

    .track {
      background: #1e1e1e;
      margin: 15px 0;
      padding: 20px;
      border-radius: 10px;
      transition: background 0.3s;
    }

    .track:hover {
      background: #2a2a2a;
    }

    .track h4 {
      margin: 0;
      font-size: 1.2em;
      color: #ffffff;
    }

    .track p {
      margin: 5px 0 0;
      color: #aaa;
    }

    footer {
      background: #1a1a1a;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #777;
    }
  </style>
</head>
<body>

<header>
  <h1>今バズってる音楽まとめ</h1>
</header>

<nav>
  <a href="#hot">Hot Tracks</a>
  <a href="#trending">Now Trending</a>
  <a href="#next">Next Up</a>
</nav>

<section class="section" id="hot">
  <h3>Hot Tracks（今バズってる曲）
    <a href="https://spotifycharts.com/regional/jp/daily/latest" target="_blank">Spotifyチャートを見る</a>
  </h3>
  <div class="tracks">
    <div class="track">
      <h4>アーティストA - 曲名1</h4>
      <p>Spotify急上昇中</p>
    </div>
    <div class="track">
      <h4>アーティストB - 曲名2</h4>
      <p>TikTokでバズり中</p>
    </div>
  </div>
</section>

<section class="section" id="trending">
  <h3>Now Trending（安定の人気）
    <a href="https://www.billboard-japan.com/charts/detail?a=hot100" target="_blank">Billboard Japanをチェック</a>
  </h3>
  <div class="tracks">
    <div class="track">
      <h4>アーティストC - 曲名3</h4>
      <p>チャート上位をキープ</p>
    </div>
    <div class="track">
      <h4>アーティストD - 曲名4</h4>
      <p>定番プレイリスト入り</p>
    </div>
  </div>
</section>

<section class="section" id="next">
  <h3>Next Up（これから来る）
    <a href="https://soundcloud.com/discover" target="_blank">SoundCloud新着を探索</a>
  </h3>
  <div class="tracks">
    <div class="track">
      <h4>アーティストE - 曲名5</h4>
      <p>インディーズシーンで話題</p>
    </div>
    <div class="track">
      <h4>アーティストF - 曲名6</h4>
      <p>音楽系YouTuberが注目</p>
    </div>
  </div>
</section>

<footer>
  &copy; 2025 Music Trends. All rights reserved.
</footer>

</body>
</html>
