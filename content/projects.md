---
title: Projects
date: 2024-01-03
type: landing

design:
  css_class: projects-page
  spacing: '5rem'
  css_style: |
    .mt-2.line-clamp-3.text-sm.text-gray-500 {
      display: block !important;
      -webkit-line-clamp: initial !important;
      -webkit-box-orient: initial !important;
      overflow: visible !important;
    }

sections:
  - block: collection
    content:
      title: Selected Projects
      text: I enjoy making things. Here are a selection of projects that I have worked on over the years.
      filters:
        folders:
          - project
    design:
      view: article-grid
      text_length: 1000
      fill_image: false
      columns: 3
---