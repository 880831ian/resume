---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: "./img/about_background.png"
# some information about your slides (markdown enabled)
title: 莊品毅 CHUANG,PIN-YI (Ian) 履歷
info: |
  展示莊品毅 CHUANG,PIN-YI (Ian) 履歷
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
duration: 35min
---

<!-- 封面 -->

# 莊品毅 CHUANG,PIN-YI (Ian)

## System Architect / SRE

專注雲端與自動化實務，致力推動企業打造穩定且可擴展的系統架構

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/880831ian" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
  <a href="https://pin-yi.me" target="_blank" class="slidev-icon-btn">
    <carbon:link />
  </a>
  <a href="mailto:880831ian@gmail.com" class="slidev-icon-btn">
    <carbon:email />
  </a>  
</div>

---

<!-- 第二頁 -->

# 關於我

<div class="flex justify-end">
  <img v-click="1" src="./img/about.jpg" class="absolute top-37 left-165 w-50" />
</div>

<br>

#### 🧱 專業背景 { v-click="2" }

<br>

<li v-click="3">具備近 4 年雲端架構與 SRE 經驗</li>

<li v-click="4">熟悉 IaC 自動化與監控整合，具成本優化經驗</li>

<li v-click="5">精通 Terraform、Helm、Kubernetes、Datadog</li>

<li v-click="6">持續經營技術部落格，並活躍於社群</li>

<br>

#### 💡 個人特質 { v-click="7" }

<br>

<li v-click="8">主動解決問題、能獨立推動技術改善</li>

<li v-click="9">重視架構一致性與自動化、能提升團隊效率</li>

<li v-click="10">樂於學習與分享、促進團隊知識流通</li>

---

<!-- 第三頁 -->

# 職涯經歷

<div class="relative w-full mt-20">

  <!-- timeline line -->
  <div class="absolute top-10 left-0 w-full h-0.5 bg-gray-300" style="z-index: -1;"></div>

  <!-- arrow -->
  <div class="absolute top-8.2 right-0 w-0 h-0 
              border-t-8 border-b-8 border-l-8 border-transparent 
              border-l-gray-300">
  </div>

  <!-- 年份區塊 -->
  <div class="w-full flex items-center justify-between mt-14">
    <div class="text-center w-1/4" v-click="1">
      <div class="text-lg font-bold mb-2">2022、2023</div>
      <div class="mx-auto w-3 h-3 bg-blue-400 rounded-full shadow"></div>
      <div class="mt-2 text-sm opacity-40">SRE @ 凡谷興業有限公司</div>
    </div>
    <div class="text-center w-1/4" v-click="6">
      <div class="text-lg font-bold mb-2">2024</div>
      <div class="mx-auto w-3 h-3 bg-blue-400 rounded-full shadow"></div>
      <div class="mt-2 text-sm opacity-40">SRE、SA @ 凡谷興業有限公司</div>
    </div>
    <div class="text-center w-1/4" v-click="12">
      <div class="text-lg font-bold mb-2">2025</div>
      <div class="mx-auto w-3 h-3 bg-blue-400 rounded-full shadow"></div>
      <div class="mt-2 text-sm opacity-40">SA @ 凡谷興業有限公司</div>
    </div>    
  </div>
</div>

<div class="w-full flex items-start justify-between mt-14">

  <ul class="w-1/4 space-y-3 text-sm text-left">
    <li v-click="2">管理 30 座以上 GKE 叢集約 500 個節點，平均每分鐘 100K 請求</li>
    <li v-click="3">熟悉 GitLab CI、EFK、GMP、Grafana 建立 CI/CD 自動化及監控日誌系統</li>
    <li v-click="4">主導 IaC 自動化與部署流程重構，維運效率提升約 <span v-mark.circle.orange="5">70%</span></li>
  </ul>

  <ul class="w-1/4 space-y-1.5 text-sm opacity-90 text-left">
    <li v-click="7">導入 Datadog，查詢與問題定位提升 <span v-mark.circle.orange="8">90%</span></li>
    <li v-click="9">優化 Prometheus 監控架構，不影響監控品質情境下，協助公司節省<span v-mark.underline.orange="9">每日約 USD 200 </span> 🔗</li>
    <li v-click="10">主動追蹤 GCP 服務公告，撰寫對應方法以及 Shell Script，避免升級中斷並節省<span v-mark.underline.orange="11">約 USD 3,000 </span></li>
  </ul>

  <ul class="w-1/4 space-y-1.5 text-sm opacity-90 text-left">
    <li v-click="13">設計及導入 500 人的 AWS Org、SSO、GCP 遷移 AWS Infra 架構</li>
    <li v-click="14">開發<span v-mark.circle.orange="15"> 22 組 </span>AWS Terraform 模組，撰寫 45+ 篇技術文件</li>
    <li v-click="16">雲端網路重構及 Internal DNS 導入</li>
  </ul>
</div>

<div class="abs-br m-6 text-xl">
  <a href="https://pin-yi.me/blog/gcp/gcp-prometheus-sample-ingested-calculate/" target="_blank" class="slidev-icon-btn">
    <carbon:link />
  </a> 
</div>

---

<!-- 第四頁 -->

# 專案實績 - AWS Organizations + SSO、Infra 架構設計

<div class="relative flex justify-end">
<img
    v-click="1"
    v-show="$clicks == 1"
    src="./img/aws-architecture.png"
    class="absolute top--1 left-9 w-194 z-0"
/>

<img
    v-click="2"
    v-show="$clicks == 2"
    src="./img/aws-nginx.png"
    class="absolute top-4 left--2 w-290 z-10"
/>

</div>

<br>

---

<!-- 第五頁 -->

# 專案實績 - Helm、Helmfile 自動化

---

<!-- 第六頁 -->

# 專案實績 - IaC Terraform、Terrgrunt 自動化

---

<!-- 第七頁 -->

# 經營 Blog — 知識分享與成長

<li v-click="1">已經撰寫 86 篇技術文章，持續成長中</li>

<li v-click="2">過去一年不重複訪客達<span v-mark.circle.orange="3"> 4666 人</span> (GA4 計算)</li>

<li v-click="4">將部份文件範例程式碼開源，特定專案<span v-mark.underline.orange="5">累積 74 顆 Star 與 18 次 Fork</span> 🔗</li>

<div class="relative flex">
  <img
    v-click="3"
    v-show="$clicks == 3"
    src="./img/ga4.jpg"
    class="absolute top--5 left-9 w-120 z-0"
/>
</div>

<div class="relative flex">
  <img
    v-click="6"
    src="./img/blog.png"
    class="absolute top-9 left--10 w-120 z-0"
/>
  <img
    v-click="7"
    src="./img/github.png"
    class="absolute top-4 left-110 w-117 z-0"
/>
</div>

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/880831ian/Prometheus-Grafana-Docker" target="_blank" class="slidev-icon-btn">
    <carbon:link />
  </a> 
</div>

<br>
