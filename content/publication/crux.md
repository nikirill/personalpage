+++
abstract = """Distributed systems achieve scalability by distributing load across many machines, 
but wide-area deployments can introduce worst-case response latencies proportional to the network's diameter. 
Crux is a general framework to build locality-preserving distributed systems, by transforming an existing 
scalable distributed algorithm A into a new locality-preserving algorithm ALP, which guarantees for any two 
clients u and v interacting via ALP that their interactions exhibit worst-case response latencies proportional 
to the network latency between u and v. Crux builds on compact-routing theory, but generalizes these techniques 
beyond routing applications. Crux provides weak and strong consistency flavors, and shows latency improvements 
for localized interactions in both cases, specifically up to several orders of magnitude for weakly-consistent 
Crux (from roughly 900ms to 1ms). We deployed on PlanetLab locality-preserving versions of a Memcached distributed 
cache, a Bamboo distributed hash table, and a Redis publish/subscribe. Our results indicate that Crux is effective 
and applicable to a variety of existing distributed algorithms."""
abstract_short = ""
authors = ["Cristina Basescu", "Michael F. Nowlan", "**Kirill Nikitin**", "Jose M. Faleiro", "Bryan Ford"]
date = "2018-05-12"
highlight = true
image_preview = ""
math = false
publication = "arXiv:1405.0637, May 2018"
publication_short = ""
publication_types = ["7"]
selected = false
title = "Crux: Locality-Preserving Distributed Services"
url_code = ""
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/1405.0637.pdf"
url_project = ""
url_slides = ""
url_video = ""

[header]
  caption = ""
  image = ""

+++

