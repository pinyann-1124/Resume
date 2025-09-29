my-resume/
│
├─ index.html
├─ style.css
└─ avatar.jpg   （放你的照片，檔名可以自己改）

</body>
</html>
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>我的履歷</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <!-- 導覽列 -->
  <nav class="navbar">
    <a href="#profile">首頁</a>
    <a href="#info">基本資料</a>
    <a href="#interest">興趣愛好</a>
    <a href="#clubs">社團經歷</a>
    <a href="#traits">個人特質</a>
    <a href="#goals">學習目標</a>
  </nav>

  <main>
    <section id="profile" class="profile">
      <img src="avatar.jpg" alt="我的照片" class="avatar" />
      <h1>你的名字</h1>
    </section>

    <section id="info">
      <h2>基本資料</h2>
      <p>生日：2007/05/12</p>
      <p>星座：金牛座</p>
      <p>學校：中原大學 資工系</p>
      <p>Email：xxx@gmail.com</p>
    </section>

    <section id="interest">
      <h2>興趣愛好</h2>
      <ul>
        <li>喜歡吃：雞翅、辣、無糖茶</li>
        <li>喜歡：貓咪、吉伊卡哇</li>
        <li>活動：聽音樂、跑步</li>
        <li>科目：數學、音樂</li>
      </ul>
    </section>

    <section id="clubs">
      <h2>社團經歷</h2>
      <p>音創社 kb 手、圖書館社 副社長</p>
    </section>

    <section id="traits">
      <h2>個人特質</h2>
      <p>樂觀、有自我要求，願意花時間去解決問題。</p>
    </section>

    <section id="goals">
      <h2>學習目標</h2>
      <p>提升英文與表達能力，學習更多技術，增強程式設計與專題經驗。</p>
    </section>
  </main>
</body>
</html>
/* 全域樣式 */
body {
  margin: 0;
  font-family: "Noto Sans TC", sans-serif;
  background: #f5f5f5;
  color: #333;
}

/* 導覽列 */
.navbar {
  position: sticky;
  top: 0;
  background: #1f3b73;
  padding: 10px;
  display: flex;
  justify-content: center;
  gap: 16px;
  z-index: 1000;
}
.navbar a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  padding: 6px 10px;
  transition: background 0.3s;
}
.navbar a:hover {
  background: #6ea8fe;
  border-radius: 6px;
}

/* 主體區 */
main {
  max-width: 700px;
  margin: 40px auto;
  padding: 32px;
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.profile {
  text-align: center;
  margin-bottom: 40px;
}
.avatar {
  width: 140px;
  height: 140px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #6ea8fe;
  margin-bottom: 16px;
}
h1 {
  margin: 0;
  font-size: 2.2rem;
  color: #1f3b73;
}

/* 區塊標題 */
h2 {
  margin-top: 28px;
  margin-bottom: 12px;
  font-size: 1.4rem;
  color: #1f3b73;
  border-left: 4px solid #6ea8fe;
  padding-left: 8px;
}

p, li {
  margin: 6px 0;
  line-height: 1.6;
}
ul {
  padding-left: 20px;
}

/* 手機版調整 */
@media (max-width: 480px) {
  main {
    padding: 20px;
  }
  .avatar {
    width: 100px;
    height: 100px;
  }
  h1 {
    font-size: 1.6rem;
  }
  .navbar {
    flex-wrap: wrap;
    gap: 8px;
  }
}
