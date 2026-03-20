---
permalink: /
title: "ISIT 2026 Workshop on Coding Theory for "
excerpt: "Post-Quantum Security and Quantum Reliability<br><span class='workshop-date'>July 03 (Friday), 2026</span>"
author_profile: false
header:
  overlay_image: "https://qsafe2026.github.io/images/header-bg.jpg"
  overlay_filter: 0.3
---

<style>
  /* 1. 引入 Google Fonts */
  @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700;800&display=swap');

  /* 2. 全局设置 */
  body, h1, h4, h5, h6, p, li, td, th, div, a, span {
    font-family: 'Open Sans', 'Helvetica Neue', Arial, sans-serif !important;
  }
  body, p, li, td, th, div { 
    font-size: 18px !important;
    line-height: 1.6 !important;
  }

  /* 3. 正文标题样式 (左对齐) */
  h2 { 
    font-size: 26px !important; 
    color: #0056b3 !important;
    margin-top: 0 !important;
    margin-bottom: 15px !important;
    text-align: left !important; 
    border-bottom: 1px solid #e1e4e8; 
    padding-bottom: 10px;
  }
  h3 { 
    font-size: 20px !important; 
    color: #0056b3 !important;
    text-align: left !important;
    margin-bottom: 5px !important;
  }

  /* 4. 页面容器设置 */
  #main, .page, .page__content, .archive {
    width: 100% !important;
    max-width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }
  .sidebar { display: none !important; width: 0 !important; }
  .page__inner-wrap {
    width: 98% !important;      
    max-width: 100% !important; 
    margin: 0 auto !important;
    padding: 0 !important;
    float: none !important;    
  }

  /* 5. 卡片盒子样式 */
  .section-box {
    background-color: #f8fbff;
    border: 1px solid #e1e4e8;
    border-left: 6px solid #0056b3;
    border-radius: 8px;
    padding: 40px 12% !important; 
    margin-bottom: 40px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    
    width: 70% !important;       
    min-width: 800px !important; 
    margin-left: auto !important;  
    margin-right: auto !important; 
    
    text-align: left !important; 
    box-sizing: border-box !important; 
  }

  /* 6. 表格样式 */
  .program-table, .dates-table {
    min-width: 500px;
    border-collapse: collapse;
    font-size: 18px !important;
    width: 100%; 
  }
  .program-table td, .dates-table td {
    padding: 12px 15px;
    border-bottom: 1px dashed #ddd;
    vertical-align: top;
    text-align: left; 
  }
  .program-table tr:last-child td, .dates-table tr:last-child td { border-bottom: none; }
  
  .time-col { width: 160px; font-weight: bold; color: #555; }
  .label-col { width: 280px !important; white-space: nowrap !important; font-weight: bold; color: #333; }
  .date-col { color: #d90000; font-weight: bold; }

  /* 7. Organizers 样式 (照片长方形) */
  .organizer-grid { 
    display: flex; 
    justify-content: space-around; 
    flex-wrap: wrap; 
    text-align: center !important; 
  }
  .organizer-item { width: 30%; margin-bottom: 20px; }
  
  /* 照片改为长方形 */
  .organizer-item img { 
    border-radius: 6px !important; 
    width: 150px !important; 
    height: 200px !important; 
    object-fit: cover !important; 
    border: 3px solid #f0f0f0; 
  }
  
  /* 【关键修改】Organizers 人名黑色加粗 */
  .organizer-item h3 { 
      text-align: center !important; 
      margin-bottom: 5px !important;
      color: #000 !important; /* 黑色 */
      font-weight: bold !important; /* 加粗 */
  }
  
  .organizer-item p { 
    text-align: center !important; 
    font-size: 0.85em !important; 
    line-height: 1.4 !important;    
    color: #444;
  }
  
  .btn--info { margin-top: 10px; display: inline-block; background-color: #0056b3 !important; border-color: #0056b3 !important; }

  /* 8. 封面标题样式 */
  .page__hero--overlay .page__title,
  .page__hero--overlay .page__lead {
    font-family: 'Open Sans', sans-serif !important;
    font-weight: 800 !important; 
    font-style: normal !important;
    color: #fff !important;
    text-shadow: 1px 1px 10px rgba(0,0,0,0.8) !important;
    font-size: 1.7em !important; 
    line-height: 1.3 !important;
    width: 100% !important; 
    max-width: 100% !important; 
    padding: 0 20px !important;
    text-align: center !important;
    margin-bottom: 10px !important;
  }
  .page__hero--overlay .page__lead {
    margin-top: 5px !important; 
  }

  /* 9. 【关键修改】日期样式 (去掉方框，保留微软雅黑加粗) */
  .workshop-date {
    font-family: 'Microsoft YaHei', 'SimHei', sans-serif !important;
    font-size: 0.55em !important; 
    font-style: normal !important;
    font-weight: bold !important; 
    letter-spacing: 0.5px !important;
    color: rgba(255,255,255,0.95);
    display: inline-block;
    margin-top: 8px;
    /* 去掉了原来的 border, padding, background-color */
    text-transform: uppercase;
  }
  
  /* 10. 折叠面板样式 */
  details {
    width: 100%;
    margin-bottom: 15px;
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    background-color: #fff;
    overflow: hidden;
  }
  summary {
    padding: 12px 20px;
    cursor: pointer;
    font-weight: bold;
    font-size: 18px; 
    color: #0056b3;
    background-color: #f8fbff;
    list-style: none;
    outline: none;
    transition: background 0.2s;
    text-align: left; 
  }
  summary:hover { background-color: #eaf5ff; }
  summary::-webkit-details-marker { display: none; }
  summary::after { content: '+'; float: right; font-weight: bold; color: #0056b3; }
  details[open] summary::after { content: '-'; }
  details[open] summary { border-bottom: 1px solid #e1e4e8; }
  details .program-table { margin: 0; width: 100%; }
  details td { padding: 15px 20px; }

  /* === 手机端适配 === */
  @media screen and (max-width: 768px) {
    .section-box {
      width: 92% !important;     
      min-width: 0 !important;   
      margin: 0 auto 30px auto !important; 
      padding: 20px 15px !important; 
    }
    .section-box table, .program-table, .dates-table {
      display: block !important;    
      width: 100% !important;       
      min-width: 0 !important;      
      overflow-x: auto !important;  
      -webkit-overflow-scrolling: touch; 
    }
    
    .page__hero--overlay {
      width: 100vw !important; 
      max-width: 100vw !important;
      background-size: cover !important; 
      background-position: center center !important;
      background-repeat: no-repeat !important;
      background-attachment: scroll !important; 
      min-height: 40vh !important; 
      margin: 0 !important;
      left: 0 !important;
      right: 0 !important;
      padding-left: 15px !important;
      padding-right: 15px !important;
    }
    .page__hero--overlay .page__title,
    .page__hero--overlay .page__lead {
      font-size: 1.3em !important; 
    }
    .workshop-date {
        font-size: 0.5em !important;
    }
    
    body, html, .page, .page__inner-wrap, .page__content {
      width: 100% !important;
      max-width: 100% !important;
      overflow-x: hidden !important; 
      margin: 0 !important;
      padding: 0 !important;
    }
  }

  /* 隐藏多余元素 */
  .greedy-nav .theme-toggle, .greedy-nav button, #theme-toggle, button[title="Toggle theme"] { display: none !important; }
  .page__footer-follow, .social-icons { display: none !important; }
  .page__footer-copyright { display: block !important; margin: 0 auto !important; text-align: center !important; }
  
  /* 强制白天模式 */
  @media (prefers-color-scheme: dark) {
    body, .page, .page__content { background-color: #fff !important; color: #333 !important; }
    h1, h2, h3, h4, h5, h6 { color: #0056b3 !important; }
    a { color: #0056b3 !important; }
    .section-box { background-color: #f8fbff !important; color: #333 !important; border: 1px solid #e1e4e8 !important; }
    details, summary { background-color: #fff !important; color: #333 !important; }
    summary { background-color: #f8fbff !important; }
    .masthead { background-color: #fff !important; border-bottom: 1px solid #e1e4e8 !important; }
  }
</style>

<div id="home"></div>

<div class="section-box">
  <h2>Scope and Topics</h2>
  <div style="text-align: justify;">
    This workshop focuses on coding theory as a unifying foundation for post-quantum cryptography (PQC) and quantum reliability, highlighting how classical codes, lattices, and decoding algorithms underpin both quantum-safe security and fault-tolerant quantum information processing. The workshop aims to bring together researchers from information theory, coding theory, post-quantum cryptography, and quantum error correction to explore shared mathematical structures and algorithmic principles.
  </div>
  <p>We invite submissions on (but not limited to) the following topics:</p>
  <ul>
    <li>Code-based cryptography (CBC) and decoding-based security assumptions</li>
    <li>Lattice-based cryptography (LBC), including LWE/LWR and related constructions</li>
    <li>Quantum error correction codes (QECC), including stabilizer and CSS constructions</li>
    <li>Information-theoretic security and coding-based approaches to quantum-safe communication</li>
    <li>Decoding algorithms for post-quantum security and quantum reliability</li>
  </ul>
</div>

<div id="submission"></div>
<div class="section-box">
  <h2>Paper Submission and Dates</h2>
  <p>Submission will be handled via EDAS. The paper format follows the main ISIT conference guidelines.</p>
  
  <h3>Important Dates</h3>
  <table class="dates-table">
    <tr>
      <td class="label-col">Paper Submission:</td>
      <td class="date-col">April 7, 2026 (firm)</td>
    </tr>
    <tr>
      <td class="label-col">Notification of Acceptance:</td>
      <td class="date-col">April 21, 2026</td>
    </tr>
    <tr>
      <td class="label-col">Final Manuscript:</td>
      <td class="date-col">April 28, 2026</td>
    </tr>
  </table>
</div>

<div id="speakers"></div>
<div class="section-box">
  <h2>Keynote Speakers</h2>

  <h3 style="margin-bottom: 2px; color: #000 !important; font-weight: bold;">Prof. Biao Chen (IEEE Fellow)</h3>
  <p style="margin-top: 0;">Syracuse University, USA</p>

  <h3 style="margin-bottom: 2px; margin-top: 25px; color: #000 !important; font-weight: bold;">Prof. Divesh Aggarwal</h3>
  <p style="margin-top: 0;">National University of Singapore</p>

  <h3 style="margin-bottom: 2px; margin-top: 25px; color: #000 !important; font-weight: bold;">Prof. Chunming Tang</h3>
  <p style="margin-top: 0;">Southwest Jiaotong University, China</p>
</div>

<div id="program"></div>
<div class="section-box">
  <h2>Tentative Program</h2>

  <details open>
    <summary>Session I: Code-Based Cryptography (CBC)</summary>
    <table class="program-table">
      <tr>
        <td class="time-col">09:00 - 09:30</td>
        <td class="event-col">Invited Talk (TBA)</td>
      </tr>
      <tr>
        <td class="time-col">09:30 - 10:00</td>
        <td class="event-col">Selected Contributors</td>
      </tr>
      <tr>
        <td class="time-col">10:00 - 10:30</td>
        <td class="event-col">Selected Contributors</td>
      </tr>
      <tr>
        <td class="time-col">10:30 - 11:00</td>
        <td class="event-col">Morning Tea Break</td>
      </tr>
    </table>
  </details>

  <details>
    <summary>Session II: Lattice-Based Cryptography (LBC)</summary>
    <table class="program-table">
      <tr>
        <td class="time-col">11:00 - 11:30</td>
        <td class="event-col">Invited Talk (TBA)</td>
      </tr>
      <tr>
        <td class="time-col">11:30 - 12:00</td>
        <td class="event-col">Selected Contributors</td>
      </tr>
      <tr>
        <td class="time-col">12:00 - 12:30</td>
        <td class="event-col">Selected Contributors</td>
      </tr>
      <tr>
        <td class="time-col">12:30 - 13:30</td>
        <td class="event-col">Lunch Break</td>
      </tr>
    </table>
  </details>

  <details>
    <summary>Session III: Quantum Error Correction Codes (QECC)</summary>
    <table class="program-table">
      <tr>
        <td class="time-col">13:30 - 14:00</td>
        <td class="event-col">Invited Talk (TBA)</td>
      </tr>
      <tr>
        <td class="time-col">14:00 - 14:30</td>
        <td class="event-col">Selected Contributors</td>
      </tr>
      <tr>
        <td class="time-col">14:30 - 15:00</td>
        <td class="event-col">Selected Contributors</td>
      </tr>
      <tr>
        <td class="time-col">15:00 - 15:30</td>
        <td class="event-col">Afternoon Tea Break</td>
      </tr>
    </table>
  </details>

  <details>
    <summary>Interactive Session</summary>
    <table class="program-table">
      <tr>
        <td class="time-col">15:30 - 16:30</td>
        <td class="event-col">Panel Discussion</td>
      </tr>
    </table>
  </details>
</div>

<div id="organizers"></div>
<div class="section-box">
  <h2>Organizers</h2>

  <div class="organizer-grid">
    <div class="organizer-item">
      <img src="/images/venkata.jpg" alt="Venkata Gandikota">
      <h3>Venkata Gandikota</h3>
      <p>Syracuse University, USA<br>Email: vsgandik@syr.edu</p>
      <a href="https://sites.google.com/view/gvenkata/home" target="_blank" class="btn btn--info">Personal website</a>
    </div>

    <div class="organizer-item">
      <img src="/images/shanxiang.jpg" alt="Shanxiang Lyu">
      <h3>Shanxiang Lyu</h3>
      <p>Jinan University, China<br>Email: lsx07@jnu.edu.cn</p>
      <a href="https://sites.google.com/view/shanx" target="_blank" class="btn btn--info">Personal website</a>
    </div>

    <div class="organizer-item">
      <img src="/images/ling.jpg" alt="Ling Liu">
      <h3>Ling Liu</h3>
      <p>Xidian University, China<br>Email: liuling@xidian.edu.cn</p>
      <a href="https://faculty.xidian.edu.cn/LIULING/en/index.htm" target="_blank" class="btn btn--info">Personal website</a>
    </div>
  </div>
</div>
