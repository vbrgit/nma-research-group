---
title: Parallelizing a hybrid finite element-boundary integral method for the analysis
  of scattering and radiation of electromagnetic waves

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- R. Durán Díaz
- R. Rico
- L.E. García-Castillo
- I. Gómez-Revuelto
- J.A. Acebrón
- I. Martínez-Fernández

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2010-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2023-11-22T10:36:46.665804Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Finite Elements in Analysis and Design*'
publication_short: ''

doi: 10.1016/j.finel.2010.03.004

abstract: 'This paper presents the practical experience of parallelizing a simulator
  of general scattering and radiation electromagnetic problems. The simulator stems
  from an existing sequential simulator in the frequency domain, which is based on
  a finite element analysis. After the analysis of a test case, two steps were carried
  out: first, a \"hand-crafted\" code parallelization of a convolution-type operation
  was developed within the kernel of the simulator. Second, the sequential HSL library,
  used in the existing simulator, was replaced by the parallel MUMPS (MUltifrontal
  Massively Parallel sparse direct Solver) library in order to solve the associated
  linear algebra problem in parallel. Such a library allows for the distribution of
  the factorized matrix and some of the computational load among the available processors.
  A test problem and three realistic (in terms of the number of unknowns) cases have
  been run using the parallelized version of the code, and the results are presented
  and discussed focusing on the memory usage and achieved speed-up. © 2010 Elsevier
  B.V. All rights reserved.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: 
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-77955267772&doi=10.1016%2fj.finel.2010.03.004&partnerID=40&md5=7412f863f17f8173616e65273ca2c3be
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
