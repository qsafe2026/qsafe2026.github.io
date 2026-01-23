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
  /* 标题颜色 */
  h2, h3 { color: #0056b3 !important; }
  
  /* 强制内容区域变宽，占满屏幕的 90% */
  .page__inner-wrap { max-width: 100% !important; }
  .page__content { max-width: 100% !important; }
  
  /* 调整板块之间的间距，让长页面呼吸感更好 */
  section { margin-bottom: 80px; padding-top: 20px; }
  
  /* 分割线样式 */
  hr { margin: 60px 0; border: 0; border-top: 1px solid #eee; }
  
  /* 组织者头像样式复用 */
  .organizer-grid { display: flex; justify-content: space-around; flex-wrap: wrap; text-align: center; }
  .organizer-item { width: 30%; margin-bottom: 20px; }
  .organizer-item img { border-radius: 50%; width: 150px; height: 150px; object-fit: cover; }
  .btn--info { margin-top: 10px; display: inline-block; }


  /* === 全局字体放大设置 === */
  
  /* 1. 增大正文、列表、表格文字 */
  body, p, li, td, th, div { 
    font-size: 18px !important;  /* 默认一般是 16px，改大到 18px */
    line-height: 1.7 !important; /* 增加行间距，防止字变大后挤在一起 */
  }

  /* 2. 增大二级标题 (如 Topics, Organizers) */
  h2 { 
    font-size: 28px !important; 
    margin-top: 40px !important; /* 字体大了，上方间距也要适当拉大 */
  }

  /* 3. 增大三级标题 (如 Session I, 老师名字) */
  h3 { 
    font-size: 22px !important; 
  }
  
  /* 4. 增大侧边栏/页脚的小字 (可选) */
  .page__footer-copyright {
    font-size: 16px !important;
  }

  
  /* === 新增：日程表样式 === */
  .program-table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 30px;
    font-size: 18px !important; /* 保持和你之前设置的大字体一致 */
  }
  .program-table td {
    padding: 12px 10px;
    border-bottom: 1px solid #eee; /*每一行下面的浅灰分割线*/
    vertical-align: top;
  }
  .program-table .time-col {
    width: 160px; /* 强制固定时间列的宽度 */
    font-weight: bold;
    color: #444;
  }
  .program-table .event-col {
    /* 事件列自动占据剩余空间 */
  }


  /* === 新增：重要日期表格样式 === */
  .dates-table {
    width: 100%;
    max-width: 800px; /* 限制一下最大宽度，防止太宽了不好看 */
    border-collapse: collapse;
    margin-bottom: 20px;
    font-size: 18px !important;
  }
  .dates-table td {
    padding: 8px 10px; /* 让行与行之间稍微紧凑一点，比日程表紧凑 */
    vertical-align: top;
    border: none; /* 去掉边框，看起来更像列表而不是表格 */
  }
  .dates-table .label-col {
    font-weight: bold; /* 左边的标题加粗 */
    width: 260px;      /* 【关键】固定左边列的宽度，确保右边对齐 */
    color: #333;
  }
  .dates-table .date-col {
    color: red;        /* 右边的日期统一设为红色 */
    font-weight: bold; /* 如果你想让日期也加粗，就留着这行 */
  }

  
</style>

<div id="home"></div>
<h2 style="text-align: center;">Workshop at IEEE ISIT 2026 (Guangzhou)</h2>

This workshop focuses on coding theory as a unifying foundation for post-quantum cryptography (PQC) and quantum reliability, highlighting how classical codes, lattices, and decoding algorithms underpin both quantum-safe security and fault-tolerant quantum information processing. The workshop aims to bring together researchers from information theory, coding theory, post-quantum cryptography, and quantum error correction to explore shared mathematical structures and algorithmic principles.

## Topics
We invite submissions on (but not limited to) the following topics:
* Code-based cryptography (CBC) and decoding-based security assumptions
* Lattice-based cryptography (LBC), including LWE/LWR and related constructions
* Quantum error correction codes (QECC), including stabilizer and CSS constructions
* Information-theoretic security and coding-based approaches to quantum-safe communication
* Decoding algorithms for post-quantum security and quantum reliability

<hr>

<div id="submission"></div>
<h2>Paper Submission and Dates</h2>

Submission will be handled via EDAS. The paper format follows the main ISIT conference guidelines.

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

<hr>

<div id="speakers"></div>
<h2>Keynote Speakers</h2>

<h3>Prof. Biao Chen (IEEE Fellow)</h3>
**Syracuse University, USA**

<h3>Prof. Divesh Aggarwal</h3>
**National University of Singapore**

<h3>Prof. Chunming Tang</h3>
**Southwest Jiaotong University, China**

<hr>

<div id="program"></div>
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

<hr>

<div id="organizers"></div>
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
