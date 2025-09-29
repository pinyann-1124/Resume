<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>我的履歷</title>
  <style>
    /* 全域樣式 */
    body {
      margin: 0;
      font-family: "Noto Sans TC", sans-serif;
      background: linear-gradient(135deg, #6ea8fe, #e2e6f0);
      color: #333;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
    }

    /* 頭部卡片 */
    .header {
      background: #fff;
      border-radius: 16px;
      padding: 30px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      text-align: center;
      margin-bottom: 30px;
    }

    .avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #6ea8fe;
      margin-bottom: 16px;
    }

    h1 {
      margin: 0;
      font-size: 2rem;
      color: #1f3b73;
    }
    p.subtitle {
      color: #6b7280;
      margin-top: 8px;
    }

    /* 區塊卡片 */
    .card {
      background: #fff;
      border-radius: 12px;
      padding: 20px 24px;
      margin-bottom: 20px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    }

    h2 {
      margin-top: 0;
      font-size: 1.4rem;
      color: #1f3b73;
      border-left: 4px solid #6ea8fe;
      padding-left: 10px;
    }

    ul {
      padding-left: 20px;
      margin: 0;
    }
    li {
      margin-bottom: 6px;
    }

    /* 聯絡方式 */
    .contact p {
      margin: 6px 0;
    }

    /* 響應式 */
    @media (max-width: 600px) {
      .container { padding: 20px 12px; }
      .avatar { width: 100px; height: 100px; }
      h1 { font-size: 1.6rem; }
    }
  </style>
</head>
<body>
  <div class="container">

    <!-- 頭部 -->
    <div class="header">
      <img class="avatar" src="你的照片網址.jpg" alt="頭像">
      <h1>你的姓名</h1>
      <p class="subtitle">想申請的職位 / 科系</p>
    </div>

    <!-- 基本資料 -->
    <div class="card contact">
      <h2>基本資料</h2>
      <p><strong>電話：</strong>09xx-xxx-xxx</p>
      <p><strong>Email：</strong>your.email@example.com</p>
      <p><strong>住址：</strong>台北市</p>
      <p><strong>作品集：</strong><a href="https://github.com/yourname" target="_blank">GitHub</a></p>
    </div>

    <!-- 技能 -->
    <div class="card">
      <h2>技能</h2>
      <ul>
        <li>HTML / CSS / JavaScript</li>
        <li>React / 前端基礎</li>
        <li>數學邏輯、圖形空間感強</li>
      </ul>
    </div>

    <!-- 經歷 -->
    <div class="card">
      <h2>經歷</h2>
      <ul>
        <li>2024 校內網站專案 — 前端切版 & JS 互動</li>
        <li>2023-2024 數學競賽隊長 — 帶領隊員規劃訓練</li>
      </ul>
    </div>

    <!-- 學歷 -->
    <div class="card">
      <h2>教育背景</h2>
      <p>某某高中 (2023 — 2026 預計畢業)</p>
    </div>

    <!-- 自我介紹 -->
    <div class="card">
      <h2>自我介紹</h2>
      <p>我擅長邏輯分析與數學題解，對程式設計有熱情。希望在實習與大學科系中，累積更多專案經驗並貢獻團隊。</p>
    </div>

  </div>
</body>
</html>

