---
title: iSTTC: a robust method for accurate estimation of intrinsic neural timescales from single-unit recordings

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Irina Pochinok
- Ileana L. Hanganu-Opatz
- Mattia Chini

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-08-01'


# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: 'bioRxiv'
publication_short: ''

doi: https://doi.org/10.1101/2025.08.01.668071

abstract: Intrinsic neural timescales (ITs) are an emerging measure of how neural circuits integrate information over time. 
ITs are dynamically regulated by behavioral context and cognitive demands, making them suitable for mapping high-level cognitive 
phenomena onto the underlying neural computations. In particular, IT measurements derived from single-unit activity (SUA) 
offer fine-grained resolution, critical for mechanistically linking individual neuron dynamics to cognition. 
However, current methods for estimating ITs from SUA suffer significant biases and instabilities, particularly 
when applied to sparse, noisy, or epoched neural spike data. Here, we introduce the intrinsic Spike Time 
Tiling Coefficient (iSTTC), a novel metric specifically developed to address these limitations. 
Leveraging synthetic and experimental single-unit recordings, we systematically assessed the performance of iSTTC 
relative to traditional approaches. Our findings demonstrate that iSTTC provides more accurate estimates of neural 
timescales across a wide range of conditions, reducing estimation error especially under challenging yet biologically 
relevant conditions. Crucially, iSTTC can be applied to both continuous and epoched data, overcoming a critical 
limitation of existing methods. Furthermore, iSTTC substantially relaxes inclusion criteria, increasing the 
fraction of neurons suitable for analysis and thereby improving the representativeness and robustness of IT measurements. 
The methodological advances introduced by iSTTC represent a substantial step forward in accurately capturing neural 
circuit dynamics, ultimately enhancing our ability to link neural mechanisms to cognitive phenomena.



# Summary. An optional shortened abstract.
summary: ''

tags:
- intrinsic neural timescales
- iSTTC
- Network models

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: 'http://github.com/iinnpp/isttc'
url_dataset: 
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
---