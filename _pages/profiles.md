---
layout: profiles
permalink: /people/
title: People
nav: true
nav_order: 4


profiles:
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - align: left
    image: Yuan_2.jpg
    content: about_einstein.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p style="font-family: Georgia, serif; font-size: 18px; ">
       PI: Tammy Yuan
      </p>
      <!-- 一排社交图标 -->
      <p style="margin-top:8px; font-size: 28px;">
        <a href="/cv/" target="_blank" rel="noopener"
          style="font-family:Georgia, serif; font-size:22px; font-weight:600; margin-right:10px;">
          CV
        </a>
        <a href="https://scholar.google.com/citations?user=XiLO06sAAAAJ&hl=en&oi=ao" target="_blank"><i class="ai ai-google-scholar"></i></a>
        <a href="https://x.com/KunxiaojiaYuan" target="_blank"><i class="fab fa-x-twitter"></i></a>
        <a href="https://www.linkedin.com/in/kunxiaojia-tammy-yuan-1550b01aa/" target="_blank"><i class="fab fa-linkedin"></i></a>

      </p>

 

 # 插入一个标题
  - align: left
    more_info: >
      <p class="Title-name">PhD students</p>

  - align: left
    image: Xiaofan_2.jpg
    content: Xiaofan.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p style="font-family: Georgia, serif; font-size: 18px; ">
        Xiaofan Shen
      </p>

  - align: left
    image: Jiaxuan_3.jpg
    content: Jiaxuan.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p style="font-family: Georgia, serif; font-size: 18px; ">
        Jasmine (Jiaxuan) Miao
      </p>



  # 插入一个标题
  - align: left
    more_info: >
      <p class="Title-name">Summer RA</p>

  - align: left
    image: Rijul.jpg
    content: Rijul.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p style="font-family: Georgia, serif; font-size: 18px; ">
        Rijul Dimri
      </p>

 # 插入一个标题
  - align: left
    more_info: >
      <p class="Title-name">Undergraduates</p>

  - align: left
    image: Manavi.jpg
    content: Manavi.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p style="font-family: Georgia, serif; font-size: 18px; ">
        Manavi Gupta
      </p>

 # 插入一个标题
  - align: left
    more_info: >
      <p class="Title-name">Alumni</p>

  - align: left
    image: shuo.jpg
    content: Shuo.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p style="font-family: Georgia, serif; font-size: 18px; ">
        Shuo Chen
      </p>

      

  - align: left
    image: Ben.jpg
    content: Ben.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p style="font-family: Georgia, serif; font-size: 18px; ">
        Benjamin Yan
      </p>


  - align: left
    image: Victor1.jpg
    content: Victor.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p style="font-family: Georgia, serif; font-size: 18px; ">
        Victor Chen
      </p>


 # 插入一个标题
  - align: left
    more_info: >
      <p class="Title-name">Committees</p>
  - align: left
    content: Commitee.md
    more_info: >
      <p class="Title-name">
      PhD
      <br><br><br><br><br><br><br><br>
      </p>
   # 插入一个标题
  - align: left
    content: Commitee1.md
    more_info: >
      <p class="Title-name">Master </p>


---



<style>
/* 只在 people 页面生效 */
.person-name {
  font-family: "Georgia", "Times New Roman", serif;
  font-size: 1.15rem;
  font-weight: 400;
  color: #1c1c1d;
  text-align: center;
  margin-top: 8px;
  margin-bottom: 0;
}
</style>

<style>
/* 只在 people 页面生效 */
.ad-name {
  font-family: "Georgia", "Times New Roman", serif;
  font-size: 1.15rem;
  font-weight: 600;
  color: var(--global-theme-color);
  text-align: center;
  margin-top: 8px;
  margin-bottom: 0;
}
</style>


<style>
/* 只在 people 页面生效 */
.Title-name {
  font-family: "Georgia", "Times New Roman", serif;
  font-size: 2rem;
  font-weight: 600;
  color: #1c1c1d;
  text-align: center;
  margin-top: 8px;
  margin-bottom: 0;
}
</style>


<style>
  /* 只影响本页的个人头像 */
  .profile img {
    max-width: 300px;   /* 桌面端最大宽度 */
    width: 90%;         /* 再保险地限制一下相对宽度 */
    height: auto;
  }
  /* 手机端更小一点 */
  @media (max-width: 768px) {
    .profile img {
      max-width: 160px;
      width: 70%;
    }
  }
</style>


<style>
  /* 深色模式下把名字和分组标题改成白色 */
  @media (prefers-color-scheme: dark) {
    .person-name,
    .Title-name { color: #fff !important; }
  }

  /* 若你的主题用 data-theme 切换暗色，也一并兼容 */
  :root[data-theme="dark"] .person-name,
  :root[data-theme="dark"] .Title-name { color: #fff !important; }
</style>


