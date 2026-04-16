---
layout: homepage
---

<nav class="custom-navbar">   <div class="nav-container">     <a href="#" class="nav-link">Homepage</a>     <a href="#-about-me" class="nav-link">About Me</a>    <a href="#-publications--preprints" class="nav-link">Publications & Preprints</a>  <a href="#-system--applications" class="nav-link">System & Applications</a>    </div> </nav>  <style>   html { scroll-behavior: smooth; scroll-padding-top: 80px; }   .custom-navbar {     position: sticky;     top: 0;     background-color: rgba(255, 255, 255, 0.95);     backdrop-filter: blur(10px);     z-index: 9999;     border-bottom: 1px solid #f0f0f0;     margin: -20px -20px 30px -20px;     padding: 15px 0;   }   .nav-container {     max-width: 1000px; /* 增加宽度以容纳更多导航项 */     margin: 0 auto;     display: flex;     justify-content: flex-start;     gap: 20px; /* 缩小间距以防在一行内排不下 */     padding: 0 20px;   }   .nav-link {     text-decoration: none !important;     color: #757575 !important;     font-weight: 600;     font-size: 15px; /* 略微缩小字号确保横向排布 */     transition: color 0.3s;     position: relative;     padding-bottom: 5px;     white-space: nowrap; /* 禁止文字换行 */   }   .nav-link:hover { color: #333 !important; }   .nav-link.active::after {     content: '';     position: absolute;     bottom: 0;     left: 40%;     width: 20%;     height: 3px;     background-color: #999;     border-radius: 2px;   }   @media (max-width: 768px) {     .nav-container {        gap: 15px;        overflow-x: auto;        white-space: nowrap;       justify-content: flex-start;     }     .nav-link { font-size: 14px; }   } </style>

## 👋 About Me

I am currently a Master’s student at the [School of Data Science and Engineering](https://dase.ecnu.edu.cn/) of [East China Normal University](https://www.ecnu.edu.cn/) and a member of the [Decision Intelligence Lab](https://decisionintelligence.github.io/index), advised by Prof. [Bin Yang](https://binyangdk.github.io/). For more information, you may take a look at my [Google Scholar](https://scholar.google.com/citations?user=F10D3A8AAAAJ) [![Google Scholar Citations](https://img.shields.io/endpoint?url=https://lizhengyu.1793410861.workers.dev/&logo=google-scholar&style=flat&labelColor=f0f0f0&color=8fb9ef)](https://scholar.google.com/citations?user=F10D3A8AAAAJ&hl) and [GitHub](https://github.com/DevCrafterLZY) [![GitHub Stars](https://img.shields.io/github/stars/DevCrafterLZY?affiliations=OWNER%2CCOLLABORATOR&style=flat&logo=github&logoColor=000000&label=GitHub%20Stars&labelColor=f0f0f0&color=8fb9ef)](https://github.com/DevCrafterLZY).


## 🏆 Awards

- **[Jan. 2026]** Our paper "[GCGNet: Graph-Consistent Generative Network for Time Series Forecasting with Exogenous Variables](https://arxiv.org/abs/2603.08032)" has been accepted by **ICLR 2026**.
- **[Nov. 2025]** Our paper "[Rethinking Irregular Time Series Forecasting: A Simple yet Effective Baseline](https://arxiv.org/pdf/2505.11250)" has been accepted for an **Oral Presentation** at **AAAI 2026**.
- **[Sep. 2025]** Our paper "[Enhancing Time Series Forecasting through Selective Representation Spaces: A Patch Perspective](https://arxiv.org/pdf/2510.14510)" has been accepted as a **Spotlight Poster** by **NeurIPS 2025**.
- **[Aug. 2025]** Our work has been awarded the **Huawei Potential High-Value Patent**.
- **[May. 2025]** Our paper "[TAB: Unified Benchmarking of Time Series Anomaly Detection Methods](https://arxiv.org/pdf/2506.18046)" has been accepted by **PVLDB 2025**.
- **[Jan. 2025]** Our paper "[CATCH: Channel-Aware Multivariate Time Series Anomaly Detection via Frequency Patching](https://arxiv.org/pdf/2410.12261)" has been accepted by **ICLR 2025**.
- **[Dec. 2023]** I have been awarded the **Special-Class Academic Excellence Scholarship**.
- **[Aug. 2023]** Our team has been awarded the **Second Prize** at the [Chinese Collegiate Computing Competition](https://jsjds.blcu.edu.cn/) 2023.
- **[Aug. 2022]** Our team has been awarded the **Third Prize** in the National Finals of the [RoboMaster University Championship](https://www.robomaster.com/zh-CN/) 2022.
- **[Dec. 2022]** I have been awarded the **Second-Class Academic Excellence Scholarship**.
- **[Dec. 2021]** I have been awarded the **First-Class Academic Excellence Scholarship**.

[//]: # (## 🔍 Research Topics)

[//]: # ()
[//]: # (My research interests cover Time Series Analysis and Deep Learning. I am currently working on foundation time series models, and time series benchmarking. In addition to pure research, I also dedicate myself to promoting research on valuable real-world applications. My research aims to contribute to the advancement of intelligent systems capable of handling massive and complicated temporal data across domains, including finance, industry, and environment.)

[//]: # ()
[//]: # (For more information, you may take a look at my [Google Scholar]&#40;https://scholar.google.com.hk/citations?user=Hal0V_AAAAAJ&#41; and [GitHub]&#40;https://github.com/DevCrafterLZY&#41;.)




{% include_relative _includes/publications.md %}



{% include_relative _includes/applications.md %}



## 👀 Visitors

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=n&d=Kjm4Zd-uz06fWWD_PHjAJjsN9m5JlhZQdGBD9fc-9Ig"></script>
