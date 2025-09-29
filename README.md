<!doctype html>
<html lang="zh-Hant">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>簡約履歷範本 — 塗 品妍</title>
  <style>
    :root{
      --bg:#f7f8fb; --card:#ffffff; --accent:#1f6feb; --muted:#6b7280; --glass:rgba(31,111,235,0.06);
      --radius:12px; --pad:18px;
      font-family: "Noto Sans TC", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:18px;background:var(--bg);color:#111}
    .container{max-width:900px;margin:0 auto}

    /* Header */
    .card{background:var(--card);border-radius:var(--radius);box-shadow:0 6px 18px rgba(16,24,40,0.06);overflow:hidden}
    header{display:flex;gap:18px;align-items:center;padding:20px}
    .avatar{width:96px;height:96px;border-radius:12px;background:linear-gradient(135deg,var(--glass),transparent);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:28px;color:var(--accent)}
    .name-block{flex:1}
    h1{margin:0;font-size:20px}
    p.role{margin:6px 0 0;color:var(--muted)}

    /* two-column layout */
    .grid{display:grid;grid-template-columns:260px 1fr;gap:18px;padding:18px}

    /* left column (contact + skills) */
    .side{display:flex;flex-direction:column;gap:12px}
    .box{background:linear-gradient(180deg,rgba(0,0,0,0.01),transparent);padding:14px;border-radius:10px}
    .label{font-size:13px;color:var(--muted);margin-bottom:8px}
    .contact-list{display:flex;flex-direction:column;gap:8px;font-size:14px}
    .contact-item{display:flex;gap:8px;align-items:center}
    .chip{display:inline-block;padding:6px 8px;border-radius:999px;background:#f1f5f9;font-size:13px}

    /* main column */
    section{margin-bottom:12px}
    .section-title{display:flex;justify-content:space-between;align-items:center;margin-bottom:8px}
    h2{margin:0;font-size:14px}
    .summary{font-size:14px;color:#111;line-height:1.5}

    /* experience rows */
    .exp{display:grid;grid-template-columns:1fr 110px;gap:12px;padding:10px;border-radius:8px}
    .exp + .exp{margin-top:8px}
    .role{font-weight:600}
    .company{color:var(--muted);font-size:13px;margin-top:6px}
    .period{text-align:right;color:var(--muted);font-size:13px}
    .bullets{margin-top:8px;color:#333;font-size:14px}
    .bullets li{margin-bottom:6px}

    /* education & awards as table-like */
    .table{width:100%;border-collapse:collapse}
    .table td{padding:8px 6px;border-bottom:1px dashed #e6e9ef}
    .footer{padding:18px;text-align:center;color:var(--muted);font-size:13px}

    @media (max-width:720px){
      .grid{grid-template-columns:1fr;}
      header{flex-direction:column;align-items:flex-start}
      .avatar{width:80px;height:80px}
      .period{text-align:left}
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <header>
        <div class="avatar">TP</div>
        <div class="name-block">
          <h1>塗 品妍（範本）</h1>
          <p class="role">申請職位 / 目標：前端實習生 / 資訊相關科系申請</p>
        </div>
        <div style="text-align:right;min-width:160px">
          <div class="chip">可立即到職</div>
        </div>
      </header>

      <div class="grid">
        <!-- left column -->
        <aside class="side">
          <div class="box">
            <div class="label">聯絡資訊</div>
            <div class="contact-list">
              <div class="contact-item"><strong>電話：</strong><span>09xx-xxx-xxx</span></div>
              <div class="contact-item"><strong>Email：</strong><span>your.email@example.com</span></div>
              <div class="contact-item"><strong>住址：</strong><span>台北市 / 可遠端</span></div>
              <div class="contact-item"><strong>作品：</strong><span>github.com/yourname</span></div>
            </div>
          </div>

          <div class="box">
            <div class="label">技能重點</div>
            <div style="display:flex;flex-wrap:wrap;gap:8px">
              <span class="chip">HTML</span>
              <span class="chip">CSS</span>
              <span class="chip">JavaScript</span>
              <span class="chip">React</span>
              <span class="chip">資料結構</span>
              <span class="chip">數學/邏輯</span>
            </div>
          </div>

          <div class="box">
            <div class="label">語言</div>
            <div style="display:flex;flex-direction:column;gap:6px">
              <div>中文（母語）</div>
              <div>英文（中級）</div>
            </div>
          </div>
        </aside>

        <!-- main column -->
        <main>
          <section>
            <div class="section-title"><h2>自傳摘要（重點式）</h2></div>
            <div class="summary">具備良好數學與邏輯思維，擅長以清晰結構拆解問題。對前端基礎（HTML/CSS/JS）有實作經驗，喜歡把資訊用簡潔的視覺呈現。希望在實習中強化專案經驗並貢獻團隊。</div>
          </section>

          <section>
            <div class="section-title"><h2>實習 / 工作經驗</h2></div>

            <div class="exp">
              <div>
                <div class="role">前端實作專案 — 校內網站</div>
                <div class="company">學校專案 • 團隊 3 人</div>
                <ul class="bullets">
                  <li>負責頁面切版與響應式佈局（HTML/CSS）。</li>
                  <li>使用 JavaScript 實作互動元件，提升使用者體驗。</li>
                </ul>
              </div>
              <div class="period">2024.07 — 2024.09</div>
            </div>

            <div class="exp">
              <div>
                <div class="role">數學競賽隊長</div>
                <div class="company">校內活動</div>
                <ul class="bullets">
                  <li>組織練習日程並帶領小組討論解題策略。</li>
                  <li>訓練邏輯思維與空間題解法。</li>
                </ul>
              </div>
              <div class="period">2023.09 — 2024.05</div>
            </div>
          </section>

          <section>
            <div class="section-title"><h2>教育背景</h2></div>
            <table class="table">
              <tr><td><strong>學校</strong> 高中 — 範例高中</td><td style="text-align:right">2023 — 2026 (預計)</td></tr>
              <tr><td><strong>課程重點</strong> 資訊／數學相關選修</td><td style="text-align:right">GPA: —</td></tr>
            </table>
          </section>

          <section>
            <div class="section-title"><h2>證照 / 獎項</h2></div>
            <ul class="bullets">
              <li>數學競賽獎項 — 校內競賽（2024）</li>
              <li>全民英檢中級（或準備中）</li>
            </ul>
          </section>

          <section>
            <div class="section-title"><h2>其他（可選）</h2></div>
            <div class="summary">興趣：熱舞、設計、閱讀。可列出社團或志工經驗。</div>
          </section>
        </main>
      </div>

      <div class="footer">版面簡潔、重點式履歷 — 可直接複製到 HTML 檔修改內容</div>
    </div>
  </div>
</body>
</html>
