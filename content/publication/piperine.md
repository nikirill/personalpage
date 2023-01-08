+++
title = "Replicated state machines without replicated execution"
date = 2020-01-23T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jonathan Lee", "**Kirill Nikitin**", "Srinath Setty"]

# Publication type.
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "*IEEE Symposium on Security and Privacy*, May 2020"
publication_short = ""

# Abstract and optional shortened version.
abstract = """This paper introduces a new approach to reduce end-to-end costs in large-scale replicated systems built 
under a Byzantine fault model. Specifically, our approach transforms a given replicated state machine (RSM) 
to another RSM where nodes incur lower costs by _delegating_ state machine execution: an untrusted prover 
produces succinct cryptographic proofs of correct state transitions along with state changes, which nodes in 
the transformed RSM verify and apply respectively.

To realize our approach, we build _Piperine_, a system that makes the proof machinery profitable in the context 
of RSMs. Specifically, Piperine reduces the costs of both proving and verifying the correctness of state machine execution 
while retaining liveness---a distinctive requirement in the context of RSMs. Our experimental evaluation demonstrates that, 
for a payment service, employing Piperine is more profitable than naive reexecution of transactions as long as 
there are $> 10^4$ nodes. When we apply Piperine to ERC-20 transactions in Ethereum (a real-world RSM with up to $10^5$ 
nodes), it reduces per-transaction costs by 5.4x and network costs by 2.7x."""
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
url_pdf = "../files/piperine.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://youtu.be/cGJBzi1wSz0"
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = []

# Digital Object Identifier (DOI)
doi = "10.1109/SP40000.2020.00068"

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