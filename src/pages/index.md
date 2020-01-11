---
title: Fresh Donuts
sidebar:
  entries:
  - title: Welcome
    url: "#intro"
    is_primary: true
  - title: Who we are
    url: "#one"
    is_primary: false
  - title: What we do
    url: "#two"
    is_primary: false
  - title: Get in touch
    url: "#three"
    is_primary: false
sections:
- type: intro
  template: intro
  title: Andrew's Pastries
  subtitle: Marion's only fresh donuts, a locally owned and operated bakery.
  section_id: intro
  background_style: style1
  actions:
  - label: Learn more
    url: "#one"
    is_scrolly: true
    is_primary: false
  component: Intro
- type: spotlights
  template: spotlights
  title: About Us
  section_id: one
  background_style: style2
  component: Spotlights
- type: features
  template: features
  title: Menu
  subtitle: All items are made to order and bulk orders require advance notice.
  section_id: two
  background_style: style3
  features_list:
  - title: Donuts
    text: Our donuts are made at our bakery overnight so that they are always fresh.
    image: donut.png
  - title: Cookies
    text: Handmade cookies of all types.
    image: cookies.jpg
  - title: Cakes
    text: Cakes for all occasions and seasons
    image: cakes.jpg
  
  actions:
  - label: Learn more
    url: "/generic"
    is_scrolly: false
    is_primary: false
  component: Features
- type: contact
  template: contact
  title: Get in touch
  text: Phasellus convallis elit id ullamcorper pulvinar. Duis aliquam turpis mauris,
    eu ultricies erat malesuada quis. Aliquam dapibus, lacus eget hendrerit bibendum,
    urna est aliquam sem, sit amet imperdiet est velit quis lorem.
  section_id: three
  background_style: style1
  contact_list:
  - title: Address
    text: |-
      1282 Delaware Ave,
      Marion, Ohio 43302
    url: ''
  - title: Email
    text: andrew@andrewspastries.us
    url: "mailto:andrew@andrewspastries.us"
  - title: Phone
    text: "(740) 387-3830"
    url: 'callto:(740)3873830'
  social:
    title: Social
    social_icons:
    - title: Facebook
      icon: fa-facebook
      url: "https://www.facebook.com/andrewspastries/"
    - title: Instagram
      icon: fa-instagram
      url: "https://www.instagram.com/andrews_pastries/"
  component: Contact
menus:
  main:
    title: Home
    weight: 1
template: home

---
