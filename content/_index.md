---
date: "2025-03-14"
sections:
- block: hero
  content:
    title: The Vazquez Lab
    cta:
        label: Join us!
        url: /contact
        icon_pack: fas
        icon: user-plus
    cta_alt:
        label: Meet the team
        url: /people
    cta_note:
        label: |-
          We're recruiting undergrads, grad students, and postdocs interested in
          studying the evolution of aging using pangenomics, molecular and 
          cellular biology, and functional evolutionary genomics.
    image:
      filename: Collage.jpg
    text: |-
      <br>
      
      Studying the *evolution of longevity-associated traits* and the *gene 
      regulatory networks* that govern them in extraordinarily long-lived 
      mammals at all levels of life.

- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    page_type: post
    subtitle: null
    text: null
    title: Latest News
  design:
    columns: "2"
    view: card
# - block: markdown
#   content:
#     subtitle: ""
#     text: null
#     title: null
#   design:
#     background:
#       image:
#         filename: coders.jpg
#         filters:
#           brightness: 1
#         parallax: false
#         position: center
#         size: cover
#         text_color_light: true
#     columns: "1"
#     css_class: fullscreen
#     spacing:
#       padding:
#       - 20px
#       - "0"
#       - 20px
#       - "0"
- block: collection
  content:
    count: 5
    filters:
      folders:
      - publication
      # publication_type: article
    text: ""
    title: Latest Publications
  design:
    columns: "2"
    view: citation
- block: markdown
  content:
    subtitle: null
    text: |
      {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    title: null
  design:
    columns: "1"
title: null
type: landing
---
