---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 下载简历
        url: uploads/resume.pdf
      headings:
        about: '关于我'
        education: '教育与经历'
        interests: '合作方向'
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium
        shape: circle
  
  - block: collection
    id: publications
    content:
      title: 代表作品与著作
      text: 融合 AI 技术、影视叙事与心理学洞察，打造高影响力跨界内容。
      
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
      spacing:
        padding: [6rem, 0, 6rem, 0]

  
  - block: collection
    id: news
    content:
      title: 近期动态
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
        
  - block: cta-card
    # demo: true # 移除这个行，以在您的正式网站上显示
    content:
      title: 期待与您合作
      text: |-
        如果您正在寻找一位既懂传统影视创作，又能熟练运用AI技术的创意人才，我愿意用我的经验和热情为您的项目创造价值。
        
        联系我：13141478676 邮箱：xinxin5007@gmail.com
      button:
        text: 联系 Iris Wang
        url: 'mailto:xinxin5007@gmail.com'
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---