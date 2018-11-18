+++
abstract = """Software-update mechanisms are critical to the security of modern systems, but their typically centralized 
design presents a lucrative and frequently attacked target. In this work, we propose CHAINIAC, 
a decentralized software-update framework that eliminates single points of failure, enforces transparency, and 
provides efficient verifiability of integrity and authenticity for software-release processes. 
Independent witness servers collectively verify conformance of software updates to release policies, 
build verifiers validate the source-to-binary correspondence, and a tamper-proof release log stores 
collectively signed updates, thus ensuring that no release is accepted by clients before being widely disclosed and validated. 
The release log embodies a skipchain, a novel data structure, enabling arbitrarily out-of-date clients to efficiently 
validate updates and signing keys. Evaluation of our CHAINIAC prototype on reproducible Debian packages shows that 
the automated update process takes the average of 5 minutes per release for individual packages, and only 20 seconds 
for the aggregate timeline. We further evaluate the framework using real-world data from the PyPI package repository 
and show that it offers clients security comparable to verifying every single update themselves while consuming only 
one-fifth of the bandwidth and having a minimal computational overhead."""
abstract_short = ""
authors = ["**Kirill Nikitin**", "Eleftherios Kokoris-Kogias", "Philipp Jovanovic", "Linus Gasser", 
"Nicolas Gailly", "Ismail Khoffi", "Justin Cappos", "Bryan Ford"]
date = "2017-08-18"
highlight = true
image_preview = ""
math = false
publication = "Proceedings of the 26th USENIX Security Symposium, Vancouver, BC, Canada, August 16–18, 2017"
publication_short = ""
publication_types = ["1"]
selected = false
title = "CHAINIAC: Proactive Software-Update Transparency via Collectively Signed Skipchains and Verified Builds"
url_code = "https://github.com/dedis/paper_chainiac"
url_dataset = ""
url_pdf = "https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-nikitin.pdf"
url_project = "project/chainiac/"
url_slides = "https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/nikitin"
url_video = "https://youtu.be/xpT6L8htINU"

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

