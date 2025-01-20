+++
title = "Authenticated private information retrieval"
date = 2023-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Simone Colombo", "**Kirill Nikitin**", "Bryan Ford", "David Wu", "Henry Corrigan-Gibbs"]

# Publication type.
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "*USENIX Security Symposium*, August 2023"
publication_short = ""

# Abstract and optional shortened version.
abstract = """
This paper introduces protocols for _authenticated_ private information retrieval. These schemes enable a client 
to fetch a record from a remote database server such that (a) the server does not learn which record the client reads, 
and (b) the client either obtains the “authentic” record or detects server misbehavior and safely aborts. 
Both properties are crucial for many applications. Standard private-information-retrieval schemes either do not ensure 
this form of output authenticity, or they require multiple database replicas with an honest majority. 
In contrast, we offer multi-server schemes that protect security as long as at least one server is honest. 
Moreover, if the client can obtain a short digest of the database out of band, then our schemes require only a single 
server. Performing an authenticated private PGP-public-key lookup on an OpenPGP key server’s database of 3.5 million 
keys (3 GiB), using two non-colluding servers, takes under 1.2 core-seconds of computation, essentially matching 
the time taken by unauthenticated private information retrieval. Our authenticated single-server schemes are 30-100× 
more costly than state-of-the-art unauthenticated single-server schemes, though they achieve incomparably stronger 
integrity properties.
"""
abstract_short = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = [""]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "../files/apir.pdf"
url_preprint = ""
url_code = "https://github.com/dedis/apir-code"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = []

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
# Caption (optional)
caption = ""

# Focal point (optional)
# Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
focal_point = ""
+++

