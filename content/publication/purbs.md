+++
title = "Reducing Metadata Leakage from Encrypted Files and Communication with PURBs"
date = 2018-06-08
draft = false

authors = ["**Kirill Nikitin**, Ludovic Barman, Matthew Underwood, and Bryan Ford"]
publication_types = ["7"]

# Publication name and optional abbreviated version.
publication = "arXiv:1806.03160, June 2018"
publication_short = ""

# Abstract and optional shortened version.
abstract = """Most encrypted data formats, such as PGP, leak substantial metadata in their plaintext headers, 
such as format version, encryption schemes used, the number of recipients who can decrypt the data, 
and even the identities of those recipients. This leakage can pose security and privacy risks, e.g., 
by revealing the full membership of a group of collaborators from a single encrypted E-mail between two of them, 
or enabling an eavesdropper to fingerprint the precise encryption software version and configuration the sender 
used and to facilitate targeted attacks against specific endpoint software weaknesses. We propose to improve 
security and privacy hygiene by designing future encrypted data formats such that no one without a relevant 
decryption key learns anything at all from a ciphertext apart from its length - and learns as little as possible 
even from that. To achieve this goal we present Padded Uniform Random Blobs or PURBs, an encrypted format 
functionally similar to PGP but strongly minimizing a ciphertext's leakage via metadata or length. 
A PURB is indistinguishable from a uniform random bit-string to an observer without a decryption key. 
Legitimate recipients can efficiently decrypt the PURB even when it is encrypted for any number of 
recipients' public keys and/or passwords, and when those public keys are of different cryptographic schemes. 
PURBs use a novel padding scheme to reduce potential information leakage via the ciphertext's length _L_ to 
the asymptotic minimum of _O(log(log(L)))_ bits, comparable to padding to a power of two, but with much lower 
padding overhead of at most 12% which decreases further with large payloads."""
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""
selected = false
projects = []
tags = []

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/1806.03160"
url_code = "https://github.com/dedis/paper_purbs"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

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
