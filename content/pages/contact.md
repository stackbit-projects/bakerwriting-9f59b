---
title: Contact
sections:
  - type: hero_section
    title: Let's Talk ...
    align: center
    padding_top: small
    padding_bottom: none
    has_border: false
    background_color: primary
    content: |
      Tell me what you need. I will get back to you. Promise.
  - title_align: left
    content_align: left
    form_position: bottom
    form_width: fifty
    form_layout: stacked
    enable_card: true
    form_id: Contact Me
    form_action: netlify
    form_fields:
      - input_type: text
        label: Name
        options: []
        is_required: true
        type: form_field
        name: First and Last
      - input_type: email
        name: Email
        label: Email
        options: []
        is_required: true
        type: form_field
      - input_type: textarea
        name: Message
        label: Message
        options: []
        is_required: true
        type: form_field
    align_vert: top
    padding_top: small
    padding_bottom: small
    has_border: false
    background_color: secondary
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: form_section
    submit_label: Contact Me
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
