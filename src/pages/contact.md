---
title: Contact
sections:
  - section_id: contact
    type: section_contact
    background: gray
    title: Contact
    content: |-
      >
      **Registered Address:**  
      Harptec Ltd.  
      2 Woodberry Grove,  
      London, N12 0DR,  
      UK  
      >
      **Offshore Development Center**  
      Harptec Software Pvt. Ltd.  
      305, Concorde Building,  
      4th Floor,  
      Dr Rustom Cama Marg,   
      Alkapuri, Vadodara-390007.  
      Gujarat, India

      >Email: [ info@harptec.com ](https://) 

      >Landline: 0208 886 6354  
      >Mobile: 07751 720038
    form_id: contactForm
    form_fields:
      - input_type: text
        name: name
        label: Name
        is_required: true
      - input_type: email
        name: email
        label: Email
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Send Message
    hide_labels: true
template: landing
---
