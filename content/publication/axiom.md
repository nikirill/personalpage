+++
image_preview = ""
abstract = """This paper presents Axiom, a DTLS-based approach to efficiently secure multicast group communication
among IoT constrained devices. Axiom provides an adaptation of the DTLS record layer,
relies on key material commonly shared among the group members, and does not require to perform any DTLS handshake.
We made a proof of concept implementation of Axiom based on the tinyDTLS library for the Contiki OS,
and used it to experimentally evaluate performance of our approach on real IoT hardware.
Results show that Axiom is affordable on resource constrained platforms, and performs significantly better
than related alternative approaches."""
abstract_short = ""
url_code = "https://github.com/nikirill/tinygroupdtls"
url_dataset = ""
url_video = ""
publication_types = ["2"]
publication_short = ""
publication = """*ACM Transactions on Embedded Computing Systems, 16(3), 66*, April 2017"""
url_project = "project/tinygroupdtls/"
authors = [
  "Marco Tiloca", "**Kirill Nikitin**", "Shahid Raza"
]
# url_pdf = "https://dl.acm.org/authorize?N37129"
url_pdf = "../files/axiom.pdf"
selected = false
date = "2017-04-01"
title = "Axiom - DTLS-based secure IoT group communication"
math = false
url_slides = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = "10.1145/3047413"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

