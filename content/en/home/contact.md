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
      captcha: true

  # Contact details (edit or remove options as required)
  email: info@ywamsendai.jp
  coordinates:
    latitude: '38.2728'
    longitude: '140.761462'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/ywamsendai'
    - icon: discord
      icon_pack: fab
      name: Chat on Discord
      link: 'https://discord.gg/djmCF4DBaV'
    - icon: telegram
      icon_pack: fab
      name: Chat on Telegram
      link: 'https://t.me/joinchat/O4PX5BsUYLG64lCazgT8Ng'
    - icon: comments
      icon_pack: fas
      name: Chat on Element
      link: 'https://app.element.io/#/group/+ywamsendai:matrix.org'
    - icon: facebook
      icon_pack: fab
      name: Message on Facebook
      link: 'https://facebook.com/ywamsendai'
    - icon: youtube
      icon_pack: fab
      name: Check out our videos
      link: 'https://www.youtube.com/channel/UCH4EWvQQGs2VEtYtH_Pr_lw'
    - icon: instagram
      icon_pack: fab
      name: Check out our pics
      link: 'https://instagram.com/ywamsendai'

design:
  columns: '2'
---
