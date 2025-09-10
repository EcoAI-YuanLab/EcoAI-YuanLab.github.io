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
      <p class="person-name">Kunxiaojia Yuan</p>
 # 插入一个标题
  - align: left
    more_info: >
      <p class="ad-name">👉 We are hiring postdoc and PhD students! Contact Dr. Yuan for details.</p>

 # 插入一个标题
  - align: left
    more_info: >
      <p class="Title-name">Alumni</p>

  - align: left
    image: shuo.jpg
    content: Shuo.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p class="person-name">Shuo Chen</p>

  - align: left
    image: Ben.jpg
    content: Ben.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p class="person-name">Benjamin Yan</p>

  - align: left
    image: Victor1.jpg
    content: Victor.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p class="person-name">Victor Chen</p>
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