---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '5rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: 'About me'
        education: 'Education'
        interests: 'Interests'
    design:
      # Gradient Mesh background adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true
      name:
        size: sm # Options: xs, sm, md, lg (default), xl
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: markdown
    id: research
    content:
      title: 'Current work'
      subtitle: ''
      text: |-
        **Primate reintroduction — Ikama Peru Wildlife Rescue Center (2026–present).**
        As consultant biologist and project lead, I assess whether an Amazonian site in Loreto
        is suitable for reintroducing primates confiscated from the illegal wildlife trade,
        combining transect surveys, botanical plots and community consultation.

        **Seed dispersal by endemic primates — undergraduate thesis.**
        With Neotropical Primate Conservation and the Lab of Socio-ecological Systems (UPCH),
        I study patterns and rates of seed dispersal by the yellow-tailed woolly monkey
        (*Lagothrix flavicauda*) and the Andean night monkey (*Aotus miconax*) in the montane
        forests of Amazonas, Peru.

        [More about my research →](research/)
    design:
      columns: '1'

  - block: resume-awards
    id: awards
    content:
      title: Awards & Fellowships
      username: me

  - block: markdown
    id: contact
    content:
      title: 'Get in touch'
      subtitle: ''
      text: |-
        I am open to collaborations, fieldwork and graduate opportunities in primatology
        and conservation. Write to me at [leilaescobaryomona@gmail.com](mailto:leilaescobaryomona@gmail.com)
        or connect on [LinkedIn](https://www.linkedin.com/in/leila-escobar/).
    design:
      columns: '1'
---
