---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ""
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: workingpapers
    content:
      title: Working Papers
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - papers
#        author: ""
#        category: ""
#        tag: ""
#        publication_type: ""
#        featured_only: false
        exclude_featured: true
#        exclude_future: false
#        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
#      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
#      sort_ascending: false
    design:
      # Choose a listing view
      view: Citation
      # Choose single or dual column layout
      columns: '2'

  - block: collection
    id: ongoingprojects
    content:
      title: Ongoing Projects
      count: 0
      sort_by: Weight
      sort_ascending: true
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - ongoingprojects
#        author: ""
#        category: ""
#        tag: ""
#        publication_type: ""
#        featured_only: false
        exclude_featured: true
#        exclude_future: false
#        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
#      offset: 0
      # Field to sort by, such as Date or Title
#      sort_by: 'Date'
#      sort_ascending: false
    design:
      # Choose a listing view
      view: citation
      # Choose single or dual column layout
      columns: '2'

  - block: collection
    id: policy
    content:
      title: Policy Reports & Briefs
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - policy
        exclude_featured: true
    design:
      # Choose a listing view
      view: citation
      # Choose single or dual column layout
      columns: '2'



---
