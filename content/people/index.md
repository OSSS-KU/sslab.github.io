---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    content:
      title: Team members
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Faculty
          - Postdoc
          - Graduate students
          - Undergraduate interns
          - Alumni
      # sort_by: Params.last_name
      sort_by: Params.priority
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
---