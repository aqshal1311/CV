<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Curriculum Vitae — Aqshal Hadi Alifvyansyach</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --accent-green:#1e9b4a;
      --accent-blue:#0b75d1;
      --text:#222;
      --muted:#5b6166;
      --page-bg:#fff;
      --paper-border:#111;
      font-size:16px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background:#f4f4f6;
      margin:24px;
      color:var(--text);
      -webkit-print-color-adjust:exact;
    }

    /* Paper container */
    .paper{
      max-width:900px;
      margin:0 auto;
      background:var(--page-bg);
      border:4px solid var(--paper-border);
      padding:48px 64px;
      height:1122px; /* approx A4 portrait height to keep single page */
      overflow:hidden;
      position:relative;
    }

    /* Top rule */
    .top-rule{
      height:4px;
      background:#222;
      width:70%;
      margin-bottom:22px;
    }

    header{
      display:flex;
      flex-direction:column;
      gap:6px;
      margin-bottom:18px;
    }
    h1{
      font-size:40px;
      margin:0;
      font-weight:600;
      letter-spacing:0.2px;
    }
    .title-sub{color:var(--accent-green);font-weight:600}

    .contact{
      margin-top:12px;
      color:var(--muted);
      line-height:1.45;
    }

    /* Sections */
    .section{
      margin-top:18px;
    }
    .section h2{
      color:var(--accent-green);
      margin:8px 0 8px 0;
      font-size:18px;
    }
    .section h3{
      color:var(--accent-blue);
      margin:6px 0 6px 0;
      font-size:16px;
    }
    p, ul{margin:6px 0 12px 0}
    ul{padding-left:20px}
    li{margin-bottom:6px}

    .skills{line-height:1.6}

    /* Footer / across the internet */
    .internet{
      margin-top:18px;
      color:var(--muted);
    }

    /* small print for mobile/print adjustments */
    @media (max-width:700px){
      .paper{padding:28px 22px}
      h1{font-size:28px}
    }

    /* Hidden reference to uploaded template image (local file path) */
    /* Template image path: /mnt/data/resume-template-zyl70.png */
    .template-ref{display:none}
  </style>
</head>
<body>
  <div class="paper" role="document">
    <img class="template-ref" src="/mnt/data/resume-template-zyl70.png" alt="template reference">
    <div class="top-rule" aria-hidden="true"></div>

    <header>
      <h1>Aqshal Hadi Alifvyansyach</h1>
      <div class="title-sub">Junior Frontend Developer</div>
      <div class="contact">
        Sorosutan UH 6/898, RT.17/RW.5, Sorosutan, Kec. Umbulharjo, Kota Yogyakarta, Daerah Istimewa Yogyakarta • Kota Yogyakarta, 55162<br>
        (+62) 821-4021-3894 • aqshalhadi27@gmail.com
      </div>
    </header>

    <main>
      <section class="section">
        <h2>Skills</h2>
        <div class="skills">Programming Languages (Java, Python, HTML), Web Development (HTML, JavaScript, PHP), Database (MySQL), Operating Systems (Linux), Data Analysis and Visualization (Python, Pandas), UI/UX Design (Canva, Figma), Graphic Design, Data Entry, Software Development, Information Security, Basic Microsoft Office (Microsoft Word, Microsoft Excel, and Microsoft PowerPoint), SPSS</div>
      </section>

      <section class="section">
        <h2>Education</h2>
        <h3>Ahmad Dahlan University, Yogyakarta</h3>
        <div class="muted">Month 2021 to Month 2025</div>
        <p>Ahmad Dahlan University Yogyakarta student with a strong background in Information Technology, particularly software development and data processing. Proficient in database management, data analysis, and information security. Possesses practical skills in various programming languages ​​and software development tools. Ready to contribute professionally within a dynamic team to support the achievement of organizational goals.</p>
      </section>

      <section class="section">
        <h2>Experience</h2>

        <h3>Yogyakarta, Indonesia</h3>
        <div class="muted">2021 to Month 2025</div>
        <ul>
          <li>Member of the 2021 UAD Technopreneur Webinar.</li>
          <li>Junior Cyber Security Training for the 2024 Digital Talent Scholarship.</li>
          <li>UAD Soft Skills Training.</li>
          <li>Member of the UAD Soft Skills Socialization Activity.</li>
        </ul>

        <h3 style="margin-top:14px">Town Hall, Yogyakarta</h3>
        <div class="muted">October 2024 to January 2025</div>
        <ul>
          <li>Internship in Website Management and Multimedia-Based Content Design.</li>
        <div>Skills: List of skills used or gained at this company</div>
      </section>

      <section class="section internet">
        <h2 style="color:var(--accent-green); margin-bottom:6px">Across the Internet</h2>
        <div>linkedin.com/in/aqshal-hadi-alifvyansyach-023ab930a, github.com/aqshal1311</div>
      </section>
    </main>

  </div>
</body>
</html>

[([https://codepen.io/Aqshal-Hadi-Alifvyansyach/pen/JoXrOww](https://github.com/aqshal1311/CV/tree/main/cv)).](https://roadmap.sh/projects/single-page-cv)
