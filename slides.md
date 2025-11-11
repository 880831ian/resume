---
theme: seriph
background: "/img/about_background.png"
title: 莊品毅 CHUANG,PIN-YI (Ian) 履歷
info: |
  展示莊品毅 CHUANG,PIN-YI (Ian) 履歷
class: text-center
favicon: "https://pin-yi.me/favicon.svg"
drawings:
  persist: false
transition: slide-left
mdc: true
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

<!-- 第 2 頁 -->

# 關於我

<div class="flex justify-end">
  <img v-click="1" src="/img/about.jpg" class="absolute top-37 left-165 w-50" />
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

<!-- 第 3 頁 -->

# 職涯經歷

<div class="relative w-full mt-20">
  <!-- timeline line -->
  <div class="absolute top-10 left-0 w-full h-0.5 bg-gray-300" style="z-index: -1;"></div>

  <!-- arrow -->
  <div class="absolute top-8.2 right--1 w-0 h-0 border-t-8 border-b-8 border-l-8 border-transparent border-l-gray-300"></div>

  <!-- 年份區塊 -->
  <div class="w-full flex items-center justify-between mt-14">
    <div class="text-center w-1/4" v-click="1">
      <div class="text-lg font-bold mb-2">2022、2023</div>
      <div class="mx-auto w-3 h-3 bg-blue-400 rounded-full shadow"></div>
      <div class="mt-2 text-sm opacity-40">SRE @ 凡谷興業 (中佑)</div>
    </div>
    <div class="text-center w-1/4" v-click="6">
      <div class="text-lg font-bold mb-2">2024</div>
      <div class="mx-auto w-3 h-3 bg-blue-400 rounded-full shadow"></div>
      <div class="mt-2 text-sm opacity-40">SRE、SA @ 凡谷興業 (中佑)</div>
    </div>
    <div class="text-center w-1/4" v-click="13">
      <div class="text-lg font-bold mb-2">2025</div>
      <div class="mx-auto w-3 h-3 bg-blue-400 rounded-full shadow"></div>
      <div class="mt-2 text-sm opacity-40">SA @ 凡谷興業 (中佑)</div>
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
    <li v-click="7">優化 Prometheus 監控架構，不影響監控品質情境下，協助公司節省<span v-mark.underline.orange="8">每日約 USD 200 </span> 🔗</li>
    <li v-click="9">導入 Datadog，查詢與問題定位提升 <span v-mark.circle.orange="10">90%</span></li>
    <li v-click="11">主動追蹤 GCP 服務公告，撰寫對應方法以及 Shell Script，避免升級中斷並節省<span v-mark.underline.orange="12">約 USD 3,000 </span></li>
  </ul>

  <ul class="w-1/4 space-y-1.5 text-sm opacity-90 text-left">
    <li v-click="14">設計及導入 500 人的 AWS Org、SSO、GCP 遷移 AWS Infra 架構</li>
    <li v-click="15">開發<span v-mark.circle.orange="16"> 22 組 </span>AWS Terraform 模組，撰寫 45+ 篇技術文件</li>
    <li v-click="17">雲端網路重構及 Internal DNS 導入</li>
  </ul>
</div>

<div class="abs-br m-6 text-xl">
  <a href="https://pin-yi.me/blog/gcp/gcp-prometheus-sample-ingested-calculate/" target="_blank" class="slidev-icon-btn">
    <carbon:link />
  </a> 
</div>

---

<!-- 第 4 頁 -->

# 專案實績 - AWS Organizations + SSO、Infra 架構設計

<div class="relative flex justify-end">
<img
    v-click="1"
    v-show="$clicks == 1"
    src="/img/aws-architecture.png"
    class="absolute top--1 left-9 w-194 z-0"
/>

<img
    v-click="2"
    v-show="$clicks == 2"
    src="/img/aws-nginx.png"
    class="absolute top-4 left--2 w-290 z-10"
/>

<img
    v-click="3"
    v-show="$clicks == 3"
    src="/img/aws-internal.png"
    class="absolute top--1 left-12 w-190 z-10"
/>

<img
    v-click="4"
    v-show="$clicks == 4"
    src="/img/aws-static.png"
    class="absolute top-1 left-30 w-160 z-10"
/>

</div>

---

<!-- 第 5 頁 -->

# 專案實績 - Terraform、Helm 模組開發、自動化設計

<li v-click="1">IaC 模組開發 (Terragrunt 舉例)</li>
<li v-click="2">本地腳本開發 (Helmfile 舉例)</li>
<li v-click="3">自動化流程設計 (Helmfile、Terragrunt + GitLab CI)</li>

