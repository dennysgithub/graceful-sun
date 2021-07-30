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
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
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
