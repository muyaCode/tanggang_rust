---
# 文档：https://vitepress.dev/zh/guide/frontmatter

# # 选项 home 将生成模板化的“主页”，在此布局中，您可以设置额外的选项，例如hero和features。
# layout: home
# doc 是默认布局，它将整个 Markdown 内容样式化为“文档”外观。
layout: doc
# # 选项 page 被视为“空白页”， Markdown 仍然会被解析，并且所有 Markdown Extensions 与 doc 布局同样生效，但它不会获得任何默认样式。
# layout: page

title: 前端学习笔记
titleTemplate: 记录一些前端学习的知识

hero:
  name: 前端路线基础到进阶
  text: 后浪卷前浪
  tagline: "不进则退"
  # 首页右边Logo设置
  # image:
  #   src: /logo.png
  #   alt: logo
  actions:
    - theme: brand
      text: 查看笔记
      link: /order/study_guide
    - theme: alt
      text: 在 GitHub 上查看
      link: https://github.com/muyaCode/FrontEndLearningNotes

features:
  - icon: 💡
    title: HTML
    details: 基于vitePress构建
  - icon: 📦
    title: CSS
    details: 由浅入深
  - icon: 🛠️
    title: JavaScript
    details: JavaScript基础到进阶。
---

<!-- 文档：https://vitepress.vuejs.org/config/frontmatter-configs#layout -->
<!-- 表情：https://github.com/markdown-it/markdown-it-emoji/blob/master/lib/data/full.json -->

<style>
  /*首页标题 覆盖变量 自定义字体渐变样式*/
  :root {
    --vp-home-hero-name-color: transparent;
    --vp-home-hero-name-background: -webkit-linear-gradient(120deg, #bd34fe, #41d1ff);
  }
</style>

<!-- 团队成员显示 -->
<!-- <script setup>
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers
} from 'vitepress/theme'

const members = [
  {
    avatar: 'https://www.github.com/yyx990803.png',
    name: 'Evan You',
    title: 'Creator',
    links: [
      { icon: 'github', link: 'https://github.com/yyx990803' },
      { icon: 'twitter', link: 'https://twitter.com/youyuxi' }
    ]
  },
]
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>
      我们的团队
    </template>
    <template #lead>
      各个成员来着....
    </template>
  </VPTeamPageTitle>
  <VPTeamMembers :members="members" />
</VPTeamPage> -->
