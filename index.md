---
layout: homepage
---

<nav class="custom-navbar">   <div class="nav-container">     <a href="#" class="nav-link">Homepage</a>     <a href="#-about-me" class="nav-link">About Me</a>     <a href="#-research-topics" class="nav-link">Research Topics</a> <a href="#-publications--preprints" class="nav-link">Publications & Preprints</a>  <a href="#-system--applications" class="nav-link">System & Applications</a>    </div> </nav>  <style>   html { scroll-behavior: smooth; scroll-padding-top: 80px; }   .custom-navbar {     position: sticky;     top: 0;     background-color: rgba(255, 255, 255, 0.95);     backdrop-filter: blur(10px);     z-index: 9999;     border-bottom: 1px solid #f0f0f0;     margin: -20px -20px 30px -20px;     padding: 15px 0;   }   .nav-container {     max-width: 1000px; /* 增加宽度以容纳更多导航项 */     margin: 0 auto;     display: flex;     justify-content: flex-start;     gap: 20px; /* 缩小间距以防在一行内排不下 */     padding: 0 20px;   }   .nav-link {     text-decoration: none !important;     color: #757575 !important;     font-weight: 600;     font-size: 15px; /* 略微缩小字号确保横向排布 */     transition: color 0.3s;     position: relative;     padding-bottom: 5px;     white-space: nowrap; /* 禁止文字换行 */   }   .nav-link:hover { color: #333 !important; }   .nav-link.active::after {     content: '';     position: absolute;     bottom: 0;     left: 40%;     width: 20%;     height: 3px;     background-color: #999;     border-radius: 2px;   }   @media (max-width: 768px) {     .nav-container {        gap: 15px;        overflow-x: auto;        white-space: nowrap;       justify-content: flex-start;     }     .nav-link { font-size: 14px; }   } </style>

## 👋 About Me

I am currently a Master’s student at the [School of Data Science and Engineering](https://dase.ecnu.edu.cn/) of [East China Normal University](https://www.ecnu.edu.cn/) and a member of the [Decision Intelligence Lab](https://decisionintelligence.github.io/index), advised by Prof. [Bin Yang](https://binyangdk.github.io/). 



## 🔍 Research Topics

My research interests cover Time Series Analysis and Deep Learning. I am currently working on foundation time series models, and time series benchmarking. In addition to pure research, I also dedicate myself to promoting research on valuable real-world applications. My research aims to contribute to the advancement of intelligent systems capable of handling massive and complicated temporal data across domains, including finance, industry, and environment.

For more information, you may take a look at my [Google Scholar](https://scholar.google.com.hk/citations?user=Hal0V_AAAAAJ) and [GitHub](https://github.com/DevCrafterLZY).




{% include_relative _includes/publications.md %}



{% include_relative _includes/applications.md %}



## 👀 Visitors

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=n&d=Kjm4Zd-uz06fWWD_PHjAJjsN9m5JlhZQdGBD9fc-9Ig"></script>




