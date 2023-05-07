Skip to content
Search or jump to…
Pull requests
Issues
Codespaces
Marketplace
Explore
 
@gschleder 
gschleder
/
starter-hugo-academic
Public
Cannot fork because you own this repository and are not a member of any organizations.
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
Beta Try the new code view
starter-hugo-academic/content/_index.md
@gschleder
gschleder Update _index.md
Latest commit 03fac59 2 hours ago
 History
 1 contributor
129 lines (128 sloc)  3.83 KB
 

---
# Leave the homepage title empty to use the site title
title: Gabriel R. Schleder
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
        - title: Research Scientist
          company: Brazilian Nanotechnology National Laboratory (LNNano/CNPEM)
          company_url: 'https://lnnano.cnpem.br/'
          company_logo: org-gc
          location: Campinas, São Paulo, Brazil
          date_start: '2023-03-01'
          date_end: ''
          description: Research Scientist of Theory and Data Science of Nanomaterials
        - title: Postdoctoral Fellow in Applied Physics
          company: Harvard University
          company_url: 'https://scholar.harvard.edu/gschleder/'
          company_logo: org-x
          location: Cambridge, Massachusetts
          date_start: '2021-07-01'
          date_end: '2023-02-28'
          description: |2-
              * Researcher in Simulations and Machine Learning of Quantum Materials and Twistronics. 
              * Taught two undergraduate courses: Phys20-Computational Physics; and AM10-Python for Scientists and Engineers.
    design:
      columns: '2'
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
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
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: gabriel.schleder (@) lnnano.cnpem.br
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: R. Giuseppe Máximo Scolfaro, 10000
        city: Campinas
        region: SP
        postcode: '13083-970'
        country: Brazil
        country_code: BR
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      # contact_links:
      # Automatically link email and phone or display as text?
      autolink: false
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
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
starter-hugo-academic/_index.md at 03fac593f32c02e7cc506ebd154cdd44c38fa131 · gschleder/starter-hugo-academic
