<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>アンモナイトってなに？</title>
  <style>
    body {
      margin: 0;
      font-family: "Rounded Mplus 1c", "Hiragino Maru Gothic ProN", Arial, sans-serif;
      background-color: #d6d3c4;
      color: #333;
    }

    /* 背景用レイヤー */
    .bg {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 120%;
      background-image: url("ammonite_bg.png");
      background-repeat: no-repeat;
      background-position: center top;
      background-size: cover;
      z-index: -1;
      transform: translateY(0);
      transition: transform 0.1s linear;
    }

    header {
      text-align: center;
      padding: 50px 20px;
    }

    header h1 {
      background: rgba(255, 255, 255, 0.85);
      display: inline-block;
      padding: 18px 32px;
      border-radius: 22px;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      background: rgba(255, 255, 255, 0.9);
      border-radius: 22px;
      padding: 28px;
      box-shadow: 0 6px 10px rgba(0,0,0,0.1);
    }

    h2 {
      color: #6b7c4a;
    }

    .highlight {
      background-color: #f3f1e7;
      border-left: 6px solid #b5b07a;
      padding: 12px;
      border-radius: 8px;
      margin: 15px 0;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      background: rgba(255,255,255,0.7);
    }
  </style>
</head>
<body>

  <!-- 背景 -->
  <div class="bg" id="bg"></div>

  <header>
    <h1> アンモナイトってなに？</h1>
  </header>

  <section>
    <h2>アンモナイトの しょうたい</h2>
    <p>
      アンモナイトは、むかしの海にすんでいた生きものです。
      ぐるぐる まいた かたい からを もっていました。
    </p>
    <div class="highlight">
      🕰️ 約4億年前〜6600万年前まで生きていました。
    </div>
  </section>

  <section>
    <h2>どんな なかま？</h2>
    <p>
      アンモナイトは、イカやタコと同じ「なんたいどうぶつ」のなかまです。
    </p>
  </section>

  <section>
    <h2>どうして 化石が たくさん あるの？</h2>
    <p>
      からが かたく、のこりやすかったため、
      たくさんの 化石が みつかっています。
    </p>
  </section>

  <footer>
    © アンモナイト学習サイト
  </footer>

  <script>
    const bg = document.getElementById("bg");

    window.addEventListener("scroll", () => {
      const scrollY = window.scrollY;
      bg.style.transform = `translateY(${scrollY * 0.3}px)`;
    });
  </script>

</body>
</html><img width="9449" height="3543" alt="ammonite_bg" src="https://github.com/user-attachments/assets/c0a8f53f-a749-40d6-9fd0-4b5b3c85b42d" />
