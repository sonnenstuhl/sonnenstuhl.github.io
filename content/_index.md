---
# Leave the homepage title empty to use the site title
title: Daniel Sonnenstuhl
date: 2024-02-12
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: pubs
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: compact
  - block: portfolio
    id: projects
    content:
      title: Work in Progress
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: d.sonnenstuhl@uchicago.edu
      #appointment_url: 'https://calendly.com/sonnenstuhl'
      address:
        street: 1307 East 60th Street
        city: Chicago
        region: IL
        postcode: '60637'
        country: United States
        country_code: US
      #office_hours:
       # - 'Office Hours:'
       # - 'Thursday 2:00pm to 3:00pm'
       #- 'Friday 9:30am to 10:30am'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
