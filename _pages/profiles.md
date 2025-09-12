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
    image: Yuan.jpg
    content: about_einstein.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p class="person-name">Kunxiaojia (Tammy) Yuan<br>



 # 插入一个标题
  - align: left
    more_info: >
      <p class="ad-name">
        <a href="https://ecoai-yuanlab.github.io/Opportunities/" target="_blank">
          We are recruiting Ph.D. students and postdocs! Click here for details.
        </a>
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
      <p class="person-name">Shuo Chen<br>

      

  - align: left
    image: Ben.jpg
    content: Ben.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p class="person-name">Benjamin Yan<br>


  - align: left
    image: Victor1.jpg
    content: Victor.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p class="person-name">Victor Chen<br>

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