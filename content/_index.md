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
          icon: r-project
          icon_pack: fab
        - name: STATA
          description: Proficient
          icon: stata
          icon_pack: fas
        - name: Python
          description: Proficient
          icon: python
          icon_pack: fas
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
              Taught, prepared discussion notes and questions for homework and exams, and graded exams for the following courses:  

              * Introductory Economics
              * Economics for a General Audience
              * Intermediate Microeconomics
              * Data Science for Economists
        - title: Research Assistant
          company: UCLA
          company_url: ''
          company_logo: ''
          location: Los Angeles, CA
          date_start: '2019-09-01'
          date_end:  '2021-12-01'
          description: |2-
             Provided data analysis and wrote report on experiences of transfer students studying economics. Created and managed survey for this project. For a separate project, coded programs designed to extract information from HTML pages, convert PDFs to other types of files and clean various types of data. Additionally, coded a program that matches this information to geographic shapefiles and distances.
        - title: Instructor
          company: UCLA
          company_url: ''
          company_logo: ''
          location: Los Angeles, CA
          date_start: '2022-06-01'
          date_end:  '2022-07-01'
          description: |2-
              Taught Intermediate Microeconomics to a class of 25 undergrad students. Created all class notes, slides, discussion notes, and questions for homeworks and tests. Graded all homeworks and tests. Held office hours for students and helped students struggling with material.
        - title: Research Associate
          company: Federal Reserve Bank of Kansas City
          company_url: ''
          company_logo: ''
          location: Kansas City, MO
          date_start: '2016-06-01'
          date_end:  '2018-07-01'
          description: |2-
              Created literary reviews, managed data and coded economic models for Community Affairs and Economic Department staff. Wrote internal and external publications for community organizations, academia and public audiences. Performed speaking engagements to roundtables and community groups on economic trends.        
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
      title: How Much Do Consumers Care About Discontinued and New Products? A Case Study of the MillerCoors Merger
      text: A concern among regulators during a merger or acquisition is
      potential price increases due to the increase in market power. However, there
      has been increased concern for the non-price effects of mergers, such as the
      effects on product variety. Prior works in the literature consider these
      effects, yet do not consider how they may compare. This paper bridges this gap
      by comparing the welfare effects of product variety changes would be in
      relation to the welfare effects of price in the context of the MillerCoors
      merger. The merger's clear product definition, decision to merge unrelated to
      product variety, well measured consumer surplus effects, evidence of price
      coordination and involvement of two large competitors with heterogeneous
      products make this an ideal setting to measure these effects. I first test if
      the merger had any effect on product variety directly, and find product
      variety fell for Miller and Coors, but increased compared to its competitors.
      I then use a random coefficient nested logit model and estimate demand for the
      MillerCoors merger in the post-merger period, expanding on work from Miller
      and Weinberg (2017). I test how much consumers value products that were added
      and dropped after the merger with two basic counterfactuals, and find consumer
      surplus declines by at most a percent when new products are dropped after the
      merger. This is 23% of the consumer welfare effects of coordinated pricing
      found in Miller and Weinberg (2017). 
      filters:
        folders:
          - publication
        exclude_featured: false
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
