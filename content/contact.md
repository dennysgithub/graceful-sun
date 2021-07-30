---
title: Kontakt
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |
      Varför inte inleda en diskussion och se vart det bär? 
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Namn
        default_value: Ditt namn
        is_required: true
      - input_type: email
        name: E-post
        label: E-post
        default_value: Din e-post
        is_required: true
      - input_type: select
        name: Ämne
        label: Ämne
        default_value: Vänligen välj
        options:
          - Rådgivning
          - Teknisk hjälp
          - Annat
      - input_type: textarea
        name: Meddelande
        label: Meddelande
        default_value: Ditt meddelande
      - input_type: checkbox
        name: consent
        label: >-
          Jag förstår att det här formuläret lagrar min inlämnade information så
          att jag kan kontaktas.
    submit_label: Skicka meddelande
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
