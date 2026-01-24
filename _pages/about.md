---
permalink: /
title: "Coding Theory for Post-Quantum Security and Quantum Reliability"
excerpt: "Workshop at IEEE ISIT 2026 (Guangzhou)"
author_profile: false
header:
  overlay_image: "https://qsafe2026.github.io/images/headerbg.jpg"
  overlay_filter: 0.5
---

<style>
  /* 1. 引入 Google Fonts */
  @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap');

  /* 2. 全局设置 */
  body, h1, h4, h5, h6, p, li, td, th, div, a, span {
    font-family: 'Open Sans', 'Helvetica Neue', Arial, sans-serif !important;
  }
  body, p, li, td, th, div { 
    font-size: 18px !important;
    line-height: 1.6 !important;
  }

  /* 3. 标题样式 */
  h2 { 
    font-size: 28px !important; 
    color: #0056b3 !important;
    margin-top: 0 !important;
    margin-bottom: 20px !important;
  }
  h3 { 
    font-size: 22px !important; 
    color: #0056b3 !important;
  }

  /* === 4. 暴力拓宽页面 === */
  #main, .page, .page__content, .archive {
    width: 100% !important;
    max-width: 100% !important;
    margin: 0 !important;
    padding: 0 !important;
  }
  .sidebar { display: none !important; width: 0 !important; }
  .page__inner-wrap {
    width: 96% !important;      
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
    padding: 30px; 
    margin-bottom: 40px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    width: 100% !important; 
    box-sizing: border-box !important; 
  }

  /* 6. 表格样式 */
  .program-table, .dates-table {
    min-width: 500px; /* 保证表格不至于缩得太小 */
    border-collapse: collapse;
    font-size: 18px !important;
  }
  .program-table td, .dates-table td {
    padding: 12px 15px;
    border-bottom: 1px dashed #ddd;
    vertical-align: top;
  }
  .program-table tr:last-child td, .dates-table tr:last-child td { border-bottom: none; }
  
  .time-col { width: 160px; font-weight: bold; color: #555; }
  .label-col { width: 300px !important; white-space: nowrap !important; font-weight: bold; color: #333; }
  .date-col { color: #d90000; font-weight: bold; }

  /* 7. 头像和按钮 */
  .organizer-grid { display: flex; justify-content: space-around; flex-wrap: wrap; text-align: center; }
  .organizer-item { width: 30%; margin-bottom: 20px; }
  .organizer-item img { border-radius: 50%; width: 150px; height: 150px; object-fit: cover; border: 3px solid #f0f0f0; }
  .btn--info { margin-top: 10px; display: inline-block; background-color: #0056b3 !important; border-color: #0056b3 !important; }

  /* 8. 封面副标题 */
  .page__lead {
    font-size: 28px !important;
    font-weight: bold !important;
    text-align: center !important;
    line-height: 1.3 !important;
    margin-top: 10px !important;
  }

  /* === 新增：折叠面板样式 (Accordion) === */
  details {
    width: 100%;           /* 宽度占满容器 */
    margin-bottom: 15px;   /* 每个折叠框之间的距离 */
    border: 1px solid #e1e4e8; /* 浅灰色边框 */
    border-radius: 6px;    /* 圆角 */
    background-color: #fff;
    overflow: hidden;
  }

  summary {
    padding: 12px 20px;    /* 按钮内部的空间 */
    cursor: pointer;       /* 鼠标放上去变成小手 */
    font-weight: bold;
    font-size: 20px;       /* 字体大小模拟之前的 h3 */
    color: #0056b3;        /* 湛蓝色文字 */
    background-color: #f8fbff; /* 浅蓝色背景，呼应主题 */
    list-style: none;      /* 隐藏默认的三角箭头(部分浏览器) */
    outline: none;
    transition: background 0.2s;
  }

  /* 鼠标悬停时的效果 */
  summary:hover {
    background-color: #eaf5ff;
  }

  /* 专门针对 Webkit 浏览器隐藏默认箭头 */
  summary::-webkit-details-marker {
    display: none;
  }

  /* 自定义一个小箭头 (可选，为了更好看) */
  summary::after {
    content: '+'; 
    float: right; 
    font-weight: bold;
    color: #0056b3;
  }
  
  /* 打开状态下，箭头变成减号 */
  details[open] summary::after {
    content: '-';
  }
  
  details[open] summary {
    border-bottom: 1px solid #e1e4e8; /* 展开时，标题和内容之间加条线 */
  }

  /* 修正折叠框里的表格样式 */
  details .program-table {
    margin: 0;
    width: 100%;
  }
  details td {
    padding: 15px 20px; /* 内容稍微宽松点 */
  }
</style>

<div id="home"></div>
<div class="section-box" style="display: flex; flex-direction: column; align-items: center;">
  <h2 style="text-align: center;">Workshop at IEEE ISIT 2026 (Guangzhou)</h2>
  <div style="width: fit-content; max-width: 90%; text-align: justify;">
    This workshop focuses on coding theory as a unifying foundation for post-quantum cryptography (PQC) and quantum reliability, highlighting how classical codes, lattices, and decoding algorithms underpin both quantum-safe security and fault-tolerant quantum information processing. The workshop aims to bring together researchers from information theory, coding theory, post-quantum cryptography, and quantum error correction to explore shared mathematical structures and algorithmic principles.
  </div>
</div>

<div class="section-box" style="display: flex; flex-direction: column; align-items: center;">
  <h2>Topics</h2>
  <div style="width: fit-content; text-align: left;">
    <p>We invite submissions on (but not limited to) the following topics:</p>
    <ul>
      <li>Code-based cryptography (CBC) and decoding-based security assumptions</li>
      <li>Lattice-based cryptography (LBC), including LWE/LWR and related constructions</li>
      <li>Quantum error correction codes (QECC), including stabilizer and CSS constructions</li>
      <li>Information-theoretic security and coding-based approaches to quantum-safe communication</li>
      <li>Decoding algorithms for post-quantum security and quantum reliability</li>
    </ul>
  </div>
</div>

<div id="submission"></div>
<div class="section-box" style="display: flex; flex-direction: column; align-items: center;">
  <h2>Paper Submission and Dates</h2>
  
  <div style="width: fit-content; text-align: left;">
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
</div>

<div id="speakers"></div>
<div class="section-box" style="display: flex; flex-direction: column; align-items: center;">
  <h2>Keynote Speakers</h2>

  <div style="width: fit-content; text-align: left;">
    
    <h3 style="margin-bottom: 2px;">Prof. Biao Chen (IEEE Fellow)</h3>
    <p style="margin-top: 0;"><strong>Syracuse University, USA</strong></p>

    <h3 style="margin-bottom: 2px; margin-top: 20px;">Prof. Divesh Aggarwal</h3>
    <p style="margin-top: 0;"><strong>National University of Singapore</strong></p>

    <h3 style="margin-bottom: 2px; margin-top: 20px;">Prof. Chunming Tang</h3>
    <p style="margin-top: 0;"><strong>Southwest Jiaotong University, China</strong></p>
    
  </div>
</div>

<div id="program"></div>
<div class="section-box" style="display: flex; flex-direction: column; align-items: center;">
  <h2>Tentative Program</h2>

  <div style="width: 100%; max-width: 900px; text-align: left;">
    
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
      <img src="/images/ling.jpg" alt="Ling Liu">
      <h3>Ling Liu</h3>
      <p>Xidian University, China<br>Email: liuling@xidian.edu.cn</p>
      <a href="https://faculty.xidian.edu.cn/LIULING/en/index.htm" target="_blank" class="btn btn--info">Personal website</a>
    </div>

    <div class="organizer-item">
      <img src="/images/shanxiang.jpg" alt="Shanxiang Lyu">
      <h3>Shanxiang Lyu</h3>
      <p>Jinan University, China<br>Email: lsx07@jnu.edu.cn</p>
      <a href="https://sites.google.com/view/shanx" target="_blank" class="btn btn--info">Personal website</a>
    </div>
  </div>
</div>
