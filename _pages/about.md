---
permalink: /
title: "Coding Theory for Post-Quantum Security and Quantum Reliability"
excerpt: "Workshop at IEEE ISIT 2026 (Guangzhou)"
author_profile: false
header:
  overlay_image: "https://buzzbbb.github.io/images/headerbg.jpg"
  overlay_filter: 0.5
---

<style>
  /* 1. 引入 Google Fonts (Open Sans) */
  @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap');

  /* 2. 全局字体设置 */
  body, h1, h4, h5, h6, p, li, td, th, div, a, span {
    font-family: 'Open Sans', 'Helvetica Neue', Arial, sans-serif !important;
  }

  /* 3. 字体大小和颜色设置 */
  body, p, li, td, th, div { 
    font-size: 18px !important;
    line-height: 1.7 !important;
  }
  h2 { 
    font-size: 28px !important; 
    color: #0056b3 !important; /* 湛蓝色标题 */
    margin-top: 0 !important; /* 去掉标题顶部的空隙，因为现在在盒子里了 */
    margin-bottom: 20px !important;
  }
  h3 { 
    font-size: 22px !important; 
    color: #0056b3 !important;
  }

  /* 4. 强制内容铺宽 */
  .page__inner-wrap { max-width: 95% !important; }
  .page__content { max-width: 100% !important; }

  /* === 5. 【核心修改】卡片盒子样式 === */
  .section-box {
    background-color: #f8fbff;    /* 极淡的蓝色背景 */
    border: 1px solid #e1e4e8;    /* 浅灰色边框 */
    border-left: 6px solid #0056b3; /* 左侧加粗的湛蓝色线条，呼应主题 */
    border-radius: 8px;           /* 圆角 */
    padding: 30px;                /* 内部留白 */
    margin-bottom: 50px;          /* 盒子之间的间距 */
    box-shadow: 0 4px 12px rgba(0,0,0,0.05); /* 轻微的投影，增加立体感 */
  }

  /* 6. 表格样式优化 */
  .program-table, .dates-table {
    width: 100%;
    border-collapse: collapse;
    font-size: 18px !important;
  }
  .program-table td, .dates-table td {
    padding: 12px 10px;
    border-bottom: 1px dashed #ddd; /* 虚线分割，更精致 */
    vertical-align: top;
  }
  .program-table tr:last-child td, .dates-table tr:last-child td {
    border-bottom: none;
  }
  .time-col { width: 160px; font-weight: bold; color: #555; }
  .label-col { width: 260px; font-weight: bold; color: #333; }
  .date-col { color: #d90000; font-weight: bold; } /* 日期深红色 */

  /* 7. 组织者头像样式 */
  .organizer-grid { display: flex; justify-content: space-around; flex-wrap: wrap; text-align: center; }
  .organizer-item { width: 30%; margin-bottom: 20px; }
  .organizer-item img { border-radius: 50%; width: 150px; height: 150px; object-fit: cover; border: 3px solid #f0f0f0; }
  .btn--info { margin-top: 10px; display: inline-block; background-color: #0056b3 !important; border-color: #0056b3 !important; }

  /* 8. 封面副标题样式 */
  .page__lead {
    font-size: 28px !important;
    font-weight: bold !important;
    text-align: center !important;
    line-height: 1.3 !important;
    margin-top: 10px !important;
  }
</style>

<div id="home"></div>
<h2 style="text-align: center; font-size: 32px !important; margin-bottom: 30px !important;">Workshop at IEEE ISIT 2026 (Guangzhou)</h2>

<div style="font-size: 19px; margin-bottom: 40px; text-align: justify;">
This workshop focuses on coding theory as a unifying foundation for post-quantum cryptography (PQC) and quantum reliability, highlighting how classical codes, lattices, and decoding algorithms underpin both quantum-safe security and fault-tolerant quantum information processing. The workshop aims to bring together researchers from information theory, coding theory, post-quantum cryptography, and quantum error correction to explore shared mathematical structures and algorithmic principles.
</div>

<div class="section-box">
  ## Topics
  We invite submissions on (but not limited to) the following topics:
  * Code-based cryptography (CBC) and decoding-based security assumptions
  * Lattice-based cryptography (LBC), including LWE/LWR and related constructions
  * Quantum error correction codes (QECC), including stabilizer and CSS constructions
  * Information-theoretic security and coding-based approaches to quantum-safe communication
  * Decoding algorithms for post-quantum security and quantum reliability
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

  <h3>Prof. Biao Chen (IEEE Fellow)</h3>
  **Syracuse University, USA**

  <br>

  <h3>Prof. Divesh Aggarwal</h3>
  **National University of Singapore**

  <br>

  <h3>Prof. Chunming Tang</h3>
  **Southwest Jiaotong University, China**
</div>

<div id="program"></div>
<div class="section-box">
  <h2>Tentative Program</h2>

  <h3>Session I: Code-Based Cryptography (CBC)</h3>
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

  <h3>Session II: Lattice-Based Cryptography (LBC)</h3>
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

  <h3>Session III: Quantum Error Correction Codes (QECC)</h3>
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

  <h3>Interactive Session</h3>
  <table class="program-table">
    <tr>
      <td class="time-col">15:30 - 16:30</td>
      <td class="event-col">Panel Discussion</td>
    </tr>
  </table>
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
