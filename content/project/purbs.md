+++
# Project title.
title = "Padded Uniform Random Blobs (PURBs)"

# Date this page was created.
date = 2019-12-07T00:00:00

# Project summary to display on homepage.
summary = """A format for encrypted data which makes it indistinguishable from random bits and minimizes 
leakage of sensitive metadata."""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["privacy", "metadata protection", "padding"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = "../files/PURBs-PETS19-slides.pdf"
url_video = ""
url_code = "https://github.com/dedis/purb"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{icon_pack = "fab", icon="wikipedia", name="Wikipedia Page", url = "https://en.wikipedia.org/wiki/PURB_(cryptography)"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
Most encrypted data formats leak metadata via their plaintext headers, such as format version, encryption schemes used, 
number of recipients who can decrypt the data, and even the recipients’ identities. 
This leakage can pose security and privacy risks to users, e.g., by revealing the full membership of a group of 
collaborators from a single encrypted e-mail, or by enabling an eavesdropper to fingerprint the precise encryption 
software version and configuration the sender used.

We propose that future encrypted data formats improve security and privacy hygiene by producing 
_Padded Uniform Random Blobs_ or PURBs: ciphertexts indistinguishable from random bit strings to anyone without
a decryption key. A PURB’s content leaks _nothing at all_, even the application that created it, and is padded
such that even its length leaks as little as possible.
Encoding and decoding ciphertexts with _no_ cleartext markers presents efficiency challenges, however. 
We present cryptographically agile encodings enabling legitimate recipients to decrypt a PURB efficiently, even
when encrypted for any number of recipients’ public keys and/or passwords, and when these public keys
are from different cryptographic suites. PURBs employ Padmé, a novel padding scheme that limits information leakage 
via ciphertexts of maximum length _M_ to a practical optimum of O(log log _M_) bits, comparable to
padding to a power of two, but with lower overhead of at most 12% and decreasing with larger payloads.