---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: portada2.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Welcome 👋'
      subtitle: ''
      text: |-
         Research scientist at the CITIC Research Centre at University of Granada. I am currently finishing my PhD on K-B Recommendation systems and nutrition.

         🆕🆕 **Currently looking for Postdocs opportunities around ecology, biodiversity and climate change.** 🆕🆕

         **Also, open to collaborate on interesting research projects!**

         **Main areas:** Data analysis, Machine learning,  Knowledge-based Systems, Natural Language Processing.


         **Brief Bio:** Applied mathematician and machine learning researcher. Pro‑efficiency in scientific communication. I have experience
          working in interdisciplinary groups obtaining, cleaning, analyzing and predicting data. I build tools based on ML/DL algorithms. I have participated in two european H2020 projects and several international conferences. 
          I’m looking for interdisciplinary challenges where my skills could help in the development of new technologies to tackle social
          and environmental issues. 



    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '1'
---
