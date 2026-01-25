---
permalink: /
title: "Coding Theory for Post-Quantum Security and Quantum Reliability"
excerpt: "Workshop at IEEE ISIT 2026 (Guangzhou)<br><span class='workshop-date'>July 03 (Friday), 2026</span>"
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

  /* 7. Organizers 样式 */
  .organizer-grid { 
    display: flex; 
    justify-content: space-around; 
    flex-wrap: wrap; 
    text-align: center !important; 
  }
  .organizer-item { width: 30%; margin-bottom: 20px; }
  .organizer-item img { border-radius: 50%; width: 150px; height: 150px; object-fit: cover; border: 3px solid #f0f0f0; }
  .organizer-item h3 { text-align: center !important; margin-bottom: 5px !important; }
  
  .organizer-item p { 
    text-align: center !important; 
    font-size: 0.85em !important; 
    line-height: 1.4 !important;    
    color: #444;
  }
  
  .btn--info { margin-top: 10px; display: inline-block; background-color: #0056b3 !important; border-color: #0056b3 !important; }

  /* 8. 【关键修改】封面标题样式 */
  
  /* 公共设置：字体、加粗、颜色、阴影、居中 */
  .page__hero--overlay .page__title,
  .page__hero--overlay .page__lead {
    font-family: 'Open Sans', sans-serif !important;
    font-weight: 800 !important; 
    color: #fff !important;
    text-shadow: 1px 1px 10px rgba(0,0,0,0.8) !important;
    text-align: center !important;
    width: 100% !important; 
    max-width: 100% !important; 
    padding: 0 20px !important;
    
    /* 【关键修改】统一字号 */
    font-size: 1.7em !important; 
    line-height: 1.3 !important;
  }

  /* 8.1 大标题：不斜 */
  .page__hero--overlay .page__title {
    margin-bottom: 10px !important;
    font-style: normal !important; 
  }

  /* 8.2 小标题：要斜 */
  .page__hero--overlay .page__lead {
    margin-top: 5px !important; 
    font-style: italic !important; 
  }

  /* 9. 日期样式 (白色方框) */
  .workshop-date {
    font-family: 'Open Sans', sans-serif !important;
    font-size: 0.6em !important; 
    
    font-style: normal !important;
    font-weight: 600 !important; 
    
    letter-spacing: 1px !important;
    color: #fff;
    display: inline-block;
    
    border: 2px solid #fff; 
    padding: 8px 15px;     
    border-radius: 4px;    
    margin-top: 15px;      
    background-color: rgba(0,0,0,0.1); 
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
    /* 手机端也保持两者大小一致 (稍微小一点适配屏幕) */
    .page__hero--overlay .page__title,
    .page__hero--overlay .page__lead {
      font-size: 1.3em !important; 
    }
    .workshop-date {
        font-size: 0.5em !important;
        padding: 5px 10px !important; 
    }
    
    body, html, .page, .page__inner-wrap, .page__content {
      width: 100% !important;
      max-width: 100% !
