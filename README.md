# makanaitabeta.github.io<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>音のプラットフォーム</title>
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', sans-serif;
      background-color: #f2f2f2;
      color: #333;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 24px;
      letter-spacing: 1px;
    }

    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      background-color: #ccc;
      padding: 60px 40px;
      text-align: center;
    }

    .hero h2 {
      font-size: 36px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
    }

    .section {
      padding: 40px;
      background-color: #fff;
      margin: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }

    .section h3 {
      border-bottom: 2px solid #ccc;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }

    .tracks {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .track {
      background-color: #eee;
      padding: 20px;
      border-radius: 6px;
      flex: 1 1 200px;
    }

    .track h4 {
      margin: 0 0 10px;
    }

    footer {
      background-color: #333;
      color: #aaa;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>音のプラットフォーム</h1>
    <nav>
      <a href="#hot">Hot</a>
      <a href="#trending">Trending</a>
      <a href="#next">Next Up</a>
    </nav>
  </header>

  <section class="hero">
    <h2>今の音、未来の音</h2>
    <p>音楽のトレンドを、ここからチェックしよう。</p>
  </section>

  <section class="section" id="hot">
    <h3>Hot Tracks（今バズってる曲）</h3>
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
    <h3>Now Trending（安定の人気）</h3>
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
    <h3>Next Up（これから来る）</h3>
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
    &copy; 2025 音のプラットフォーム | お問い合わせ | 利用規約
  </footer>

</body>
</html>
