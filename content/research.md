---
title: "Research"
subtitle: ""
# 用 landing page 模板，跟主页一样能放多个区块
type: landing
# Optional: 在页面顶显示封面色
design:
  spacing: '5rem'

sections:
  - block: collection        # --- Papers 区块 ---
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      view: citation

  - block: collection        # --- Talks 区块 ---
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
---
