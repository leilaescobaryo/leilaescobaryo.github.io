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
      # To show a "Download CV" button, upload your CV to `static/uploads/resume.pdf`
      # and uncomment the lines below.
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
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
      title: 'Research focus'
      subtitle: ''
      text: |-
        My work sits at the intersection of **primate ecology** and **tropical forest conservation**.
        For my undergraduate thesis I studied **seed dispersal by neotropical primates** in Peru, a key
        ecological process through which primates help regenerate Amazonian forests.

        Through field placements in the Peruvian Amazon and a research internship at Duke University,
        I have combined behavioural field methods with laboratory and molecular approaches. I am now
        looking for graduate and research opportunities in primate ecology, conservation genetics and
        socio-ecological systems.

        [Read more about my research →](research/)
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
        I am open to collaborations, field projects and graduate opportunities.
        Feel free to write to me at [leilaescobaryomona@gmail.com](mailto:leilaescobaryomona@gmail.com)
        or connect on [LinkedIn](https://www.linkedin.com/in/leila-escobar/).
    design:
      columns: '1'
---
