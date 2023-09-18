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
          company_logo: lnnano
          location: Campinas, São Paulo, Brazil
          date_start: '2023-03-01'
          date_end: ''
          description: Research Scientist of Theory and Data Science of Nanomaterials
        - title: Postdoctoral Fellow in Applied Physics
          company: Harvard University
          company_url: 'https://scholar.harvard.edu/gschleder/'
          company_logo: harvard
          location: Cambridge, Massachusetts
          date_start: '2021-07-01'
          date_end: '2023-02-28'
          description: |2-
              * Researcher in Simulations and Machine Learning of Quantum Materials and Twistronics. 
              * Taught two undergraduate courses: Phys20-Computational Physics; and AM10-Python for Scientists and Engineers.
    design:
      columns: '2'
  - block: accomplishments
    content:
      title: Highlights
      subtitle: ''
      text: ''
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `items` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Prêmio José Leite Lopes de Melhor Tese de Doutorado 2022 SBF
          certificate_url: 'https://sbfisica.org.br/v1/sbf/gabriel-ravanhani-schleder-vence-premio-professor-jose-leite-lopes-de-2022/'
          date_end: ''
          date_start: '2023-05-01'
          description: ''
          organization: Sociedade Brasileira de Física (SBF)
          organization_url: 'https://sbfisica.org.br/'
          url: 'https://sbfisica.org.br/v1/sbf/gabriel-ravanhani-schleder-vence-premio-professor-jose-leite-lopes-de-2022/'
        - title: INCT Materials Informatics
          certificate_url: 'https://inct-mi.pesquisa.ufabc.edu.br/discentes-do-inct-professor-gabriel-schleder/'
          date_end: ''
          date_start: '2023-04-01'
          description: The National Institute of Science, Technology and Innovation Program (INCT/CNPq) of Materials Informatics has been created! We have scholarships of all levels, from undergrad to postdoctoral levels.
          organization: INCT Materials Informatics
          organization_url: 'https://inct-mi.pesquisa.ufabc.edu.br/'
          url: 'https://inct-mi.pesquisa.ufabc.edu.br/discentes-do-inct-professor-gabriel-schleder/'
        - title: Prêmio CAPES de Tese de Doutorado 2022
          certificate_url: 'https://www.in.gov.br/en/web/dou/-/edital-n-11/2022-resultado-premio-capes-de-tese-edicao-2022-421902318'
          date_end: ''
          date_start: '2022-08-11'
          description: ''
          organization: CAPES
          organization_url: 'https://www.gov.br/capes/pt-br/assuntos/premios/premio-capes-de-tese/teses-premiadas/teses-premiadas-em-2022'
          url: 'https://www.gov.br/capes/pt-br/assuntos/premios/premio-capes-de-tese/teses-premiadas/teses-premiadas-em-2022'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
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
      title: Contact
      subtitle:
      text: |-
        Entre em contato!
      # Contact (add or remove contact options as necessary)
      email: gabriel.schleder (@) lnnano.cnpem.br
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: R. Giuseppe Máximo Scolfaro, 10000
        city: Campinas
        region: SP, Brazil
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
