---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Protistology Nordics Society
      text: An association of scientists interested in the genetics, cell biology, ecology, and evolution of protists.
      primary_action:
        text: Become a member
        url: https://nettskjema.no/a/378661
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: Diatoms.jpeg
          filters:
            brightness: 0.5
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Welcome to Protistology Nordics
          text: The Protistology Nordics Society (PiN) is an association of scientists based in Nordics countries and interested in microbial eukaryotes, or protists. 
          feature_icon: check
          features:
            - "Membership at no cost!"
            - "One scientific meeting a year to facilitate vibrant discussions about the latest research in protistology, social interaction, and networking"
            - "Encouraging the development of young scientists"
          # Upload image to `assets/media/` and reference the filename here
          image: random.png
          button:
            text: Become a member!
            url: https://nettskjema.no/a/378661
---
