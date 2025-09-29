/* 全域 */
body {
  margin: 0;
  padding: 0;
  font-family: "Noto Sans TC", sans-serif;
  background: #f5f5f5;
  color: #333;
  line-height: 1.6;
}

/* 主容器 */
main {
  max-width: 700px;
  margin: 0 auto;
  padding: 48px 16px;
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 6px 18px rgba(0,0,0,0.1);
}

/* 頭像與姓名區 */
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
.profile h1 {
  margin: 0;
  font-size: 2.4rem;
  color: #1f3b73;
}

/* 各區塊標題 */
section h2 {
  font-size: 1.6rem;
  margin-top: 32px;
  margin-bottom: 12px;
  border-left: 4px solid #6ea8fe;
  padding-left: 8px;
  color: #1f3b73;
}

/* 區段內容 */
section p {
  margin: 6px 0;
}

/* 響應式 */
@media (max-width: 480px) {
  main {
    padding: 32px 12px;
  }
  .avatar {
    width: 100px;
    height: 100px;
  }
  .profile h1 {
    font-size: 1.8rem;
  }
  section h2 {
    font-size: 1.3rem;
  }
}


