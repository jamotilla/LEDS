---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Laboratorio de 
        Dinámicas y Estructuras Sociales
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        El **Laboratorio de Dinámicas y Estructuras Sociales (LEDS)** de la Facultad del Hábitat de la UASLP, tiene como objetivo principal generar conocimiento de vanguardia que contribuya a comprender la estructura y dinámica de las sociedades a lo largo del tiempo, con especial atención en el surgimiento, desarrollo y crisis de la modernidad.
  
  - block: collection
    content:
      title: Últimas noticias
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
