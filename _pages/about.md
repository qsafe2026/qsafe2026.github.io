---
permalink: /
title: "Coding Theory for Post-Quantum Security and Quantum Reliability"
excerpt: "Workshop at IEEE ISIT 2026 (Guangzhou)"
author_profile: false
header:
  overlay_image: "https://qsafe2026.github.io/images/header-bg.jpg"
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

  /* === 4. 暴力拓宽页面容器 (保持背景宽敞) === */
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

  /* 5. 【关键修改】卡片盒子样式 (调整为 2/3 宽度) */
  .section-box {
    background-color: #f8fbff;
    border: 1px solid #e1e4e8;
    border-left: 6px solid #0056b3;
    border-radius: 8px;
    padding: 30px; 
    margin-bottom: 40px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    
    /* 修改开始：宽度控制 */
    width: 70% !important;       /* 占页面约 2/3 */
    min-width: 800px !important; /* 保证最小宽度，防止在小屏幕太挤 */
    margin-left: auto !important;  /* 自动居中 */
    margin-right: auto !important; /* 自动居中 */
    /* 修改结束 */
    
    box-sizing: border-box !important; 
  }

  /* 6. 表格样式 */
  .program-table, .dates-table {
    min-width: 500px;
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
  
  /* 9. 折叠面板样式 */
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
    font-size: 20px;
    color: #0056b3;
    background-color: #f8fbff;
    list-style: none;
    outline: none;
    transition: background 0.2s;
    text-align: left; /* 确保标题文字左对齐 */
  }
  summary:hover { background-color: #eaf5ff; }
  summary::-webkit-details-marker { display: none; }
  summary::after { content: '+'; float: right; font-weight: bold; color: #0056b3; }
  details[open] summary::after { content: '-'; }
  details[open] summary { border-bottom: 1px solid #e1e4e8; }
  details .program-table { margin: 0; width: 100%; }
  details td { padding: 15px 20px; }

  /* === 新增：隐藏顶部的主题切换/搜索按钮 === */
  .greedy-nav .theme-toggle, 
  .greedy-nav button, 
  #theme-toggle,
  button[title="Toggle theme"] {
    display: none !important; /* 强制隐藏 */
  }
  
  /* 注意：如果你发现手机版菜单按钮也不见了，请把 .greedy-nav button 这一行删掉 */

  /* === 新增：暴力隐藏底部的 Sitemap 和 Follow 链接 === */
  .page__footer-follow,
  .social-icons {
    display: none !important;
  }
  
  /* 确保只保留我们自定义的 Copyright 居中显示 */
  .page__footer-copyright {
    display: block !important;
    margin: 0 auto !important;
    text-align: center !important;
  }


  /* === 新增：暴力强制由暗转明（覆盖系统的深色模式） === */
  @media (prefers-color-scheme: dark) {
    /* 1. 强制背景变白，文字变黑 */
    body, .page, .page__content {
      background-color: #fff !important;
      color: #333 !important;
    }

    /* 2. 强制标题和链接的颜色 */
    h1, h2, h3, h4, h5, h6 {
      color: #0056b3 !important; /* 你的主题蓝色 */
    }
    a {
      color: #0056b3 !important;
    }
    
    /* 3. 修复我们自定义的方框颜色 */
    /* 在黑夜模式下，方框里的文字如果不强制设为黑色，可能会变成白色导致看不见 */
    .section-box {
      background-color: #f8fbff !important; /* 保持淡蓝色背景 */
      color: #333 !important; /* 强制文字黑色 */
      border: 1px solid #e1e4e8 !important;
    }

    /* 4. 修复折叠面板 */
    details, summary {
      background-color: #fff !important;
      color: #333 !important;
    }
    summary {
      background-color: #f8fbff !important;
    }

    /* 5. 修复顶部的导航栏（如果有变黑的话） */
    .masthead {
      background-color: #fff !important;
      border-bottom: 1px solid #e1e4e8 !important;
    }
  }

  /* === 新增：专门修复手机端封面显示 (终极修正版) === */
  @media screen and (max-width: 768px) {
    
    /* 1. 针对 wrapper 的修复：确保容器本身就是全宽的 */
    .initial-content, 
    .page__hero--overlay,
    .page__hero {
      width: 100% !important;
      max-width: 100% !important;
      margin: 0 !important;
      padding-left: 0 !important;
      padding-right: 0 !important;
    }

    /* 2. 针对背景图的修复 */
    .page__hero--overlay {
      /* 【核心关键点】手机上必须用 scroll，绝对不能用 fixed！*/
      /* fixed 会导致图片在手机上定位错乱，看起来像只有一半 */
      background-attachment: scroll !important; 
      
      /* 强制居中剪裁 */
      background-position: center center !important;
      background-size: cover !important;
      
      /* 设置合理的高度，太高了手机滑不动 */
      min-height: 60vh !important; 
    }
    
    /* 3. 修复标题文字大小和边距 */
    .page__hero--overlay .page__title {
      font-size: 2.0em !important; /* 稍微改小一点，防止换行太难看 */
      line-height: 1.2 !important;
      padding: 0 15px !important;    /* 左右留点缝隙 */
      width: 100% !important;        /* 确保文字容器也是全宽 */
      box-sizing: border-box !important;
    }
    
    /* 4. 修复副标题 */
    .page__lead {
      font-size: 1.1em !important;
      padding: 0 15px !important;
      width: 100% !important;
      box-sizing: border-box !important;
    }
  }
  
  /* === 新增：修复封面大标题颜色 === */
  /* 特指：只修改封面图(overlay)上面的标题 */
  .page__hero--overlay .page__title {
    color: #fff !important; /* 强制白色 */
    
    /* 建议加一点文字阴影，防止背景图太亮时看不清文字 */
    text-shadow: 1px 1px 10px rgba(0,0,0,0.8) !important;
  }

  /* 如果封面上的副标题（Workshop...）也变蓝了，把下面这几行也加上 */
  .page__hero--overlay .page__lead {
    color: #fff !important; 
    text-shadow: 1px 1px 8px rgba(0,0,0,0.8) !important;
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
  
  <h2 style="text-align: center; margin-bottom: 5px !important;">Keynote Speakers</h2>

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
