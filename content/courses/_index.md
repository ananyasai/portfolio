---
title: Courses
summary: My courses
type: landing
hero_media: "featured.jpg"
image:
  caption: "Relevant Courses"
  focal_point: "Center"
  preview_only: false
cascade:
  - target:
      path: '{/courses/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: all-courses
    content:
      title: Relevant Courses
      filters:
        folders:
          - courses
        exclude_featured: false
      count: 0   # show all
    design:
      view: citation
---
