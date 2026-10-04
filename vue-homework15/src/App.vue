<template>
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">
        My Website
      </a>

      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">

          <li class="nav-item">
            <a class="nav-link active" href="#">
              Home
            </a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#">
              About
            </a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#">
              Contact
            </a>
          </li>

        </ul>
      </div>
    </div>
  </nav>


  <!-- Hero -->
  <section class="bg-primary text-white py-5">
    <div class="container py-5">

      <div class="row align-items-center">

        <div class="col-md-7">
          <h1 class="display-4 fw-bold">
            Welcome to My Website
          </h1>

          <p class="lead">
            เว็บไซต์ตัวอย่างที่พัฒนาด้วย Vue.js 3
            และ Bootstrap 5
          </p>

          <button class="btn btn-light btn-lg">
            Learn More
          </button>
        </div>

        <div class="col-md-5 text-center">
          <div class="bg-white text-primary rounded-4 shadow p-5">
            <h2 class="fw-bold">
              Vue.js 3
            </h2>

            <p class="mb-0">
              The Progressive JavaScript Framework
            </p>
          </div>
        </div>

      </div>

    </div>
  </section>


  <!-- Features -->
  <section class="py-5">
    <div class="container">

      <div class="text-center mb-5">
        <h2 class="fw-bold">
          เทคโนโลยีที่ใช้
        </h2>

        <p class="text-muted">
          การพัฒนาเว็บไซต์ด้วย Vue.js 3 และ Bootstrap 5
        </p>
      </div>

      <div class="row g-4">

        <div class="col-md-4">
          <div class="card h-100 shadow-sm">
            <div class="card-body text-center p-4">

              <h3>💚</h3>

              <h4 class="card-title">
                Vue.js 3
              </h4>

              <p class="card-text text-muted">
                Framework สำหรับพัฒนาเว็บไซต์
                และ Web Application
              </p>

            </div>
          </div>
        </div>


        <div class="col-md-4">
          <div class="card h-100 shadow-sm">
            <div class="card-body text-center p-4">

              <h3>🎨</h3>

              <h4 class="card-title">
                Bootstrap 5
              </h4>

              <p class="card-text text-muted">
                Framework สำหรับออกแบบเว็บไซต์
                ให้สวยงามและ Responsive
              </p>

            </div>
          </div>
        </div>


        <div class="col-md-4">
          <div class="card h-100 shadow-sm">
            <div class="card-body text-center p-4">

              <h3>💻</h3>

              <h4 class="card-title">
                Web Development
              </h4>

              <p class="card-text text-muted">
                เรียนรู้การสร้างเว็บไซต์
                ด้วยเทคโนโลยีสมัยใหม่
              </p>

            </div>
          </div>
        </div>

      </div>

    </div>
  </section>


<footer class="bg-dark text-white text-center py-4">
  <p class="mb-1">
    Vue.js 3 & Bootstrap 5
  </p>

  <p class="mb-0">
    รหัสนักศึกษา: 69711889 | ชื่อ: ชินาธิป บำรุงรักษ์
  </p>
</footer>

</template>
