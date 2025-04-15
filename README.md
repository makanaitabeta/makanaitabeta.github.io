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
      background: #f2f2f2;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(to right, #00c853, #64dd17);
      padding: 30px 20px;
      text-align: center;
      color: white;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      font-weight: 800;
    }
    nav {
      background: #e0e0e0;
      padding: 15px 20px;
      text-align: center;
    }
    nav a {
      color: #2e7d32;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #00c853;
    }
    .section {
      padding: 50px 20px;
      max-width: 800px;
      margin: 0 auto;
      border-bottom: 1px solid #ccc;
    }
    .section h3 {
      font-size: 1.8em;
      margin-bottom: 10px;
      color: #2e7d32;
    }
    .section a {
      font-size: 14px;
      color: #388e3c;
      text-decoration: underline;
    }
    .track {
      background: #ffffff;
      margin: 15px 0;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
      transition: transform 0.3s;
    }
    .track:hover {
      transform: translateY(-5px);
    }
    .track h4 {
      margin: 0;
      font-size: 1.2em;
      color: #333;
    }
    .track p {
      margin: 5px 0 0;
      color: #666;
    }
    footer {
      background: #e0e0e0;
      text-align: center;
      padding: 25px 15px;
      font-size: 14px;
      color: #555;
    }
    footer a {
      color: #00c853;
      text-decoration: none;
      font-weight: 600;
    }
    footer a:hover {
      text-decoration: underline;
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
  &copy; 2025 Music Trends.  
  <br>  
  TikTokもチェック！  
  <br>  
  <a href="https://www.tiktok.com/@yourusername" target="_blank">@yourusername</a>
</footer>
</body>
</html>

