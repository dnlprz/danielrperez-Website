---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: Proficient
          icon: r
          icon_pack: fab
        - name: STATA
          description: Proficient
          icon: stata
          icon_pack: fab
        - name: Python
          description: Proficient
          icon: python
          icon_pack: fab
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
        - title: Teaching Assistant
          company: UCLA
          company_url: ''
          company_logo: ''
          location: Los Angeles, CA
          date_start: '2019-09-01'
          date_end: ''
          description: |2-
              * Led TA sections for 20 Economics Classes teaching the following courses for groups of students ranging from 10 to 30.
                * Introductory Economics
                * Economics for a General Audience
                * Intermediate Microeconomics
                * Data Science for Economists
              * Wrote discussion notes and questions for homework and tests.
        - title: Research Assistant
          company: UCLA
          company_url: ''
          company_logo: ''
          location: Los Angeles, CA
          date_start: '2019-09-01'
          date_end:  '2021-12-01'
          description: |2-
            * Designed a survey distributed to over 100 students for an internal department study, analyzed the results of the survey, and wrote a report on experiences of transfer students studying economics.
            * In a separate project for a working paper on an Economic History topic, programmed a tool in Python designed to extract information from HTML pages, convert PDFs to CSV files and cleaned geographic and census data in STATA.
            * Developed a tool in ArcGIS that matches the geographic and census information to geographic shapefiles and distances.
            * Wrote appendix chapters detailing the cleaning procedure and all code related to the project.
        - title: Instructor
          company: UCLA
          company_url: ''
          company_logo: ''
          location: Los Angeles, CA
          date_start: '2022-06-01'
          date_end:  '2022-07-01'
          description: |2-
            * Taught Economics 101: Intermediate Microeconomics to a class of 25 undergrad students.
            * Created all class notes, slides, discussion notes, and questions for homework and tests.
            * Helped students with material in weekly office hours and through email.
        - title: Research Associate
          company: Federal Reserve Bank of Kansas City
          company_url: ''
          company_logo: ''
          location: Kansas City, MO
          date_start: '2016-06-01'
          date_end:  '2018-07-01'
          description: |2-
            * Prepared literature reviews, organized data and coded economic models for Community Affairs and Economic Department staff.
            * Penned internal and external publications for community organizations, academia, and public audiences.
            * Performed speaking engagements to roundtables and community groups on economic trends.
            * Coauthored three articles describing Low and Middle-Income Survey Results and Consumer Credit Report Analyses. Solo authored two articles focused on Mixed-Income housing and subprime auto lending. 
    design:
      columns: '3'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: ''
          date_start: '2021-06-01'
          description: ''
          organization: UCLA
          title: Graduate Summer Research Mentorship
          organization_url: 'https://grad.ucla.edu/funding/financial-aid/funding-for-continuing-students/graduate-summer-research-mentorship-program/'
        - date_end: '2022-09-01'
          date_start: '2018-09-01'
          description: ''
          organization: UCLA
          title: Cota-Robles Fellowship
          organization_url: 'https://grad.ucla.edu/funding/financial-aid/funding-for-continuing-students/graduate-summer-research-mentorship-program/'
    design:
      columns: '2'
  - block: collection
    content:
      title: Working Papers
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: danielrperez@g.ucla.edu
      address:
        street: Bunche Hall 8276, 315 Portola Plaza
        city: Los Angeles
        region: CA
        postcode: '90095'
        country: United States
        country_code: US
      directions: 
      office_hours:
        - 9 AM - 4 PM
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Follow Me on Twitter
          link: https://twitter.com/danrperez
        - icon: linkedin
          icon_pack: fab
          name: Follow Me on Linkedin
          link: https://www.linkedin.com/in/danielrperez/
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
