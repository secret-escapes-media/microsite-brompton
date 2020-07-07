---
layout: competition
id: competition
permalink: /
nav: false

title: Compet&shy;ition
long-title: >
  Win a two-night trip to the Lake&nbsp;District with a whole year of free Brompton hire!
meta-title: Win a two-night trip to the Lake District with a whole year of free Brompton hire!
description: Win a two-night trip to the Lake District with a whole year of free Brompton hire! We’ll send you to the gorgeous Belsfield Hotel, a grand period property set on the shimmering shores of Windermere, surrounded by epic cycle routes and scenery. Enjoy a hearty breakfast each morning, before you pedal power your way around the irresistible Lakeland scenes.
enter-cta: Enter Now

competition-form:
  id: comp
  post-url: "https://getform.io/f/53e4999e-2b6f-4ae4-866d-82604aac814b"
  expiry-date: 2020-12-01
  fields:
    - id: name
      type: text
      label: Name
      required: true
    - id: email
      type: email
      label: Email
      required: true
    - id: qualify
      type: radio
      label: Are you a UK resident and over the age of 18?
      required: true
      options:
        - id: qualify-true
          label: 'Yes'
          value: 'yes'
        - id: qualify-false
          label: 'No'
          value: 'no'
          invalid: true
    - id: opt-in
      type: radio
      label: Would you like to receive emails from Brompton Bike Hire?
      required: true
      options:
        - id: opt-in-true
          label: 'Yes'
          value: 'yes'
        - id: opt-in-false
          label: 'No'
          value: 'no'
  submit: Submit Entry
  terms: >
    By submitting your entry, you agree to the <a href="#" class="js-open-modal link--underlined" data-open-modal="competition-terms">terms and conditions</a> of this competition
---