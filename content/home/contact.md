---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  email: rebecca.yyyy@outlook.com
  phone: (+61) 424099400 
  address:
    street: 231 Harbour Esplanade
    city: Melbourne
    region: VIC
    postcode: 3008
    country: Australia
    country_code: AU
  office_hours:
    - 'Monday 09:00 to 13:00 (GMT+10)'
  appointment_url: 'https://outlook.live.com/owa/calendar/00000000-0000-0000-0000-000000000000/ed35db51-0a6f-482f-b762-d27ab00c19e0/cid-B896B5BA07E05C04/index.html'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Becca_YY'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: https://unimelb.zoom.us/j/6843568748?pwd=TFlZd2hONmgrZzNvL2s1ZXQ5VnJldz09

design:
  columns: '2'
---
