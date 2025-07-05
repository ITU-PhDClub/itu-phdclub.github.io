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
  
  - block: markdown
    content:
      title: Documents
      text: | 
        PhD guide for settling in [here](https://ituniversity.sharepoint.com/:w:/s/PhDClub-Committee/EZGVwblzntFLpmQL8puSTcIBxisPNLE6KdagLXZ_3Rie0A)
        
        Our constitution can be found here <a href="/uploads/PhD%20Club%20Constitution.pdf" target="_blank" rel="noopener">PhD Club Constitution</a>
    design:
      columns: '2'

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

  - block: markdown
    content:
      text: '{{< figure src="pand.png" link="https://phddenmark.dk">}}'
---