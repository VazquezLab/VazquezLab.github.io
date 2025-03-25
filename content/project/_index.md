---
title: Projects
type: landing

sections:
  - block: portfolio
    id: projects
    content:
      title: Projects
      text: "The Vazquez Lab is generally focused on questions around the evolution of longevity in mammals, with a special interest in humans, bats, and cetaceans. These projects use a combination of functional genomics (gene expression, chromatin accessibility, and epigenetic markers); population genomics (both traditional and pangenome-based); evolutionary genomics (e.g: selection scans and trait/molecular evolution); and molecular and cellular biology (e.g: high-throughput screens, genetic manipulation, and microscopy). Additionally, the lab also collaborates closely with other groups in Penn State and abroad on a number of related topics. Beyond these topics, we encourage all interested students and researchers to propose their own project ideas!"
      filters:
        # Folders to display content from
        folders:
          - project
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
        - name: Pangenomics
          tag: Pangenomics
        - name: Evolutionary Medicine
          tag: Evolutionary Medicine
        - name: Comparative Biology
          tag: Comparative Biology
        - name: Functional Genomics
          tag: Functional Genomics
        - name: Longevity
          tag: Longevity
        - name: DNA Damage and Repair
          tag: DNA Damage and Repair
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
---
