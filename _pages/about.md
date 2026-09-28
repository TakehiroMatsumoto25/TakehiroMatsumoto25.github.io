---
layout: about
title: About
permalink: /
subtitle: 東北大学大学院 理学研究科 数学専攻 博士前期課程

profile:
  align: right
  image: Matsumoto_prof_pic0.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>東北大学大学院 理学研究科</p>
    <p>数学専攻 博士課程</p>
    <p>Email: takehiro.m.jp[at]gmail.com</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
one_page_nav: true

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---
<style>
  .profile img {
    width: 180px; /* この数字を小さくするほど、画像が小さくなります */
    height: auto;
    margin-top: 20px;
  }
</style>

こんにちは．松本健宏です．
現在サイト作成中です．


## Research Keywords (キーワード)

- **Mathematics, Computational science**: 
  - Finite Element Method (有限要素法)
  - Fluid Simulation (流体シミュレーション)
  - Aqueous humour (房水)
- **Causal Discovery**:
  - LiNGAM, VAR-LiNGAM
- **Machine Learning**:
  - Machine learning (機械学習)
  - Variational Auto-Encoder (変分オートエンコーダ)

<section id="projects" class="one-page-section" markdown="1">

## Projects

<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>

</section>

<section id="presentation" class="one-page-section" markdown="1">

## Presentations / 講演履歴

- **AMSC2026: Workshop on Applied Mathematics and Scientific Computing**（しいのき迎賓館，金沢，2026年1月）
  <br>"Finite Element Simulation of Thermal Convection in the Human Eye"

- **2025年度応用数学合同研究集会**（龍谷大学，2025年12月）
  <br>"前眼部における熱対流を含む房水流の有限要素シミュレーション"

- **応用数学フレッシュマンセミナー2025**（京都大学，2025年11月）
  <br>"大規模農業用灌漑システムの最適制御に向けたVAR-LiNGAMによる因果解析"

- **Current Status and New Development in the Theoretical Analysis for the Discrete Models of Partial Differential Equations**（中国 成都 University of Electronic Science and Technology of China，2025年9月）
  <!-- <br>"Finite element approaches to the thermal convection in the eye" -->

- **日本応用数理学会2025年度年会**（東京理科大学，2025年9月）
  <br>"大規模灌漑システムの最適制御に向けたVAR-LiNGAMによる因果解析"

</section>

<section id="publications" class="one-page-section" markdown="1">

## Publications

現在、論文は投稿準備中です。
(Currently in preparation.)

</section>

<section id="cv" class="one-page-section" markdown="1">

## CV

現在準備中です。
(Currently in preparation.)

</section>

<section id="myself" class="one-page-section" markdown="1">

## Myself

### BackGround

- **Hobbies**
  - Skiing
  - Cycling
  - Fishing
  - Eating Delicious food
  - Watching Motor sports (GT500)
  - Kicks

</section>


<!-- 
Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](https://www.reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. 
-->
