<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dylan Weaver - Resume</title>
  <style>
    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background: #f9fafb;
      color: #1f2937;
      line-height: 1.6;
    }
    .container {
      display: grid;
      grid-template-columns: 280px 1fr;
      max-width: 1000px;
      margin: 0 auto;
      background: #fff;
      min-height: 100vh;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    aside {
      background: #111827;
      color: #f9fafb;
      padding: 40px 20px;
    }
    aside h1 {
      font-size: 28px;
      margin-bottom: 10px;
    }
    aside p, aside a {
      font-size: 14px;
      color: #d1d5db;
      text-decoration: none;
    }
    aside a:hover { color: #60a5fa; }
    aside section { margin-top: 30px; }
    aside h2 {
      font-size: 14px;
      text-transform: uppercase;
      border-bottom: 1px solid #374151;
      padding-bottom: 4px;
      margin-bottom: 10px;
      letter-spacing: 1px;
    }
    aside ul { list-style: none; padding: 0; margin: 0; }
    aside li {
      background: #1f2937;
      margin: 6px 0;
      padding: 6px 10px;
      border-radius: 6px;
      font-size: 13px;
    }

    main {
      padding: 40px;
    }
    main h2 {
      font-size: 18px;
      margin-top: 0;
      text-transform: uppercase;
      color: #2563eb;
      border-bottom: 2px solid #e5e7eb;
      padding-bottom: 4px;
      margin-bottom: 12px;
    }
    .edu, .exp {
      margin-bottom: 25px;
    }
    .edu strong, .exp strong {
      display: block;
      font-size: 16px;
      color: #111827;
    }
    .edu .sub, .exp .sub {
      color: #6b7280;
      font-size: 14px;
    }
    ul {
      margin: 6px 0 0 18px;
    }
    li {
      margin: 6px 0;
    }
    /* Print-friendly adjustments */
    @media print {
      body { background: #fff; }
      .container { box-shadow: none; }
      aside { background: #fff; color: #000; }
      aside h2, aside li { color: #000; background: none; }
    }
  </style>
</head>
<body>
  <div class="container">
    <aside>
      <h1>Dylan Weaver</h1>
      <p><a href="mailto:Dylanweaver425@gmail.com">Dylanweaver425@gmail.com</a></p>
      <p><a href="tel:+18622851141">(862) 285-1141</a></p>
      <p><a href="https://www.linkedin.com/in/developerdylan/" target="_blank">linkedin.com/in/developerdylan</a></p>

      <section>
        <h2>Skills</h2>
        <ul>
          <li>C++, Python</li>
          <li>Google Workspace</li>
          <li>Shopify, LightSpeed</li>
          <li>Automotive Troubleshooting</li>
          <li>Basic CAD</li>
          <li>Customer Service</li>
          <li>Problem Solving</li>
          <li>Critical Thinking</li>
        </ul>
      </section>
    </aside>

    <main>
      <section>
        <h2>Objective</h2>
        <p>Motivated Computer Science senior with a strong foundation in C++ and Python, seeking a software development internship. Passionate about advancing automotive technology and eager to contribute to innovative projects through strong problem solving and technical skills.</p>
      </section>

      <section>
        <h2>Education</h2>
        <div class="edu">
          <strong>William Paterson University, Wayne, NJ</strong>
          <div class="sub">B.S. Computer Science · Minor in Mathematics</div>
          <div class="sub">Graduation May 2026 · GPA: 3.49 · Dean’s List</div>
        </div>
      </section>

      <section>
        <h2>Experience</h2>
        <div class="exp">
          <strong>Shadow Hobbies, Woodland Park, NJ</strong>
          <div class="sub">Employee — Dec 2022 – Present</div>
          <ul>
            <li>Managed cash register and handled transactions to ensure a smooth customer experience.</li>
            <li>Assisted customers in selecting and repairing R/C vehicles by explaining features and locating parts.</li>
            <li>Diagnosed and repaired vehicle issues using manuals and technical tools.</li>
            <li>Maintained online inventory and organized incoming parts, processing hundreds weekly.</li>
            <li>Recognized for adaptability and problem-solving, contributing to project success and customer satisfaction.</li>
          </ul>
        </div>
      </section>
    </main>
  </div>
</body>
</html>
