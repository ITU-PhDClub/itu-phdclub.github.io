---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title:
      image:
        filename: welcome.svg
      text: |
        Our mission is to connect PhD students from different research areas, backgrounds, and cultures through various events. We provide a platform for PhD students to build a social network, share experiences, and help each other out!
  
  - block: collection
    content: 
      title: Upcoming Events
      count: 3
      filters:
        author: ''
        category: ''
        folders: 
        - event
        exclude_past: true
      sort_by: "Date"
      sort_ascending: true
    design:
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '1'

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Board Members
      sort_by: Params.last_name
      sort_ascending: true
    design:
      # Show user's social networking links? (true/false)
      show_social: true
      # Show user's interests? (true/false)
      show_interests: false
      # Show user's role?
      show_role: true
      # Show user's organizations/affiliations?
      show_organizations: true

---