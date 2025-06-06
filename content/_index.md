---
# Leave the homepage title empty to use the site title
title:
date: 2024-07-06
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: tag_cloud
    content:
      title: Topics
      subtitle: ""
      text: ""
      # text: My work has touched on the following topics
      # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 10
    design:
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 0.7
      font_size_max: 2.0
  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: portfolio
    id: projects
    content:
      title: Projects
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
      buttons:
        - name: All
          tag: '*'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 3 years experience
          icon: r-project
          icon_pack: fab
        - name: Python
          description: 4 years experience
          icon: python
          icon_pack: fab
        - name: SQL
          description: 1 year experience
          icon: database
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Quantitative Researcher
          company: Quantbot Technologies LP
          location: NY, New York
          date_start: '2024-06-16'
        - title: Intern
          company: Quantbot Technologies LP
          location: NY, New York
          date_start: '2023-05-25'
          date_end: '2023-08-25'
          description: ''
        - title: Research Intern
          company: IBM Research
          location: Cambridge, MA
          date_start: '2022-06-01'
          date_end: '2022-08-22'
          description: ''
        - title: Research Intern
          company: IBM Research
          location: Cambridge, MA
          date_start: '2019-06-20'
          date_end: '2019-08-23'
          description: ''
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_start: '2022-05-26'
          organization: New England Statistical Society
          title: Student Poster Award
        - date_start: '2021-10-14'
          organization: Neural Information Processing Systems
          title: Outstanding Reviewer Award
        - date_start: '2018-10-04'
          organization: Neural Information Processing Systems
          title: Student Travel Award
    design:
      columns: '2'
  - block: features
    content:
        title: 'Professional Services'
        items:
          - name: NeurIPS Reviewer
            description: "2021, 2022"
          - name: AISTATS Reviewer
            description: "2022"
          - name: TMLR Reviewer
            description: "2022, 2023"
---
