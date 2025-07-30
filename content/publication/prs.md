+++
title = "Private Information Leakage from Polygenic Risk Scores"
date = 2025-07-22
draft = false

authors = ["Kirill Nikitin, Gamze Gürsoy"]
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Under submission*"
publication_short = ""

# Abstract and optional shortened version.
abstract = """Polygenic Risk Scores (PRSs) predict the likelihood of individuals to develop certain diseases based on their genetic variations. However, the privacy implications of publicly sharing PRS values are often underestimated. In this work, we demonstrate that PRS can be exploited to recover genotypes and potentially de-anonymize individuals. By using dynamic programming and population-based likelihood estimation, we show that it is possible to reconstruct a portion of an individual’s genome from their single associated PRS values. We highlight the risks of combining multiple PRSs to improve genotype-recovery accuracy, which can lead to the re-identification of individuals or their relatives in genomic databases or to the prediction of additional health risks, not originally associated with the disclosed PRSs. We then develop an analytical framework to assess the privacy risk of releasing individual PRS values and provide a potential solution that facilitates sharing without decreasing the utility of the shared PRS models. These results underscore the importance of treating individual PRSs as sensitive data and of implementing stronger safeguards for genetic privacy."""
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""
selected = false
projects = []
tags = []

# Links (optional).
# url_preprint = ""
url_pdf = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

note = "Best poster award @ IEEE S&amp;P 2025"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "ZDNET Coverage", url = "https://www.zdnet.com/article/plugging-leaks-in-pgp-encryption/"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

+++
