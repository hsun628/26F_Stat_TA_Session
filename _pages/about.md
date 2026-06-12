---
permalink: /
title: "TA Website for Statistics with Recitation (26F)!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- CSS 樣式定義，負責橫向排版與切換邏輯 -->
<style>
  .tabs-container {
    position: relative;
    margin: 20px 0;
    background: #fff;
  }
  .tabs-container input[type="radio"] {
    display: none;
  }
  .tabs-nav {
    display: flex;
    border-bottom: 2px solid #e0e0e0;
    margin-bottom: 15px;
  }
  .tabs-nav label {
    padding: 10px 20px;
    font-size: 11pt;
    font-weight: bold;
    color: #666;
    cursor: pointer;
    border-bottom: 2px solid transparent;
    margin-bottom: -2px;
    transition: all 0.2s ease;
  }
  .tabs-nav label:hover {
    color: #003366;
  }
  .tab-content {
    display: none;
    padding: 10px 5px;
    animation: fadeIn 0.3s ease;
  }
  /* 切換選取狀態 */
  #tab1:checked ~ .tabs-nav label[for="tab1"],
  #tab2:checked ~ .tabs-nav label[for="tab2"],
  #tab3:checked ~ .tabs-nav label[for="tab3"] {
    color: #003366;
    border-bottom: 2px solid #003366;
  }
  #tab1:checked ~ #content1,
  #tab2:checked ~ #content2,
  #tab3:checked ~ #content3 {
    display: block;
  }
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(2px); }
    to { opacity: 1; transform: translateY(0); }
  }
</style>

<div class="tabs-container">
  <!-- 隱藏的單選鈕，用來控制狀態 -->
  <input type="radio" id="tab1" name="tab-group" checked>
  <input type="radio" id="tab2" name="tab-group">
  <input type="radio" id="tab3" name="tab-group">

  <!-- 橫向導覽列選單 -->
  <div class="tabs-nav">
    <label for="tab1">📊 Slide 課程講義</label>
    <label for="tab2">💻 R Code 程式碼</label>
    <label for="tab3">📈 Data 實習資料集</label>
  </div>

  <!-- 分頁內容 1: Slide -->
  <div id="content1" class="tab-content">
    <p style="color: #666; font-style: italic;">點擊下方連結下載各週簡報 PDF：</p>
    <ul>
      <li><b>Week 01：</b> <a href="{{ site.url }}/files/W1_Intro.pdf">W1_Intro.pdf (R 環境安裝與基礎)</a></li>
      <li><b>Week 02：</b> <a href="{{ site.url }}/files/W2_Descriptive.pdf">W2_Descriptive.pdf (敘述統計與 Tidyverse)</a></li>
      <li><b>Week 03：</b> <span style="color: #999;">機率分佈與繪圖（尚未公佈）</span></li>
    </ul>
  </div>

  <!-- 分頁內容 2: R Code -->
  <div id="content2" class="tab-content">
    <p style="color: #666; font-style: italic;">每週實習課示範 R 腳本檔案：</p>
    <ul>
      <li><b>Week 01：</b> <a href="{{ site.url }}/files/W1_Code.R">W1_Code.R (基本物件與運算)</a></li>
      <li><b>Week 02：</b> <a href="{{ site.url }}/files/W2_Code.R">W2_Code.R (dplyr 資料清洗練習)</a></li>
      <li><b>Week 03：</b> <span style="color: #999;">ggplot2 繪圖範例（尚未公佈）</span></li>
    </ul>
  </div>

  <!-- 分頁內容 3: Data -->
  <div id="content3" class="tab-content">
    <p style="color: #666; font-style: italic;">上課進度或作業所需之數據集：</p>
    <ul>
      <li><b>Week 01：</b> <i>無外部資料集</i></li>
      <li><b>Week 02：</b> <a href="{{ site.url }}/files/survey.csv">survey.csv (課堂問卷回收資料)</a></li>
      <li><b>Week 03：</b> <span style="color: #999;">尚未公佈</span></li>
    </ul>
  </div>
</div>

### Hi! This is the TA Website for Statistics with Recitation (26F)!
All TA Session Materials will be posted here, including slides, R codes, HW, and Quizs.

### Contact: R15xxxx.ntu.edu.tw (Mail Title with [Statistics TA])
### Office Hours: 
- **By Appointment** (Send me an Email!) 
- **Location:** Social Science Building Room 6XX

### Announcement