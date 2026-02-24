title: "Sleep and Cognition Lab"
summary: "Exploring the mysteries of sleep and memory."
date: 2026-02-24
type: landing

sections:

  block: hero
  content:
  title: "睡眠与认知实验室"
  text: "我们致力于通过神经科学手段研究睡眠中的记忆巩固、针对性记忆重现 (TMR) 以及大脑如何组织复杂信息。"
  image:
  filename: ""
  design:
  background:
  gradient_mesh:
  enable: true
  spacing:
  padding: ["120px", "0", "120px", "0"]

  block: features
  content:
  title: "研究方向"
  items:
  - name: 记忆重现 (TMR)
  description: 研究特定刺激在睡眠中如何触发记忆巩固。
  icon: brain
  icon_pack: fas
  - name: 数据建模 (RSA)
  description: 利用表征相似性分析探索神经活动的结构。
  icon: chart-bar
  icon_pack: fas
  - name: 实验技术
  description: 结合 EEG 和计算建模深入探索认知机制。
  icon: microchip
  icon_pack: fas

  block: collection
  id: publications
  content:
  title: "精选论文"
  filters:
  folders:
  - publication
  featured_only: true
  design:
  view: article-grid
  columns: 2

  block: collection
  id: news
  content:
  title: "最新动态"
  filters:
  folders:
  - post
  design:
  view: card
