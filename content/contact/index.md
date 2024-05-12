---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contacto
      text: |-
        Laboratorio de Dinámicas y Estructuras Sociales de la Facultad del Hábitat 
      email: antonio.motilla@uaslp.mx
      phone: 4448262300-6868
      address:
        street: Niño Artillero 150
        city: San Luis Potosí
        region: San Luis Potosí 
        postcode: '94305'
        country: México
        country_code: México
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: Planta baja del edificio del Instituto de Investigación y Posgrado de la Facultad del Hábitat
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
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
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
