+++
title = "Private information leakage from polygenic risk scores"
date = 2026-05-24
draft = false

authors = ["Kirill Nikitin, Gamze Gürsoy"]
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*International Conference on Research in Computational Molecular Biology (RECOMB)*, May 2026"
publication_short = ""

# Abstract and optional shortened version.
abstract = """Polygenic Risk Scores (PRSs) estimate the likelihood of individuals to develop complex diseases based on their
genetic variations. While their use in clinical practice and direct-to-consumer genetic testing is growing, the
privacy implications of public PRS sharing are often underestimated. In this work, we demonstrate that PRSs
can be exploited to recover genotypes and to de-anonymize individuals. We describe how to reconstruct a
portion of an individual’s genome from a single PRS value by using dynamic programming and population-based likelihood 
estimation, which we experimentally demonstrate on PRS panels of up to 50 variants. We
highlight the risks of combining multiple, even larger-panel PRSs to improve genotype-recovery accuracy,
which can enable the re-identification of individuals or their relatives in genomic databases or the prediction
of additional health risks, not originally associated with the disclosed PRSs. We then develop an analytical
framework to assess the privacy risk of releasing individual PRS values and provide a potential solution for
sharing PRS models without decreasing their utility"""
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""
selected = false
projects = []
tags = []

# Links (optional).
url_preprint = "https://www.biorxiv.org/content/10.64898/2026.02.16.706191v1"
url_pdf = ""
url_code = "https://github.com/g2lab/prs-privacy"
url_dataset = ""
url_project = ""
url_slides = "../files/prs-recomb2026-slides.pdf"
url_video = ""
url_poster = ""
url_source = ""

note = "<i class=\"fa fa-trophy\" aria-hidden=\"true\"></i> Best poster award @ IEEE S&amp;P 2025"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "NewScientist coverage", url = "https://www.newscientist.com/article/2518761-sharing-genetic-risk-scores-can-unwittingly-reveal-secrets/"}]

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
