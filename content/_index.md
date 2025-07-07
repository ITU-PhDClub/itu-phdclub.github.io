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
        We are a PhD society at the IT University of Copenhagen (ITU) with a mission to connect junior researchers from different research areas, backgrounds, and cultures through various events. We provide a platform for PhD students to build a social network, share experiences, and help each other out.
      css_class: justify-text
  
  - block: markdown
    content:
      title: About Us
      text: | 
        The ITU PhD Club was founded in 2023 by a group of enthusiastic PhD students who aimed to build a more active and connected PhD community at ITU. Following a series of initiatives, the society held its founding meeting on 24 November 2023, adopted an official <a href="/uploads/PhD%20Club%20Constitution.pdf" target="_blank" rel="noopener">constitution</a>, and appointed the first board of the PhD Club.
        
        Since then, the club has organized a variety of events -- from academic talks to social events outside of the university. As an advocate for the interests and well-being of PhD students at ITU, the club is often also involved in making changes within the university as well as on a national level through its membership in PAND (the PhD Association Network of Denmark). To smoothen the process of settling in at ITU, the PhD Club has also put together a [helpful guide for it](https://ituniversity.sharepoint.com/:w:/s/PhDClub-Committee/EZGVwblzntFLpmQL8puSTcIBxisPNLE6KdagLXZ_3Rie0A).

    design:
      columns: "1"
      css_class: justify-text
      background:
        image:
          filename: /background.jpg
          filters:
            brightness: 0.3
          parallax: true
          position: center
          size: cover

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