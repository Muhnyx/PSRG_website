---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
        - title: Photonic Systems Research Group
          content: "Advancing Light-Based Technologies for Next-Generation Communication, Sensing, and Processing"
          align: center
          background:
            image:
              filename: landing.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: Our Research Areas
          content: 'Integrated Photonics • Microwave Photonics • mmWave Signal Processing • Novel Sensing • Artificial Intelligence, Autonomy, and Quantum System Enabling Technologies'
          align: left
          background:
            image:
              filename: contact.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
        - title: Enabling the Future of Connectivity
          content: "Our research supports high-speed, low-power systems for communications, sensing, and processing"
          align: left
          background:
            image:
              filename: welcome.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#666'
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
      interval: 3000

  - block: hero
    content:
      title: |
        Research Overview
      image:
        filename: lab.jpg
        filters:
          brightness: 0.55
      text: |
        <br>
        <strong>We advance photonic technologies for high-speed communications, sensing, and signal processing.</strong><br>
        Integrated photonics, microwave photonics, and ultrafast laser systems to enable scalable, energy-efficient solutions for future information networks and intelligent systems.
    design:
         # full-height hero
      background:
        overlay_color: '#000000'        # darkens busy image
        overlay_opacity: 0.45           # 45 % tint
      indicators: dots                  # slide dots instead of dashes
      
  - block: markdown
    content:
      # title: About the Group
      # subtitle: Advancing Photonic Systems for Communications, Sensing, and Intelligence
      text: |
        ---
        
        Our research interests span the development, integration, and characterization of low-noise, ultrafast lasers and advanced photonic systems and devices. We focus on leveraging photonic technologies to enable next-generation solutions for communications, sensing, and signal processing, bridging foundational optical science with system-level engineering to address the evolving demands of information and intelligent technologies.
        <br>

        **Principal Technology Areas**:
        - Millimeter-wave and microwave photonic systems, including fiber-wireless architectures and agile RF photonic links
        - Photonic integrated circuits for microwave photonics, with an emphasis on realizing agile, reconfigurable, and multifunctional systems
        - Ultrafast lasers and optical frequency comb development for advanced optical sources and signal generation 
        - Optical characterization and precision measurement techniques 
        - Numerical modeling, simulation, and data-driven analysis of complex photonic and physical systems

        <br>

        **Emerging Applications**:
        - Agile mmWave and sub-THz photonic signal processing for next-generation wireless and sensing networks
        - Enabling subsystems for quantum computing and photonic sensing platforms
        - Photonic systems supporting autonomy and artificial intelligence, including high-speed, low-latency signal processing
        
        - High-performance photonic components for secure, scalable, and energy-efficient networks

        <br>

        The Photonic Systems Research Group is committed to advancing the state of the art in photonic science and engineering to address real-world challenges and enable transformative technologies.

        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
      design:
        columns: '1'
        spacing:
        # order = top, right, bottom, left
          padding: ['0rem', '0', '4rem', '0']   # top gap gone, bottom stays 4 rem


# Commented sections moved below

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
# - block: collection
#  id: section-1
#   content:
#     text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
#     # Display content from the `content/post/` folder
#     filters:
#       folders:
#         - post
#   design:
#     # Choose how many columns the section has. Valid values: '1' or '2'.
#     columns: '1'
#     # Choose your content listing view - here we use the `showcase` view
#     view: showcase
#     # For the Showcase view, do you want to flip alternate rows?
#     flip_alt_rows: true

---
