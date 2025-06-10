---
title: 'Home'
date: 2025-06-09
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: The Sapphire
      text: A pre school
      primary_action:
        text: Get Admission
        url: blog/admissions-open/
        icon: rocket-launch
      secondary_action:
        text: Contact
        url: contact/
      announcement:
        text: "Announcing the release of website."
        link:
          text: "Read more"
          url: "/blog/website-release/"
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
          filename: thesapphireschool-wo-text.png
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "1000+"
          description: |
            Students graduated
        - statistic: "25+"
          description: |
            Years of teaching experience
        - statistic: "14+"
          description: |
            Years of The Sapphire
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: about
    content:
      title: About the school
      text: What is offered
      items:
        - name: Easy admission
          icon: sparkles
          description: Easy admission within 1 day!
        - name: Highly Rated
          icon: star
          description: Rated 5-stars by the parents
        - name: Building child's future
          icon: rectangle-group
          description: Build your child's future with trusted school
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Nurture your kids education
          text: As easy as 1, 2, 3!
          feature_icon: check
          features:
            - "Experienced teachers"
            - "Active games"
            - "Mental match"
          # Upload image to `assets/media/` and reference the filename here
          image: sketching.jpg
          button:
            text: Get Admission
            url: blog/admissions-open/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-card
    content:
      title: Get your kid enrolled
      text: As easy as 1, 2, 3!
      button:
        text: Get Admission
        url: blog/admissions-open/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
        
---
