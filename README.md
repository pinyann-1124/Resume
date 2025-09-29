<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>我的履歷</title>
  <style>
    body {
      margin: 0;
      font-family: "Noto Sans TC", sans-serif;
      line-height: 1.6;
      color: #333;
      scroll-behavior: smooth;
    }

    /* 導覽列 */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      background: #1f3b73;
      color: #fff;
      padding: 12px 20px;
      display: flex;
      justify-content: center;
      gap: 20px;
      z-index: 1000;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: 500;
    }
    nav a:hover {
      text-decoration: underline;
    }

    /* 頁面基本區塊 */
    section {
      max-width: 900px;
      margin: 100px auto 60px auto;
      padding: 40px 20px;
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.08);
    }

    h1, h2 {
      margin-top: 0;
      color: #1f3b73;
    }
    h1 {
      font-size: 2.4rem;
    }
    h2 {
      font-size: 1.6rem;
      border-left: 4px solid #6ea8fe;
      padding-left: 8px;
    }

    .center {
      text-align: center;
    }
    .avatar {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #6ea8fe;
      margin-bottom: 16px;
    }

    ul {
      padding-left: 20px;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #666;
    }

    body {
      background: linear-gradient(135deg,#6ea8fe,#e2e6f0);
    }
  </style>
</head>
<body>

  <!-- 導覽列 -->
  <nav>
    <a href="#about">關於我</a>
    <a href="#skills">技能</a>
    <a href="#experience">經歷</a>
    <a href="#education">學歷</a>
    <a href="#contact">聯絡方式</a>
  </nav>

  <!-- 首頁區塊 -->
  <section id="about" class="center">
    <img class="avatar" src="你的照片網址.jpg" alt="頭像">
    <h1>你的姓名</h1>
    <p>申請職位 / 科系 | 個人簡介一句話</p>
  </section>

  <!-- 技能 -->
  <section id="skills">
    <h2>技能</h2>
    <ul>
      <li>HTML / CSS / JavaScript</li>
      <li>React / 前端基礎</li>
      <li>數學邏輯、圖形空間能力</li>
    </ul>
  </section>

  <!-- 經歷 -->
  <section id="experience">
    <h2>經歷</h2>
    <ul>
      <li>2024 校內網站專案 — 前端切版與互動</li>
      <li>2023-2024 數學競賽隊長 — 規劃訓練與帶隊</li>
    </ul>
  </section>

  <!-- 學歷 -->
  <section id="education">
    <h2>學歷</h2>
    <p>某某高中 (2023 — 2026 預計畢業)</p>
  </section>

  <!-- 聯絡方式 -->
  <section id="contact">
    <h2>聯絡方式</h2>
    <p><strong>Email：</strong>your.email@example.com</p>
    <p><strong>電話：</strong>09xx-xxx-xxx</p>
    <p><strong>GitHub：</strong><a href="https://github.com/yourname" target="_blank">github.com/yourname</a></p>
  </section>

  <footer>
    © 2025 你的姓名 — 個人履歷網站
  </footer>

</body>
</html>


