<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>我的個人履歷</title>
  <style>
    body {
      max-width: 700px;
      margin: 0 auto;
      padding: 24px;
      font-family: "Noto Sans TC", sans-serif;
      color: #333;
      line-height: 1.6;
    }
    h1 {
      font-size: 2.4rem;
      margin-bottom: 0.2em;
    }
    h2 {
      font-size: 1.6rem;
      margin-top: 1.4em;
      margin-bottom: 0.4em;
      border-bottom: 2px solid #ccc;
      padding-bottom: 0.2em;
    }
    .section {
      margin-bottom: 1.2em;
    }
    .info-line {
      margin: 0.4em 0;
    }
    .label {
      font-weight: 600;
    }
    .list {
      margin: 0;
      padding-left: 1.4em;
    }
    img.avatar {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      display: block;
      margin-bottom: 1em;
    }
    @media (max-width: 480px) {
      body {
        padding: 16px;
      }
      h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>
  <!-- 如果要放大頭貼，取消下面 img 標籤的註解並放入你的圖片連結 -->
  <!-- <img class="avatar" src="你的照片網址.jpg" alt="頭貼"> -->

  <h1>你的姓名</h1>

  <div class="section">
    <h2>基本資料</h2>
    <p class="info-line"><span class="label">生日：</span>YYYY / MM / DD</p>
    <p class="info-line"><span class="label">目前就讀：</span>高中／大學、科系或年級</p>
    <p class="info-line"><span class="label">Email：</span>your.email@example.com</p>
    <p class="info-line"><span class="label">電話：</span>09xx-xxx-xxx</p>
  </div>

  <div class="section">
    <h2>興趣 / 喜好</h2>
    <p>（簡短幾句話或列點）</p>
    <ul class="list">
      <li>興趣一</li>
      <li>興趣二</li>
      <li>興趣三</li>
    </ul>
  </div>

  <div class="section">
    <h2>社團經歷 / 活動</h2>
    <ul class="list">
      <li>社團或活動名稱 — 職務 / 參與時段</li>
      <li>另一個活動 — 職務 / 時段</li>
    </ul>
  </div>

  <div class="section">
    <h2>個人特質 / 自我介紹</h2>
    <p>這裡寫幾句你自己的性格、優點、工作態度或特色。</p>
  </div>

  <div class="section">
    <h2>學習目標 / 未來方向</h2>
    <p>你希望達到什麼、未來想學什麼、做什麼樣的專案。</p>
  </div>
</body>
</html>

