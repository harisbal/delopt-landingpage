---
title: "Home"
date: 2024-10-18
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Optimize your deliveries
      text: Simple, fast and scalable API for optimizing delivery routes in real-time
      primary_action:
        text: Try it!
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: https://docs.hugoblox.com
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
  # - block: stats
  #   content:
  #     items:
  #       - statistic: "1M+"
  #         description: |
  #           Websites built  
  #           with Hugo Blox
  #       - statistic: "10k+"
  #         description: |
  #           GitHub stars  
  #           since 2016
  #       - statistic: "3k+"
  #         description: |
  #           Discord community  
  #           for support
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Features
      text: Build your site with blocks 🧱
      items:
        - name: Simple
          icon: custom/pinch-easy-icon
          description: Seamless integration to make the delivery process simple and effortless​.
        - name: Fast
          icon: custom/thunder-icon
          description: Keep your dispatch plan up to date and make sure that every order will arrive on time.
        - name: Scalable
          icon: custom/flexibility-scalability-icon
          description: Dispatch from a single to hundreds of orders using the same infrastructure.
        - name: Efficient
          icon: custom/coin-stack-decrease-icon
          description: Reduce your operational costs through better fleet management
        - name: Parametrizable
          icon: custom/control-panel-icon
          description: Constraint the dispatches based on your own requirements
        - name: Reliable
          icon: custom/handshake-icon
          description: Our cloud-based solution guarantees 99.9% availability
  - block: cta-image-paragraph
    id: demo
    content:
      items:
        - title: Try delopt!
          text: As easy as 1, 2, 3!
          feature_icon: check
          features:
            - "Assess multiple dispatch scenarios"
            - "Verify performance and quality"
            - "Assure it covers your needs"
          # Upload image to `assets/media/` and reference the filename here
          image: delopt-example.png
          button:
            text: Get Started
            url: https://hugoblox.com/templates/
        # - title: Large Community
        #   text: Join our large community on Discord - ask questions and get live responses
        #   feature_icon: bolt
        #   features:
        #     - "Dedicated support channel"
        #     - "3,000+ users on Discord"
        #     - "Share your site and get feedback"
        #   # Upload image to `assets/media/` and reference the filename here
        #   image: coffee.jpg
        #   button:
        #     text: Join Discord
        #     url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  # - block: testimonials
  #   content:
  #     title: ""
  #     text: ""
  #     items:
  #       - name: "Hugo Smith"
  #         role: "Marketing Executive at X"
  #         # Upload image to `assets/media/` and reference the filename here
  #         image: "testimonial-1.jpg"
  #         text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
  #   design:
  #     spacing:
  #       # Reduce bottom spacing so the testimonial appears vertically centered between sections
  #       padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Optimise your deliveries
      text: Say goodbye to delayed deliveries and customer complaints 
      button:
        text: Contact Us!
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
