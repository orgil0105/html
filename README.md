<!DOCTYPE html>
<html lang="mn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aegis Cyber Defense</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      background-color: #0b0f1a;
      color: #e5e7eb;
      line-height: 1.6;
    }

    header {
      height: 100vh;
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.8)), url('background.jpg') center/cover no-repeat;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    header h1 {
      font-size: 3rem;
      color: #38bdf8;
      margin-bottom: 15px;
    }

    header p {
      max-width: 700px;
      font-size: 1.1rem;
      color: #d1d5db;
    }

    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }

    h2 {
      color: #38bdf8;
      margin-bottom: 20px;
      font-size: 2rem;
      text-align: center;
    }

    .about p {
      text-align: center;
      max-width: 900px;
      margin: auto;
      font-size: 1rem;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 40px;
    }

    .card {
      background-color: #111827;
      padding: 25px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0,0,0,0.4);
    }

    .card h3 {
      color: #7dd3fc;
      margin-bottom: 10px;
    }

    .card p {
      font-size: 0.95rem;
      color: #d1d5db;
    }

    .mission {
      background-color: #020617;
      border-radius: 10px;
      padding: 40px;
      text-align: center;
    }

    footer {
      background-color: #020617;
      text-align: center;
      padding: 30px 20px;
      font-size: 0.9rem;
      color: #9ca3af;
    }

    footer span {
      color: #38bdf8;
    }
  </style>
</head>
<body>

  <!-- HERO SECTION -->
  <header>
    <h1>Aegis Cyber Defense</h1>
    <p>
      Бид кибер орчны аюулгүй байдлыг хангах, мэдээллийн нууцлал, бүрэн бүтэн байдал,
      тасралтгүй ажиллагааг хамгаалахад чиглэсэн мэргэжлийн кибер аюулгүй байдлын байгууллага юм.
    </p>
  </header>

  <!-- ABOUT SECTION -->
  <section class="about">
    <h2>Бидний тухай</h2>
    <p>
      Aegis Cyber Defense нь байгууллага, төрийн болон хувийн хэвшлийн системүүдийг
      кибер халдлага, эмзэг байдлаас хамгаалах зорилготойгоор үйл ажиллагаа явуулдаг.
      Бид олон улсын стандарт, шилдэг туршлагад суурилсан шийдлүүдийг санал болгож,
      урьдчилан сэргийлэх, илрүүлэх, хариу арга хэмжээ авах цогц үйлчилгээг үзүүлдэг.
    </p>
  </section>

  <!-- SERVICES SECTION -->
  <section>
    <h2>Манай үйлчилгээ</h2>
    <div class="services">
      <div class="card">
        <h3>Эмзэг байдлын шинжилгээ</h3>
        <p>
          Сүлжээ, систем, вэб аппликейшний эмзэг байдлыг илрүүлж,
          эрсдэлийн үнэлгээ хийж, засварлах зөвлөмж өгнө.
        </p>
      </div>
      <div class="card">
        <h3>Penetration Testing</h3>
        <p>
          Бодит халдлагын загвараар системийг шалгаж,
          хамгаалалтын бодит түвшинг тодорхойлно.
        </p>
      </div>
      <div class="card">
        <h3>Сүлжээ ба серверийн хамгаалалт</h3>
        <p>
          Firewall, IDS/IPS, hardening тохиргоо хийж,
          дотоод болон гадаад аюул заналыг бууруулна.
        </p>
      </div>
      <div class="card">
        <h3>Кибер сургалт, зөвлөх үйлчилгээ</h3>
        <p>
          Ажилтнуудад зориулсан кибер аюулгүй байдлын сургалт,
          бодлого, журам боловсруулах зөвлөгөө өгнө.
        </p>
      </div>
    </div>
  </section>

  <!-- MISSION SECTION -->
  <section>
    <div class="mission">
      <h2>Бидний эрхэм зорилго</h2>
      <p>
        Монгол Улс болон бүс нутгийн хэмжээнд кибер аюулгүй байдлын
        соёлыг төлөвшүүлж, байгууллагуудын мэдээллийн системийг
        найдвартай, аюулгүй байлгахад хувь нэмэр оруулах.
      </p>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>
      © 2025 <span>Aegis Cyber Defense</span> — Кибер аюулгүй байдлын мэргэжлийн шийдэл
    </p>
    <p>Contact: info@aegiscyber.mn</p>
  </footer>

</body>
</html>
