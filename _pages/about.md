---
permalink: /
title: "TA Website for Statistics with Recitation (26F)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 透過 CSS 讓框框與文字完美適應深淺色模式 */
  .custom-info-box {
    border: 1px solid #e2e8f0;
    /* 淺色模式下預設使用全白背景 */
    background-color: #ffffff;
    padding: 20px; 
    border-radius: 10px; 
    margin-top: 15px;
  }
  
  /* 讓框框內的內文顏色跟隨系統主題切換 */
  .custom-info-box p {
    color: inherit !important;
  }
  
  .custom-sub-text {
    font-size: 0.95em;
    padding-left: 15px;
    opacity: 0.8; /* 使用透明度代替寫死的灰色 */
  }

  /* 首頁最新公告的特定結構樣式 */
  .home-announcement-header {
    border-bottom: 1px dashed #e2e8f0;
    padding-bottom: 12px;
    margin: 0 0 15px 0;
  }

  .home-announcement-footer {
    border-top: 1px dashed #e2e8f0; 
    padding-top: 15px; 
    margin-top: 15px; 
    text-align: right;
  }

  /* 讓 code 區塊也能完美適應深淺色 */
  .custom-info-box code {
    background-color: #f1f5f9 !important;
    color: #475569 !important;
    padding: 3px 8px;
    border-radius: 5px;
    font-family: monospace;
    font-size: 0.95em;
  }

  /* 當偵測到系統預設深色模式 */
  @media (prefers-color-scheme: dark) {
    .custom-info-box {
      background-color: #252a34; /* 深色模式下的溫潤深灰底 */
      border-color: #3f444e;     /* 深色模式下的微弱邊框 */
    }
    .home-announcement-header, .home-announcement-footer {
      border-bottom-color: #3f444e; /* 深色模式下的虛線顏色 */
      border-top-color: #3f444e;
    }
    .custom-info-box code {
      background-color: #1e222b !important; /* 深色模式下的 code 黯淡背景 */
      color: #cbd5e1 !important;           /* 深色模式下的 code 明亮文字 */
    }
  }
  
  /* 針對 Minimal Mistakes 模板常見的強制切換深色樣式覆寫 */
  html[data-theme="dark"] .custom-info-box,
  .theme-dark .custom-info-box {
    background-color: #252a34;
    border-color: #3f444e;
  }
  html[data-theme="dark"] .home-announcement-header,
  html[data-theme="dark"] .home-announcement-footer,
  .theme-dark .home-announcement-header,
  .theme-dark .home-announcement-footer {
    border-bottom-color: #3f444e;
    border-top-color: #3f444e;
  }
  html[data-theme="dark"] .custom-info-box code,
  .theme-dark .custom-info-box code {
    background-color: #1e222b !important;
    color: #cbd5e1 !important;
  }
</style>

## Hi! This is the TA Website for Statistics with Recitation!
All TA Session Materials will be posted here, including slides, R codes, HW, and Quizs.

---

## TA Information

<div class="custom-info-box">
  <p style="margin: 0 0 10px 0;"><b>Contact:</b> R15xxxx@ntu.edu.tw</p>
  <p class="custom-sub-text" style="margin: 0 0 15px 0;">* Please use the email subject prefix: <code>[Statistics TA]</code></p>
  <p style="margin: 0 0 10px 0;"><b>Office Hours:</b> By Appointment</p>
  <p class="custom-sub-text" style="margin: 0 0 15px 0;">* Please send me an email at least one day in advance</p>
  <p style="margin: 0;"><b>Location:</b> Room 6XX, Social Science Building</p>
</div>

---

## Announcement

<div class="custom-info-box">
  
  <div class="home-announcement-header">
    <h3 style="margin: 0; line-height: 1.3;">2026-06-13: Welcome to ECON2022!</h3>
  </div>
  
  <p style="margin: 0 0 20px 0; line-height: 1.65; font-size: 0.95em;">
    Welcome to the Statistics TA session! The website is now fully set up. You can explore and download weekly handouts, sample codes, and other course materials using the menu at the top right of this page. Feel free to contact me if you have any question or suggestion about the website!
  </p>

  <div class="home-announcement-footer">
    <a href="{{ '/announcements/' | relative_url }}" style="color: inherit; opacity: 0.7; font-size: 0.9em; font-weight: bold; text-decoration: none;">
      View Older Announcements &rarr;
    </a>
  </div>

</div>