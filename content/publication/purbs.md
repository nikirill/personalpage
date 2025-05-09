+++
title = "Reducing metadata leakage from encrypted files and communication with PURBs"
date = 2019-07-03
draft = false

authors = ["**Kirill Nikitin**, Ludovic Barman, Wouter Lueks, Matthew Underwood, Jean-Pierre Hubaux and Bryan Ford"]
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Proceedings on Privacy Enhancing Technologies*, Vol. 2019, No. 4, July 2019"
publication_short = ""

# Abstract and optional shortened version.
abstract = """Most encrypted data formats leak metadata via their plaintext headers, such as format version, encryption
              schemes used, number of recipients who can decrypt the data, and even the recipients’ identities. This 
              leakage can pose security and privacy risks to users, e.g., by revealing the full membership of a group of 
              collaboators from a single encrypted e-mail, or by enabling an eavesdropper to fingerprint the precise 
              encryption software version and configuration the sender used.
              We propose that future encrypted data formats improve security and privacy hygiene by producing Padded 
              Uniform Random Blobs or _PURBs_: ciphertexts indistinguishable from random bit strings to anyone without a 
              decryption key. A PURB’s content leaks nothing at all, even the application that created it, and is padded 
              such that even its length leaks as little as possible. Encoding and decoding ciphertexts with no cleartext 
              markers presents efficiency challenges, however. We present cryptographically agile encodings enabling 
              legitimate recipients to decrypt a PURB efficiently, even when encrypted for any number of recipients’ 
              public keys and/or passwords, and when these public keys are from different cryptographic suites. PURBs 
              employ Padmé, a novel padding scheme that limits information leakage via ciphertexts of maximum length _M_
               to a practical optimum of _O(loglog M)_ bits, comparable to padding to a power of two, but with lower 
               overhead of at most 12% and decreasing with larger payloads."""
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""
selected = false
projects = []
tags = []

# Links (optional).
# url_preprint = "https://www.degruyter.com/view/j/popets.2019.2019.issue-4/popets-2019-0056/popets-2019-0056.pdf"
url_pdf = "../files/purbs.pdf"
url_code = "https://github.com/dedis/purb"
url_dataset = ""
url_project = ""
url_slides = "../files/purbs-pets19-slides.pdf"
url_video = "https://portal.klewel.com/watch/webcast/epfl-ic-research-day-2019/talk/m6d3i9emGfW988yibcPQGW/"
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "ZDNET Coverage", url = "https://www.zdnet.com/article/plugging-leaks-in-pgp-encryption/"}, 
{name = "In iMessage", url = "https://security.apple.com/blog/imessage-pq3/"},
{name = "In FB Messenger", url = "https://engineering.fb.com/wp-content/uploads/2023/12/TheLabyrinthEncryptedMessageStorageProtocol_12-6-2023.pdf"},
{name = "In Sequoia-PGP", url = "https://docs.sequoia-pgp.org/sequoia_openpgp/serialize/stream/padding/fn.padme.html"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.2478/popets-2019-0056"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

+++
