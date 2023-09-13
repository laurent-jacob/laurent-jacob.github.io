---
# Leave the homepage title empty to use the site title
title:
date: 2023-09-11
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
        exclude_tags: ['hidden']
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
       - name: All
         tag: '*'
       - name: Deep Learning
         tag: Deep Learning
       - name: GWAS
         tag: GWAS
      # Field to sort by, such as Date or Title
      sort_by: order
      sort_ascending: false
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  # Customized the people block at layouts/partials/blocks/people.html
  - block: people
    id: people
    content:
      title: People
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Ph.D. students
        - Postdocs and engineers
        - MSc interns
      sort_by: Params.starting_date
      sort_ascending: false
      text: I am grateful to all the people I co-advised. Most of the work featured on this website is theirs.
    design:
      # Show user's social networking links? (true/false)
      show_social: false
      # Show user's interests? (true/false)
      show_interests: true
      # Show user's role?
      show_role: true
      # Show user's organizations/affiliations?
      show_organizations: true
  - block: collection
    id: publications
    content:
      title: Some recent publications
      text: See my [Google Scholar profile](https://scholar.google.com/citations?hl=fr&user=54bOCmQAAAAJ) for a complete list.  
      filters:
        folders:
          - publication
        exclude_featured: true
        exclude_tags: [skip]
    design:
      columns: '2'
      view: list
  - block: markdown
    id: community
    content:
      title: Community
      text: |
        I was involved in the organization of several scientific events:
        - [LEGO](https://gt-lego.cnrs.fr/), a French working group on machine learning for genomics. We organize national meetings to gather researchers interested in this topic.
        - [MLMG2022](https://mlmg2022.github.io/), an [ECML](https://2022.ecmlpkdd.org/index.html) workshop on machine learning for microbial genomics.
        - I co-chaired the Systems Biology and Networks track of the [2021 ISMB conference](https://www.iscb.org/ismbeccb2021).
        - The 2020 [prospective meeting](https://databio.sciencesconf.org/) on data science, AI and biology from the biology and computer science institutes of CNRS.
    design:
      columns: '1'
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
---
