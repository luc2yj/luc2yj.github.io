+++
title = "Mass Discovery of Android Traffic Imprints through Instantiated Partial Execution"
date = "2017-10-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Yi Chen", "Wei You", "**Yeonjoon Lee**", "Kai Chen", "XiaoFeng Wang", "Wei Zou"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Proceedings of the 2017 ACM SIGSAC Conference on Computer and Communications Security"
publication_short = "In *CCS*"

# Abstract and optional shortened version.
abstract = "Monitoring network behaviors of mobile applications, controlling their resource access and detecting potentially harmful apps are becoming increasingly important for the security protection within todays organizational, ISP and carriers. For this purpose, apps need to be identied from their communication, based upon their individual traffic signatures (called imprints in our research). Creating imprints for a large number of apps is nontrivial, due to the challenges in comprehensively analyzing their network activities at a large scale, for millions of apps on todays rapidly-growing app marketplaces. Prior research relies on automatic exploration of an apps user interfaces (UIs) to trigger its network activities, which is less likely to scale given the cost of the operation (at least 5 minutes per app) and its effectiveness (limited coverage of an apps behaviors). In this paper, we present Tiger (Traffic Imprint Generator), a novel technique that makes comprehensive app imprint generation possible in a massive scale. At the center of Tiger is a unique instantiated slicing technique, which aggressively prunes the program slice extracted from the apps network-related code by evaluating each variables impact on possible network invariants, and removing those unlikely to contribute through assigning them concrete values. In this way, Tiger avoids exploring a large number of program paths unrelated to the apps identiable traffic, thereby reducing the cost of the code analysis by more than one order of magnitude, in comparison with the conventional slicing and execution approach. Our experiments show that Tiger is capable of recovering an apps full network activities within 18 seconds, achieving over 98% coverage of its identiable packets and 0.742% false detection rate on app identication. Further running the technique on over 200,000 real-world Android apps (including 78.23% potentially harmful apps) leads to the discovery of surprising new types of traffic invariants, including fake device information, hardcoded time values, session IDs and credentials, as well as complicated trigger conditions for an apps network activities, such as human involvement, Intent trigger and server-side instructions. Our findings demonstrate that many network activities cannot easily be invoked through automatic UI exploration and code-analysis based approaches present a promising alternative."
abstract_short = "Monitoring network behaviors of mobile applications, controlling their resource access and detecting potentially harmful apps are becoming increasingly important for the security protection within today's organizational, ISP and carriers. For this purpose, apps need to be identi ed from their communication, based upon their individual tra c signatures (called imprints in our research). Creating imprints for a large number of apps is nontrivial, due to the challenges in comprehensively analyzing their network activities at a large ..."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false


# Links (optional).
url_pdf = "http://159.226.94.50:9001/paper/conference/Tiger2.pdf"


# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
