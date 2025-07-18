---
layout: home
layoutClass: "m-home-layout"

hero:
  name: 千浔物语
  text: Qian Xun 的成长之路
  tagline: 知识是进步的阶梯，争取每天都有知识点更新
  image:
    src: /logo.png
    alt: 千浔物语
  actions:
    - text: 前端物语
      link: /fe/es6/
    - text: 源码阅读
      link: /analysis/utils/only-allow
      theme: alt
    - text: 日常笔记
      link: /notes/css/flex
    - text: 踩坑记录
      link: /pit/packageManager
      theme: alt
features:
  - icon: 📖
    title: 前端物语
    details: 整理前端常用知识点<small>（面试八股文）</small><br />如有异议按你的理解为主，不接受反驳 🧐
    link: /fe/javascript/types
    linkText: 前端常用知识
  - icon: 📘
    title: 源码阅读
    details: 了解各种库的实现原理<br />学习其中的小技巧和冷知识 🔍️
    link: /analysis/utils/only-allow
    linkText: 源码阅读
  - icon: 💡
    title: Workflow
    details: 在工作中学到的一切<small>（常用库/工具/奇淫技巧等）</small><br />配合 CV 大法来更好的摸鱼 🙈
    link: /workflow/utils/library
    linkText: 常用工具库
  - icon: 📝
    title: 日常笔记
    details: 根据日常工作以及学习总结而成的一系列笔记、文章<br  />长文章预警！✨
    link: /notes/css/flex
    linkText: 日常笔记
  - icon: 🐞
    title: 踩坑记录
    details: 那些年我们一起踩过的坑<br />总有一些让我们想不到的问题 🤡
    link: /pit/packageManager
    linkText: 踩坑记录
  - icon: 🌟
    title: 翻译文章
    details: 翻译国外的一些好文章<br />个人渣翻如有错误还请理解 🌱
    link: /translate/debounceAndThrotting
    linkText: 踩坑记录
  - icon: 🧰
    title: 提效工具
    details: 工欲善其事，必先利其器<br />记录开发和日常使用中所用到的软件、插件、扩展等 💫
    link: /efficiency/online-tools
    linkText: 提效工具
  - icon: 🍺
    title: Keep Reading, Keep Coding, Keep Learning! 🎉
    details: '<small class="bottom-small">一个想躺平的小开发</small>'
    link: /mao
---

<!-- 首页下划线 -->
<HomeUnderline />

<!-- 五彩纸屑 -->
<Confetti />

<style>
/*爱的魔力转圈圈*/
.m-home-layout .image-src:hover {
  transform: translate(-50%, -50%) rotate(666turn);
  transition: transform 59s 1s cubic-bezier(0.3, 0, 0.8, 1);
}

.m-home-layout .details small {
  opacity: 0.8;
}

.m-home-layout .item:last-child .details {
  display: flex;
  justify-content: flex-end;
  align-items: end;
}
</style>
