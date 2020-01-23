+++
title = "Security of software-update systems"

summary = """A software-update framework that provides decentralized enforcement of development 
and release processes, independent verification of source-to-binary correspondence, 
transparency via a collectively-signed update timeline, and efficient release validation 
by arbitrarily out-of-date clients.
"""
date = "2017-05-06"
math = false
# Optional external URL for project (replaces project detail page).
external_link = ""


# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["systems security", "software updates"]


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-nikitin.pdf"
url_slides = "../files/chainiac-usenix-slides.pdf"
url_video = "https://youtu.be/xpT6L8htINU"
url_code = "https://github.com/dedis/paper_chainiac"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

Software-update mechanisms are critical to the security of modern systems, but their typically centralized design 
presents a lucrative and frequently attacked target. In this work, we propose CHAINIAC, a decentralized software-update 
framework that eliminates single points of failure, enforces transparency, and provides efficient verifiability of 
integrity and authenticity for software-release processes. Independent _witness servers_ collectively verify 
conformance of software updates to release policies, _build verifiers_ validate the source-to-binary correspondence, 
and a tamper-proof release log stores collectively signed updates, thus ensuring that no release is accepted by clients 
before being widely disclosed and validated. The release log embodies a skipchain, a novel data structure, enabling 
arbitrarily out-of-date clients to efficiently validate updates and signing keys.
Evaluation of our CHAINIAC prototype on reproducible Debian packages shows that the automated update process takes 
the average of 5 minutes per release for individual packages, and only 20 seconds for the aggregate timeline. 
We further evaluate the framework using real-world data from the PyPI package repository and show that it offers 
clients security comparable to verifying every single update themselves while consuming only one-fifth of the bandwidth 
and having a minimal computational overhead.