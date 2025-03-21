---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Galileu Santos de Jesus
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: #
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
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
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
        - title: Software Engineering Researcher
          company: Universidade Federal de Pernambuco
          company_url: 'https://portal.cin.ufpe.br/'
          location: Recife - PE. Brazil.
          date_start: '2020-03-01'
          date_end: ''
          description: Software Engineering Researcher. Static Analisys. Semantic Conflicts.
        # - title:  Data Scientist
        #   company: Ministério da Saúde
        #   company_url: 'https://www.gov.br/saude/pt-br'
        #   location: Recife - PE. Brazil.
        #   date_start: '2023-03-01'
        #   date_end: ''
        #   description: Responsible for data analysis (Data Scientist) and prediction of health systems.
        - title: Head of Data Science
          company: LAIS - Laboratory of Technological Innovation in Health
          company_url: 'https://lais.huol.ufrn.br/'
          location: Recife - PE. Brazil.
          date_start: '2022-01-01'
          date_end: '2023-12-01'
          description: Responsible for data analysis (Data Scientist) and prediction of health systems. I worked on COVID-19 data analysis, helping in decision making in several states of Brazil. In addition to being the backend leader of some solutions made in Python using Django.
        # - title: Back end Developer
        #   company: Stone CO
        #   company_url: 'https://www.stone.com.br/'
        #   location: Rio de Janeiro - RJ. Brazil.
        #   date_start: '2022-10-01'
        #   date_end: '2023-03-01'
        #   description: I worked as a backend developer using the Elixir programming language. I assisted in the structuring of Payment Account Settlement, creating dashboards and reports to identify incidents.
        - title: Technology Director
          company: Ensinar Tecnologia
          company_url: 'https://ensinartecnologia.com.br/'
          location: Recife - PE. Brazil.
          date_start: '2019-03-01'
          date_end: '2022-08-01'
          description: I work as a technology and innovation manager in educational projects throughout Brazil. Working with companies like Google (implementation of the Google for Education program) and Microsoft (artificial intelligence project - AcademIA Microsoft). In addition to being responsible for all innovation and customer support management.
        - title: Professor
          company: Universidade Federal de Sergipe
          company_url: 'https://www.ufs.br/'
          location: Aracaju - SE. Brazil.
          date_start: '2018-03-01'
          date_end: '2020-03-31'
          description: Professor of Computer Science, in the languages area. Acting in subjects. Compilers; Formal Language; Functional Programming; Imperative Programming; Object Oriented Programming; Data Structure and Computer Fundamentals.
        - title: Technology Director
          company: COESI
          company_url: 'https://coesi.com.br/'
          location: Aracaju - SE. Brazil.
          date_start: '2016-02-01'
          date_end: '2020-03-01'
          description: I worked as a technology coordinator, helping to create robotics projects and teaching programming, as well as corporate solutions.
        - title: Computer Science Intern
          company: Ministério Público do Trabalho
          company_url: 'https://www.prt20.mpt.mp.br/'
          location: Aracaju - SE. Brazil.
          date_start: '2015-11-01'
          date_end: '2016-08-01'
          description: Responsible for the technology sector, I worked helping to create solutions and support the systems.
        - title: Computer Science Intern
          company: Correios
          company_url: 'https://www.correios.com.br/'
          location: Aracaju - SE. Brazil.
          date_start: '2015-04-01'
          date_end: '2015-10-01'
          description: Responsible for the technology sector, I worked helping to create solutions and support the systems.
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         icon: coursera
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         icon: edx
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         icon: datacamp
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
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
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
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
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
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
      title: Contact
      # subtitle:
      # text: |-
      # Contact (add or remove contact options as necessary)
      email: 'gsj@cin.ufpe.br'
      address:
        street: Av. Jornalista Anibal Fernandes, s/n.
        city: Recife
        region: PE
        postcode: '50740-560'
        country: Brazil
        country_code: BR
      # directions: Enter main Building A and take the stairs on the left to Office B-205, on the second floor.
      office_hours: No fixed office hours; please email or chat to book an appointment
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '-8.055278501385974'
        longitude: '-34.95138364801885'
      # contact_links:
        # - icon: twitter
        #   icon_pack: fab
        #   name: DM Me
        #   link: 'https://twitter.com/Twitter'
        # - icon: skype
        #   icon_pack: fab
        #   name: Skype Me
        #   link: 'skype:echo123?call'
        # - icon: video
        #   icon_pack: fas
        #   name: Zoom Me
        #   link: 'https://zoom.com'
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