<div class="relative flex">
  <img
    v-click="1"
    v-show="$clicks == 1"
    src="/img/iac-modules.png"
    class="absolute top--24 left-75 w-105 z-0"
/>
</div>

<div class="relative flex">
  <img
    v-click="2"
    v-show="$clicks == 2"
    src="/img/helmfile-script.png"
    class="absolute top--2 left-20 w-195 z-0"
/>
</div>

<div class="relative flex">
  <img
    v-click="3"
    v-show="$clicks == 3"
    src="/img/helmfile-gitlab-ci.png"
    class="absolute top-5 left-0 w-250 z-0"
/>
</div>

<div class="relative flex">
  <img
    v-click="3"
    v-show="$clicks == 3"
    src="/img/terragrunt-gitlab-ci.png"
    class="absolute top-45 left-0 w-250 z-0"
/>
</div>

---

<!-- 第 6 頁 -->

# 專案實績 - Terraform、Helm 模組開發、自動化設計

<li>自動化流程設計 (Helmfile、Terragrunt + GitLab CI) 程式說明 / 說明檔案： <span>{{ $clicks < 4 ? '.gitlab-ci.yml' : '.generate_job.sh' }}</span></li>

````md magic-move {lines: true}
```yaml
git-diff:
  stage: git-diff
  script:
    # 先判斷是否為 main 分支，如果是就取前一次的 commit sha，否則就取 origin/main 的 commit sha
    - |
      if [ "$CI_COMMIT_BRANCH" == "main" ]; then
        LAST_COMMIT_SHA=$(git rev-parse HEAD~1)
      else
        LAST_COMMIT_SHA=$(git fetch origin && git rev-parse origin/main)
      fi
    # 先判斷 modules/ 下是否有檔案被修改
    - MODULES_CHANGED_FILES=$(git diff --name-only ${LAST_COMMIT_SHA} ${CI_COMMIT_SHA} -- ${CI_PR... (太長省略)
```

```yaml
- |
  if [ -z "$MODULES_CHANGED_FILES" ]; then
    echo "沒有任何 modules 檔案被修改！"
    # 如果沒有 modules 檔案被修改，就取 projects/ 下的檔案是否有被修改
    echo "檢查 hcl 檔案是否異動"
    CHANGED_FILES=$(git diff --name-only ${LAST_COMMIT_SHA} ${CI_COMMIT_SHA} -- ${CI_PROJECT_DIR}/projects/)
    if [ -z "$CHANGED_FILES" ]; then
      echo "沒有任何 hcl 檔案被修改！"
    else
      echo -e "本次異動 hcl 檔案：\n${CHANGED_FILES}"
    fi
  else
    ... 太長省略 ...
   # 針對同時有調整 module 以及 hcl 進行檢查及整理，且如果是調整 module 會隨機列出使用該 module 的 hcl 檔案)
```

```yaml
- |
  PROJECT_URL=$(echo "$CHANGED_FILES" | awk -F'/' '/projects\/[^\/]+\/.*\/(terragrunt\.hcl|.*\.tf)/ ... (太長省略)
  PROJECT_URL=$(echo $PROJECT_URL | sed 's/ /,/g')
  echo -e "最終結果：\n"${PROJECT_URL}
- |
  if [ "$CI_PIPELINE_SOURCE" == "merge_request_event" ]; then
    ./generate_job.sh ${PROJECT_URL} plan
  else
    ./generate_job.sh ${PROJECT_URL}
  fi
```

```yaml
artifacts:
  paths:
    - job.yml
  expire_in: "3600"
```

```shell
generate_job() {
  echo "${PROJECT_URL}:
  stage: plan(異動 modules 則隨機抽樣)
  script:
    - cd projects/${PROJECT_URL}
    - terragrunt validate
    - terragrunt refresh 1>/dev/null
    - |
      # 執行資訊
      echo -e \"========================== 請確認下方異動內容，是否正確 ==========================\n\"
    - terragrunt plan -out=tfplan
  artifacts:
    paths:
      - projects/${PROJECT_URL}
    expire_in: \"3600\"
  " >>job.yml
```

```shell
  if [ "${stage}" = "apply" ]; then
    echo "apply：${PROJECT_URL}:
  stage: apply
  script:
    - cd projects/${PROJECT_URL}
    - echo 'y' | terragrunt apply tfplan
  dependencies:
    - ${PROJECT_URL}
  needs:
    - ${PROJECT_URL}
  when: manual
  " >>job.yml
  fi
```
````

---

<!-- 第 7 頁 -->

# 技術部落格經營 — 持續學習與知識分享

