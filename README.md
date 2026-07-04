<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <title>我的作品集</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- 導覽列 -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">我的作品集</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#about">關於我</a></li>
          <li class="nav-item"><a class="nav-link" href="#projects">作品</a></li>
          <li class="nav-item"><a class="nav-link" href="#contact">聯絡</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- 關於我 -->
  <section id="about" class="container py-5">
    <h2 class="mb-4">關於我</h2>
    <p>嗨！我是 XXX，一位專注於前端開發與設計的創作者，擅長 HTML、CSS、JavaScript 與 Bootstrap。</p>
  </section>

  <!-- 作品展示 -->
  <section id="projects" class="container py-5">
    <h2 class="mb-4">作品展示</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card h-100 shadow">
          <img src="https://via.placeholder.com/400x200" class="card-img-top" alt="專案 A">
          <div class="card-body">
            <h5 class="card-title">專案 A</h5>
            <p class="card-text">這是一個響應式網站設計案例。</p>
            <a href="#" class="btn btn-primary">查看專案</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 shadow">
          <img src="https://via.placeholder.com/400x200" class="card-img-top" alt="專案 B">
          <div class="card-body">
            <h5 class="card-title">專案 B</h5>
            <p class="card-text">這是一個前端互動效果展示。</p>
            <a href="#" class="btn btn-primary">查看專案</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 shadow">
          <img src="https://via.placeholder.com/400x200" class="card-img-top" alt="專案 C">
          <div class="card-body">
            <h5 class="card-title">專案 C</h5>
            <p class="card-text">這是一個 UI/UX 設計案例。</p>
            <a href="#" class="btn btn-primary">查看專案</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- 聯絡方式 -->
  <section id="contact" class="container py-5">
    <h2 class="mb-4">聯絡我</h2>
    <p>Email: example@email.com</p>
    <p>LinkedIn: linkedin.com/in/example</p>
    <p>GitHub: github.com/example</p>
  </section>

  <!-- 頁尾 -->
  <footer class="bg-dark text-white text-center py-3">
    © 2026 我的作品集
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
