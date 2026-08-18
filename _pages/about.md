---
permalink: /
title: "TA Website for Statistics with Recitation (26F)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 讓框框內的內文顏色跟隨系統主題切換 */
  .custom-info-box p {
    color: inherit !important;
  }
  
  .custom-sub-text {
    font-size: 0.95em;
    padding-left: 15px;
    opacity: 0.8; 
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

  /* 淺色模式下 code 區塊的預設樣式 */
  .custom-info-box code {
    background-color: #f1f5f9 !important;
    color: #475569 !important;
    padding: 3px 8px;
    border-radius: 5px;
    font-family: monospace;
    font-size: 0.95em;
  }

  /* ======================================================== */
  /* 強制覆蓋：當偵測到系統深色模式，或網頁被啟用深色主題時 */
  /* ======================================================== */
  
  @media (prefers-color-scheme: dark) {
    .custom-info-box {
      background-color: #252a34 !important; /* 強制變黑底 */
      border-color: #3f444e !important;     /* 強制變暗邊框 */
      color: #ffffff !important;            /* 強制文字變白 */
    }
    .home-announcement-header, .home-announcement-footer {
      border-bottom-color: #3f444e !important; 
      border-top-color: #3f444e !important;
    }
    .custom-info-box code {
      background-color: #1e222b !important; 
      color: #cbd5e1 !important;           
    }
  }
  
  html[data-theme="dark"] .custom-info-box,
  .theme-dark .custom-info-box {
    background-color: #252a34 !important;
    border-color: #3f444e !important;
    color: #ffffff !important;
  }
  html[data-theme="dark"] .home-announcement-header,
  html[data-theme="dark"] .home-announcement-footer,
  .theme-dark .home-announcement-header,
  .theme-dark .home-announcement-footer {
    border-bottom-color: #3f444e !important;
    border-top-color: #3f444e !important;
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

<div class="custom-info-box" style="background-color: #ffffff; border: 1px solid #e2e8f0; color: #222222; padding: 20px; border-radius: 10px; margin-top: 15px;">
  <p style="margin: 0 0 10px 0;"><b>Contact:</b> R15323005@ntu.edu.tw</p>
  <p class="custom-sub-text" style="margin: 0 0 15px 0;">* Please use the email subject prefix: <code>[Statistics TA]</code></p>
  <p style="margin: 0 0 10px 0;"><b>Office Hours:</b> By Appointment</p>
  <p class="custom-sub-text" style="margin: 0 0 15px 0;">* Please send me an email at least one day in advance</p>
  <p style="margin: 0;"><b>Location:</b> Room 6XX, Social Science Building</p>
</div>

---

## Announcement

<div class="custom-info-box" style="background-color: #ffffff; border: 1px solid #e2e8f0; color: #222222; padding: 20px; border-radius: 10px; margin-top: 15px;">
  
  <div class="home-announcement-header">
    <h3 style="margin: 0; line-height: 1.3;">2026-06-13: Welcome to ECON2022!</h3>
  </div>
  
  <p style="margin: 0 0 20px 0; line-height: 1.65; font-size: 0.95em;">
    Welcome to the Statistics TA session! The website is now fully set up. You can explore and download weekly handouts, sample codes, and other course materials using the menu at the top right of this page. Feel free to contact me if you have any question or suggestion about the website!
  </p>

  <div class="home-announcement-header">
    <h3 style="margin: 0; line-height: 1.3;">2026-07-04: PDFs Now Available!</h3>
  </div>
  
  <p style="margin: 0 0 20px 0; line-height: 1.65; font-size: 0.95em;">
    Hi everyone, the PDF versions of the TA session notes and weekly exercises have been updated for those who prefer to study with PDFs. One thing to note is that the PDF formatting may not look as polished (and as pretty) as the original Notion pages. If you have any suggestions for improving the PDF layout or know of a better way to preserve the formatting, I'd love to hear from you! Your feedback will help us continue improving the quality of this course. Thank you!
  </p>

  <div class="home-announcement-footer">
    <a href="{{ '/announcements/' | relative_url }}" style="color: inherit; opacity: 0.7; font-size: 0.9em; font-weight: bold; text-decoration: none;">
      View Previous Announcements &rarr;
    </a>
  </div>

</div>