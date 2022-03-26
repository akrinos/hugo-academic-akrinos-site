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
  email: akrinos@mit.edu
  address:
    street: 266 Woods Hole Road MS #51
    city: Woods Hole
    region: MA
    postcode: '02543'
    country: United States
    country_code: US
  coordinates:
    latitude: '41.5265'
    longitude: '-70.6731'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: Twitter
      link: 'https://twitter.com/ariannakrinos'

design:
  columns: '2'
---
