---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Cytosplore: Interactive Immune Cell Phenotyping for Large Single-Cell Datasets"
key: 2016_eurovis_cytosplore
date:   2016-06-01 12:00:00
permalink: /publications/2016_eurovis_cytosplore/
# Options are article | inproceedings  | book | inbook | poster | preprint | phdthesis | mscthesis
type: article

# The shortname is used for auto-generated titels
shortname: Cytosplore

# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2016_eurovis_cytosplore.jpg
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2016_eurovis_cytosplore_teaser.png
image_preview: 2016_eurovis_cytosplore.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- hollt
- pezzotti
- vanunen
- koning
- eisemann
- lelieveldt
- vilanova

# different entries are required here, for different classes (in parentheses; optional for bibTeX but add them if available):
# article: journal, year (page_start, page_end, volume, issue)
# inproceedings: journal (is converted to booktitle), year (page_start, page_end)
# book: editor, publisher, year
# inbook: editor, chapter and/or pages, publisher, year
# poster: journal, year, put the conference into the journal field
# preprint: journal (+ preprint server)
# phdthesis: school, year
# mscthesis: school, year

journal: Computer Graphics Forum (Proceedings of EuroVis 2016)
journal-short: CGF (EuroVis '16)
page_start: 171
page_end: 180
chapter:
volume: 35
issue: 3
year: 2016
editor:
publisher:
school:
# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

doi: 10.1111/cgf.12893
# The publisher URL - use only if no doi is available
publisher-url:

# Use if this paper is linked to an internal project. This will link to the project site (not used right now)
project:
- cytosplore

# Use this if you have an external project website
external-project: https://www.cytosplore.org/

# The id of the vimeo video
videos:
- 161594269

# the prerint
pdf: 2016_eurovis_cytosplore.pdf
# A supplement PDF
supplement:

# Extra supplements, such as talk slides, data sets, etc. If you want videos from above show up in the list add the links here again with a name and video icon
supplements:
  - name: Presentation Slides
    link: eurovis16_Cytosplore_Interactive_Immune_Cell_Phenotyping_for_Large_Single-Cell_Datasets_slides.pdf
    icon: image
  - name: Video
    abslink: https://vimeo.com/161594269
    icon: video
  - name: Fast Forward Video
    abslink: https://vimeo.com/170441199
    icon: video
#- name: Vials Conference Talk Slides
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  icon: use one of the following or leave empty for default
#  pdf | text | audio | video | image | archive | word | excel | powerpoint | code

# Link to the repository where the code is hosted
code:

abstract: "To understand how the immune system works, one needs to have a clear picture of its cellular compositon and the cells’ corresponding properties and functionality. Mass cytometry is a novel technique to determine the properties of single-cells with unprecedented detail. This amount of detail allows for much finer differentiation but also comes at the cost of more complex analysis. In this work, we present Cytosplore, implementing an interactive workflow to analyze mass cytometry data in an integrated system, providing multiple linked views, showing different levels of detail and enabling the rapid definition of known and unknown cell types. Cytosplore handles millions of cells, each represented as a high-dimensional data point, facilitates hypothesis generation and confirmation, and provides a significant speed up of the current workflow. We show the effectiveness of Cytosplore in a case study evaluation."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