<li v-click="1">已經撰寫 86 篇技術文章，持續增加中</li>
<li v-click="2">今年截至 11 月，不重複訪客達<span v-mark.circle.orange="3"> 9300 人</span> (GA4 計算)</li>
<li v-click="4">將部份文件範例程式碼開源，特定專案<span v-mark.underline.orange="5">累積 75 顆 Star 與 18 次 Fork</span> 🔗</li>

<div class="relative flex">
  <img
    v-click="3"
    v-show="$clicks == 3"
    src="/img/ga4.png"
    class="absolute top--5 left-9 w-120 z-0"
/>
</div>

<div class="relative flex">
  <img
    v-click="6"
    src="/img/blog.png"
    class="absolute top-9 left--10 w-120 z-0"
/>
  <img
    v-click="7"
    src="/img/github.png"
    class="absolute top-4 left-110 w-117 z-0"
/>
</div>

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/880831ian/Prometheus-Grafana-Docker" target="_blank" class="slidev-icon-btn">
    <carbon:link />
  </a>
</div>

---

<!-- 第 8 頁 -->

# 參與開源 — 從實務到社群

<li v-click="1">2023 年 7 月起持續參與 GitHub 開源專案</li>
<li v-click="2">聚焦在 SRE 與 DevOps 領域</li>

<br>
<br>

#### 🔧 主要貢獻 { v-click="3" }

<br>

<li v-click="4"> AWS EKS Terraform IaC Module - #3376</li>
<li v-click="5"> OpenTelemetry 官方文件 - #3096</li>

<div class="relative flex">
  <img
    v-click="4"
    src="/img/AWS-EKS-terraform-IaC-module.png"
    class="absolute top--70 left-110 w-110 z-0"
/>
  <img
    v-click="5"
    src="/img/OpenTelemetry.png"
    class="absolute top--1 left-110 w-110 z-0"
/>
</div>

<br>
<br>
<br>

<span v-click="6" style="color: red"> 已成功合併至專案的主幹分支（main/master branch）</span>

---

<!-- 第 9 頁 -->

# 專業認證 / 技能樹

<div class="flex items-start">
  <div class="relative w-130 h-80">
    <img src="/img/pca.webp" class="absolute top-0 left-0 w-45 z-0" />
    <img src="/img/rhce.webp" class="absolute top-37 left--0 w-45 z-0" />
    <img src="/img/rhcsa.webp" class="absolute top-73 left--0 w-45 z-0" />
  </div>

  <!-- 右邊文字 -->
  <ul class="ml--60 leading-relaxed mt-3">
  證照
    <li v-click="1">Google Cloud Professional Cloud Architect (PCA)  #2025/02</li>
    <li v-click="1">RED HAT CERTIFIED ENGINEER (RHCE)  #2019/07</li>
    <li v-click="1">RED HAT CERTIFIED SYSTEM ADMINISTRATOR (RHCSA)  #2019/01</li>
    <li v-click="2">AWS Certified Solutions Architect – Associate (SAA)  #預計 2026/04 前</li>
    <br>
  技能樹
    <li v-click="3">雲平台：GCP、AWS</li>
    <li v-click="3">容器化：Kubernetes (GKE、EKS、OpenShift)、Docker</li>
    <li v-click="3">IaC：Terraform、Terragrunt、Helm、Helmfile、Ansible</li>
    <li v-click="3">CI/CD：GitLab CI、GitHub Action、Jenkins</li>
    <li v-click="3">監控與日誌：Datadog、Prometheus、Grafana、EFK、GMP</li>
    <li v-click="3">程式語言：Shell Script</li>
  </ul>
</div>

---

<!-- 第 10 頁 -->

<div class="h-65 w-full flex items-center justify-center text-6xl">
  <span>Thank you / 感謝您的時間</span>
</div>

<div class="flex items-start">
  <div class="relative w-1000">
    <!-- Blog -->
    <div class="absolute top--5 left-20 flex flex-col items-center">
      <img src="/img/blog-qrcode.png" class="w-45 z-0" />
      <span class="mt-2 text-lg">Blog（技術文章）</span>
    </div>
    <!-- GitHub -->
    <div class="absolute top--5 left-83 flex flex-col items-center">
      <img src="/img/github-qrcode.png" class="w-45 z-0" />
      <span class="mt-2 text-lg">GitHub（專案 & 開源貢獻）</span>
    </div>
    <!-- Slidev -->
    <div class="absolute top--5 left-146 flex flex-col items-center">
      <img src="/img/slidev-qrcode.png" class="w-45 z-0" />
      <span class="mt-2 text-lg">Slidev (本簡報以此開源工具製作)</span>
    </div>
  </div>
</div>
