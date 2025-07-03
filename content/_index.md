---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
  

sections:
  - block: slider
    content:
      slides:
      - title: Vision & Mission
        content: "We engineer low-noise, ultrafast lasers and agile photonic systems for communications, sensing, and signal processing."
        align: center
        background:
          image:
            filename: landing.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Research & Opportunities
        content: 'Our group focuses on microwave photonics, photonic integrated circuits, and multifunctional system design — from concept to lab validation. Students gain hands-on experience with cutting-edge tools, publish in top journals, and work across academia, industry, and government.'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Build, Publish, and Lead — Together
        content: 'At the Photonics Systems Research Group, you''ll join a collaborative, mentorship-driven environment focused on innovation and impact.'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: JOIN US
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '500px'
      # is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2000


  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: landing.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #       spacing:
  #         # Customize the section spacing. Order is top, right, bottom, left.
  #         padding: ['20px', '0', '200px', '0']

  - block: hero
    content:
      title: |
        Photonic Systems Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        'Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ul'
  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'


  # A section to display blog posts
  - block: collection
    id: section-1
    content:
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      # Display content from the `content/post/` folder
      filters:
        folders:
          - post
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
      
---
