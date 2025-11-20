
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Vasu Thatapudi — Portfolio Preview</title>
  <style>
    /* Simple, modern reset + typography */
    :root{
      --bg:#ffffff; --muted:#6b7280; --accent:#1e40af; --card:#f9fafb;
      --container:1100px;
      --radius:12px;
    }
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial; color:#0f172a;background:var(--bg);-webkit-font-smoothing:antialiased}
    a{color:var(--accent); text-decoration:none;}
    .container{max-width:var(--container);margin:0 auto;padding:32px}
    header{background:#fff;position:sticky;top:0;z-index:40;border-bottom:1px solid #eef2ff}
    .header-inner{display:flex;align-items:center;justify-content:space-between;max-width:var(--container);margin:0 auto;padding:14px 32px}
    .brand{font-weight:600;font-size:18px}
    nav a{margin-left:18px;font-size:14px;color:#0f172a;opacity:.85}
    .btn{display:inline-block;padding:10px 14px;border-radius:8px;background:var(--accent);color:#fff;font-weight:600}
    .btn-outline{border:1px solid var(--accent);padding:10px 14px;border-radius:8px;color:var(--accent);background:transparent}
    /* Hero */
    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;padding:56px 32px;align-items:center}
    .heading{font-size:34px;line-height:1.05;margin:0 0 18px}
    .lead{color:var(--muted);margin:0 0 22px}
    .card{background:var(--card);padding:20px;border-radius:var(--radius);box-shadow:0 8px 20px rgba(2,6,23,0.06)}
    .list{padding-left:18px;margin:12px 0;color:var(--muted)}
    /* Grid sections */
    section{padding:40px 32px}
    .section-title{font-size:22px;margin:0 0 18px;font-weight:600}
    .skills-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:14px}
    .skill{background:#fff;padding:14px;border-radius:10px;box-shadow:0 6px 16px rgba(2,6,23,0.04);text-align:center;font-weight:600}
    .cards{display:grid;grid-template-columns:repeat(2,1fr);gap:18px}
    .card h4{margin:0 0 8px;font-size:16px}
    .badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:10px}
    .badge{background:#f3f4f6;padding:6px 10px;border-radius:8px;font-size:12px}
    /* Contact */
    .contact-box{background:var(--accent);color:#fff;padding:26px;border-radius:14px;max-width:560px}
    .contact-box a{background:#fff;color:var(--accent);padding:10px 14px;border-radius:10px;font-weight:700;display:inline-block;margin-top:12px}
    footer{padding:24px;text-align:center;color:var(--muted);font-size:13px}
    /* Responsive */
    @media (max-width:900px){
      .hero{grid-template-columns:1fr; padding:32px}
      .cards{grid-template-columns:1fr}
      .skills-grid{grid-template-columns:repeat(2,1fr)}
      nav{display:none}
    }
    @media (max-width:520px){
      .skills-grid{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <header>
    <div class="header-inner">
      <div class="brand">Vasu Thatapudi</div>
      <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#experience">Experience</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
      <a class="btn" href="/assets/Vasu_Thatapudi_QA.pdf" download>Resume</a>
    </div>
  </header>

  <main class="container">
    <!-- Hero -->
    <div class="hero" id="about">
      <div>
        <h1 class="heading">QA Analyst & ETL Tester</h1>
        <p class="lead">I specialise in validating large-scale data migrations from on-prem systems to cloud data platforms. My focus areas include Azure Data Factory pipeline validation, source-to-target mapping, reconciliation and automation of data quality checks. Experienced in ADF, Databricks and SQL/PySpark assertions.</p>
        <div style="display:flex;gap:12px">
          <a class="btn" href="#projects">See Migration Projects</a>
          <a class="btn-outline" href="#contact">Contact</a>
        </div>
      </div>

      <aside class="card">
        <h3 style="margin:0 0 8px">Quick Snapshot</h3>
        <ul class="list">
          <li><strong>Speciality:</strong> On-prem → Cloud migrations, ADF validation</li>
          <li><strong>Experience:</strong> 3+ yrs QA / ETL testing</li>
          <li><strong>Tools:</strong> Azure Data Factory, Databricks, SQL</li>
          <li><strong>Testing Areas:</strong> S2T mapping, reconciliation, incremental loads</li>
          <li><strong>Email:</strong> thatapudivasu92@gmail.com</li>
          <li><strong>Phone:</strong> +91 8179339554</li>
        </ul>
      </aside>
    </div>

    <!-- Skills -->
    <section id="skills">
      <h2 class="section-title">Core Competencies</h2>

      <div class="skills-grid">
        <div class="skill">ETL Testing</div>
        <div class="skill">Azure Data Factory</div>
        <div class="skill">Databricks</div>
        <div class="skill">Automation Testing</div>
        <div class="skill">SQL</div>
        <div class="skill">Python</div>
        <div class="skill">JIRA</div>
        <div class="skill">HP ALM</div>
        <div class="skill">Agile Methodology</div>
      </div>
    </section>

    <!-- Experience -->
    <section id="experience">
      <h2 class="section-title">Experience</h2>

      <div class="cards">
        <div class="card">
          <h4>Quality Assurance Analyst — Tata Consultancy Services</h4>
          <div style="color:var(--muted);font-size:13px;margin-bottom:10px">May 2022 — Present</div>
          <ul class="list">
            <li>Validated large-scale on-prem → cloud migrations using S2T mapping and reconciliation checks.</li>
            <li>Designed and executed ADF pipeline validation covering activities, dataflows, parameters, triggers and monitoring.</li>
            <li>Implemented SQL & PySpark assertions for row counts, aggregates, nullability and transformations.</li>
            <li>Tested incremental loads (CDC/watermarks), late arrivals and idempotency across runs.</li>
            <li>Collaborated with data engineers to define data contracts and validation gates.</li>
          </ul>
        </div>

        <div class="card">
          <h4>Production Engineer — VEM Technologies</h4>
          <div style="color:var(--muted);font-size:13px;margin-bottom:10px">Oct 2019 — May 2022</div>
          <ul class="list">
            <li>Led process optimization and inspection procedures to improve product quality.</li>
            <li>Applied automation and analytics to reduce defects and improve throughput.</li>
            <li>Documented process changes and ensured compliance with quality standards.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects">
      <h2 class="section-title">Highlighted Migration & ADF Validation Projects</h2>

      <div class="cards">
        <div class="card">
          <h4>On-Prem Finance DB → Azure Data Lake</h4>
          <p style="color:var(--muted);margin:8px 0 12px">Performed full & incremental validation of ADF pipelines migrating Oracle transactional/dimensional data to Azure Data Lake (Parquet). Implemented row-level reconciliation and aggregate checks.</p>
          <div class="badges">
            <div class="badge">ADF</div><div class="badge">Databricks</div><div class="badge">SQL</div><div class="badge">S2T</div>
          </div>
        </div>

        <div class="card">
          <h4>ADF Pipeline Validation — Customer Data Migration</h4>
          <p style="color:var(--muted);margin:8px 0 12px">Validated activities, dataflows, parameter passing and triggers. Built automated SQL/PySpark checks for schema, duplicates and quality metrics; integrated with CI/CD.</p>
          <div class="badges">
            <div class="badge">ADF</div><div class="badge">Triggers</div><div class="badge">PySpark</div><div class="badge">CI/CD</div>
          </div>
        </div>

        <div class="card">
          <h4>Incremental Load Testing with CDC</h4>
          <p style="color:var(--muted);margin:8px 0 12px">Tested CDC and watermark-based incremental loads, verified idempotency and late-arriving record handling, and reconciled cumulative aggregates.</p>
          <div class="badges">
            <div class="badge">CDC</div><div class="badge">Watermarks</div><div class="badge">Idempotency</div>
          </div>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact">
      <h2 class="section-title">Contact</h2>
      <p style="color:var(--muted);margin-bottom:12px">I am actively seeking opportunities in ETL Testing, Data Quality Engineering, and ADF pipeline validation. If my skills align with your requirements, please reach out to discuss how I can contribute to your data initiatives.</p>

      <div class="contact-box">
        <div style="font-size:18px;font-weight:700;margin-bottom:6px">✉️ Contact Now</div>
        <div style="font-size:15px">thatapudivasu92@gmail.com</div>
        <a href="mailto:thatapudivasu92@gmail.com">Send Email</a>
      </div>
    </section>
  </main>

  <footer>
    © <span id="year"></span> Vasu Thatapudi
  </footer>

  <script>document.getElementById('year').textContent = new Date().getFullYear();</script>
</body>
</html>
