---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Clinic Information
      text: |-
        New patient appointments are made by referral only. 
      email: info@sykes-ohns.ca
      phone: 416 848 2236
      fax: 416 281 0553
      address:
        street: 666 St. Clair Ave West, Suite 101
        city: Toronto
        region: ON
        postcode: 'M4C 1B1'
        country: Canada
        country_code: CA
      coordinates:
        latitude: '43.682011'
        longitude: '-79.425026'
      directions: Residential street and Green P parking available nearby.
      office_hours:
        - 'Monday-Wednesday 08:00 to 15:00'
   
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
    #  form:
    #    provider: netlify
    #    formspree:
    #      id:
    #    netlify:
    #      # Enable CAPTCHA challenge to reduce spam?
    #      captcha: false
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
