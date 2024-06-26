---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-01-07
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: skills
  #   content:
  #     title: Skills
  #     text: ''
  #     # Choose a user to display skills from (a folder name within `content/authors/`)
  #     username: admin
  #   design:
  #     columns: '1'
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Robotics Engineer
          company: COBOD International
          company_url: 'https://cobod.com/'
          company_logo: cobod
          location: Copenhagen, Denmark
          date_start: '2023-05-01'
          date_end: ''
          description: |2-
              * Skills: Robot Operating System (ROS), ROS2, ros2_control, Robot assembly, RoboDK, C++, Python, CMake, Qt, Ubuntu, git, RViz, Gazebo, SOLIDWORKS.
        - title: Robotics Engineer - Student Assistant
          company: COBOD International
          company_url: 'https://cobod.com/'
          company_logo: cobod
          location: Copenhagen, Denmark
          date_start: '2022-10-01'
          date_end: '2023-05-01'
          description: |2-
              * Awarded student worker of the year 2023.
              * Built and programmed robotic solutions to redefine the construction industry.
              * Skills: Robot Operating System (ROS), ROS2, Robot assembly, RoboDK, C++, Python, CMake, Qt, Ubuntu, git, RViz, Gazebo, SOLIDWORKS.
        - title: PLC Programmer - BSc Thesis Project
          company: LIAM LAB
          company_url: 'https://www.linkedin.com/company/consorzio-liam/?originalSubdomain=it'
          company_logo: liamlab
          location: Bologna, Italy
          date_start: '2021-02-01'
          date_end: '2021-10-01'
          description: |2-
              * Developed an algorithm for phasing and buffering e-commerce items.
              * Tested and debugged the solution on a digital twin of a packaging machine.
              * Skills: Beckhoff TWINCAT3, ISG-Virtuos, CoDeSys, IEC 61131-3.
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: '2023-12-31'
          date_start: '2023-01-01'
          description: Awarded to the best performer student worker at COBOD International
          icon: cobod
          organization: COBOD International
          organization_url: https://www.edx.org
          title: 'Student Worker of the Year 2023'
        - certificate_url: https://courses.edx.org/certificates/c3133303935c440abc8f19278e750823
          date_end: ''
          date_start: '2022-01-01'
          description: 'Completed the 15-weeks online course "AMRx: Autonomous Mobile Robots" organized by ETH Zürich and edX.'
          icon: edx
          organization: ETH Zürich & edX
          organization_url: https://www.edx.org/learn/autonomous-robotics/eth-zurich-autonomous-mobile-robots
          title: 'AMRx: Autonomous Mobile Robots'
          url: 'https://www.edx.org/learn/autonomous-robotics/eth-zurich-autonomous-mobile-robots'
        - certificate_url: uploads/TOEFL_score.pdf
          date_end: ''
          date_start: '2021-03-01'
          description: 'Score: 102'
          icon: toefl
          organization: ETS
          organization_url: https://www.ets.org/toefl/test-takers/ibt.html
          title: 'TOEFL iBT'
        - certificate_url: ''
          date_end: ''
          date_start: '2019-06-01'
          description: 'Full scholarship awarded to 10 students for taking part in a double degree program with Tongji University, covering expenses during the one year spent in Shanghai, China.'
          icon: unibo
          organization: University of Bologna
          organization_url: https://www.unibo.it/en
          title: 'AlmaTong Scholarship'
          url: 'https://corsi.unibo.it/2cycle/AutomationEngineering/almatong-bachelor-programme'
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
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
        - name: Mobile Robots
          tag: Mobile Robots
        - name: Motion Planning
          tag: Motion Planning
        - name: Automation
          tag: Automation
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Get in touch
      subtitle: Feel free to contact me :)
      # Contact (add or remove contact options as necessary)
      email: filippo.bosi24@gmail.com
      # phone: 
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # coordinates:
      #   latitude: '37.4275'
      #   longitude: '-122.1697' 
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: 'https://www.linkedin.com/in/filippo-bosi/'
        - icon: github
          icon_pack: fab
          name: GitHub
          link: https://github.com/filippo-bosi
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
